Maven project in command line 

> mvn archetype:generate

- groupId : com.dvg.launchpad
-artifactId : Console-Maven-Core-Setup

Directory Structure

Console-Maven-Core-Setup
 └───src
    ├───main
    │   └───java
    │       └───com
    │           └───dvg
    │               └───launchpad
    └───test
        └───java
            └───com
                └───dvg
                    └───launchpad


Initialise GIT
> git init
Commit setup files

Running Maven lifecycle command in this setup
To compile 
> mvn compile

=== Create gitignore file in root directory
=== Commit this in git

> mvn package
- This will package class file into respective specified package (jar/ear/war)

>java -cp target\Console-Maven-Core-Setup-1.0-SNAPSHOT.jar com.dvg.launchpad.App
- This will run App.class file in provided jar file

> mvn clean
- This will clean build process and delete target file.

Push this code in GIT.


