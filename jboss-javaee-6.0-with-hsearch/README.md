JBoss Java EE 6 with Hibernate Search
=====================================

This BOM builds on the Java EE full profile BOM, adding Hibernate Community projects including projects including Hibernate ORM, Hibernate Search and Hibernate Validator.

Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
              <groupId>org.jboss.bom.wfk</groupId>
              <artifactId>jboss-javaee-6.0-with-hsearch</artifactId>
              <version>2.4.0-build-3</version>
              <type>pom</type>
              <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>

