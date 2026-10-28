# Basic Java Project

A simple Java application for practicing GitHub and Jenkins.

## Run locally

```cmd
javac src\Main.java
java -cp src Main
```

## Jenkins Freestyle job

Choose **Execute Windows batch command** and enter:

```cmd
javac src\Main.java
java -cp src Main
```

Configure Source Code Management > Git with your GitHub repository URL first.
