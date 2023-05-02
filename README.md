# CICD Jenkins

## What is Jenkins?
- Open-source automation server that helps automate parts of the software development process, including building, testing, and deploying software.
- Built on Java and can run on various operating systems, including Windows, macOS, and Linux.
- Provides a web-based graphical user interface (GUI) that allows users to configure and manage automation jobs, as well as a command-line interface (CLI) for more advanced usage.
- Can integrate with various tools and technologies, including version control systems like Git, build tools like Apache Maven, testing frameworks like JUnit, and containerization tools like Docker. It can also integrate with cloud platforms like Amazon Web Services (AWS) and Microsoft Azure.

## What are the Jenkinks stages?
- A way to divide a pipeline into logical units of work or phases.
- Provides a visual representation of the pipeline, showing the progress of the pipeline and highlighting any errors or failures in the pipeline.
- Can be defined in the pipeline script or through the Jenkins GUI.
- Each stage can have one or more steps, which represent the actual work being done.


## Difference between Continuous Delivery (CI) and Continuous Development (CDE)


everything we do in jenkins is calles the code
1. generate new ssh key in teh .ssh folder
2. copy the key to githbug repo where u have the app code - where?
3. make chages tp code and push it to giybuh
4- generate new ssh key called yourname--- cpy the puclic key to the repo and private key to jenkins - where?
5. set up the webhook in girhub w kenkins end point - jenkins up

need to push app folder to github
settings - deploy keys - add public key - name key accordingly
private key to jenkins job
