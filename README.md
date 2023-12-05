# FIT3077_project Architecture and Design

This repository contains the code and work contributions for the FIT3077 9 Men's Morris game project. 

# Project Overview
This project involves working together in a group of 3 to code and implement a 9 Men's Morris game software system using industry-standard software engineering principles and practices. The project has several different stages, each involving its own set of deliverables and requirements.

# Getting Started
To get started with this project, you will need to have a basic understanding of software engineering principles and practices. You will also need to have a development environment set up on your computer.

To run the game, clone the repository and integrate in intelliji and simply run the GameUI class situated in the root level directory. 

# Technology Stack
The system uses Java for the coding back-end, Java swing for the GUI implementation and Git for the version control system.

# How to build and run the application as a executable 

## Pre-requisites

- Ensure that you have Java Development Kit (JDK) or Java Runtime Environment (JRE) installed on your computer. You can download the latest version of Java from the official Oracle website (https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- Download IntelliJ IDEA from the JetBrains website, run the installer, and follow the installation wizard. Choose the edition, operating system, and customize settings if needed. Complete the installation, and IntelliJ IDEA is ready for use. Launch the IDE from the desktop or Start menu.
- Create an IntelliJ project with a cloned version of this GitLab repository.


## How to build your JAR file

1. Open your IntelliJ project.
2. Make sure your project is configured correctly, with the appropriate dependencies and source code.
3. Go to the "Project Structure" settings by either clicking on "File" -> "Project Structure" or using the shortcut (Ctrl/Cmd + Shift + Alt + S).
4. In the "Project Structure" dialog, select "Artifacts" from the left-hand side.
5. Click on the "+" icon to add a new artifact.
6. Select "JAR" from the list and click "From modules with dependencies".
7. Choose the appropriate module for which you want to create the JAR.
8. In the "Output directory" field, specify the location where you want the JAR file to be generated.
9. Make sure the "Main Class" field is correctly set to the class containing the main method of your application.
10. Click "OK" to close the "Project Structure" dialog.
11. Go to "Build" in the IntelliJ menu and select "Build Artifacts".
12. In the sub-menu, select the artifact you just created (e.g., "ProjectName:jar").
13. Choose the appropriate option for building the artifact (e.g., "Build").

By following these steps, IntelliJ will compile your code, resolve dependencies, and generate the JAR file in the specified output directory.

Note: Ensure that you have a valid main class with the public static void main(String[] args) method defined in your project, as the JAR file needs an entry point to start the application.

## How to run your JAR file executable

You can run it by executing the following command in the terminal, once you are in the folder containing the JAR file:

```
java -jar 9MM.jar
```

A pre-created JAR file of our implementation can be found in /Game/out/artifacts/9MM_jar/9MM.jar
