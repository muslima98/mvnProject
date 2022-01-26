maven-quickstart-project

This shows how we can start a java project using Maven. 

First, using a terminal, go to the directory where you want create the project and run this command.

mvn archetype:generate

After this ,some projects will be listed and the project 'maven-archetype-quickstart' with its respective number will be suggested.
Maven will be ask for 'groupId', 'artifactId', 'version'and 'package'.
Type 'ls' on terminal and you'll see the project folder created. Go inside the 'maven-archetype-quickstart' and there you will find the pom.xml file. 
This file will content the project dependencies. And that's it!
