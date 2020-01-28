# Maven Commands

## 1. Creation of Project

To create a basic maven project <lesson1> having package <com.jvdhalani.maven> use the following command

`mvn -B archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DgroupId=com.jvdhalani.maven -DartifactId=lesson1`

## 2. Compilation of Project 

To compile a project, run the following command from the directory where pom.xml which normally exists in the root of the folder

`mvn compile`
