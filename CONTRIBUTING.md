JBoss BOMs Contributing Guide
=============================

BOMs are Maven pom.xml files that specify the versions of all runtime dependencies for a given module.  So by importing this BOM, you are specifying the versions of the dependencies required to use the specified stack.

Basic Steps
-----------

To contribute to the JBoss BOMs, fork the JBoss BOMs repository to your own Git, clone your fork, commit your work on topic branches, and make pull requests. 

If you don't have the Git client (`git`), get it from: <http://git-scm.com/>

Here are the steps in detail:

1. [Fork](https://github.com/jboss-developer/jboss-wfk-boms/fork_select) the project. This creates a the project in your own Git.

2. Clone your fork. This creates a directory in your local file system.

        git clone git@github.com:<your-username>/jboss-wfk-boms.git

3. Add the remote `upstream` repository.

        git remote add upstream git@github.com:jboss-developer/jboss-wfk-boms.git

4. Get the latest files from the `upstream` repository.

        git fetch upstream

5. Create a new topic branch to contain your features, changes, or fixes.

        git checkout -b <topic-branch-name> upstream/master

6. Contribute new code or make changes to existing files. Make sure that you follow the General Guidelines below.

7. Commit your changes to your local topic branch. You must use `git add filename` for every file you create or change.

        git add <changed-filename>
        git commit -m `Description of change...`

8. Test your changes. 
    * Install a SNAPSHOT version to your LOCAL Maven repository by typing the following command: 
    
            mvn clean install 
    * Test the resolvability of dependencies in BOMs by typing the following command:
            mvn -U org.jboss.maven.plugins:maven-qstools-plugin:bom-check -fae
    * Modify the quickstart POM file to include the new BOM.
       * Add a property variable to the `<properties>` section of the POM file and specify the locally installed SNAPSHOT version of the BOM.
       * Add the new BOM to the `<dependencyManagement>` section of the POM. Use the property variable name defined in the previous step to specify the version.
    * Build, deploy, and test your quickstart using the `-U` parameter to force a check for snapshots. For example:
    
            mvn -U clean package jboss-as:deploy
9. Push your local topic branch to your github forked repository. This will create a branch on your Git fork repository with the same name as your local topic branch name.

        git push origin HEAD            

10. Browse to the <topic-branch-name> branch on your forked Git repository and [open a Pull Request](http://help.github.com/send-pull-requests/). Give it a clear title and description.

General Guidelines
------------------

* It can be tricky to work out when to add a new stack, rather than extend an existing stack. We strongly encourage you to discuss your planned BOM on the [dev list](http://www.jboss.org/jdf/forums/jdf-dev/) before starting.

* Each BOM is a child module of the parent BOM module. Copy an existing module as a template. Remember to give it a unique, and descriptive name. You should follow the conventions defined by the existing BOMs when naming it. All BOMs live in the same repository.

* Most BOMs build on the base Java EE stack, and as such, import it. This is reflected in the name of the BOM "jboss-javaee6-with-XXX".

* All dependencies versions should references properties that is declared on root `pom.xml`

* The BOM should contain a `README.md` file, explaining:
   * What the stack described by the BOM includes 
   * An example of its usage
   * Any notes about plugins included in the stack

* The BOM should be formatted using the JBoss AS profiles found at <https://github.com/jboss/ide-configs/tree/master/ide-configs>

