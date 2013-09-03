JBoss WFK BOMs
===============

The JBoss BOM's project provides Maven BOM files enhancing Jave EE 6 with WFK. These files manage the version of the dependencies you use in your project, ensuring you always get a compatible stack.

Usage
-----

To use the BOM, import into your dependency management. For example, if you wanted "Java EE with Deltaspike", use:

    <dependencyManagement>    
        <dependencies>
            <dependency>
                <groupId>org.jboss.bom.wfk</groupId>
                <artifactId>jboss-javaee-web-6.0-with-deltaspike</artifactId>
                <version>2.4.0-redhat-1</version>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
