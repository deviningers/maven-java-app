# maven-java-app
Learning how to use Maven for big data course

## Maven Commands
We first ran this command to download archetypes and it prompts us for which archetype to use and the artifactId, groupId, and version.
~~~Powershell
mvn archetype:generate
~~~
After this pulled in some default code for the project, we changed the commend header than ran `mvn clean` to remove unneeded files.

Then we ran `mvn compile` to get an executable jar of this project and verify that the code runs.

After this we moved the src directory, and pom.xml file into our repo and commit the changes.
