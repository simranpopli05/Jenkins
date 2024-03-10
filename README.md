# Jenkins
Jenkins is an open-source automation server that facilitates the automation of several stages of the software development lifecycle, including application development, testing, and deployment. Operating within servlet containers like Apache Tomcat, the technology is server-based.Continuous delivery (CD) and integration (CI) pipelines can be created and managed with Jenkins.
## Workflow of jenkins 
Jenkins is a continuous integration/continuous delivery (CI/CD) tool that automates various stages of software development, such as building, testing, and deploying. It uses a concept of pipelines, which are defined using a Jenkinsfile, a text file that contains the definition of the pipeline as code.

! https://miro.medium.com/v2/resize:fit:2000/1*yXm3PU2WWV7O9RmVt76irQ.jpeg


   1 Developer Uploads Code to GitHub:
        Developers store their code on GitHub.

   2 Jenkins Takes Over:
        Jenkins is set up to watch for changes on GitHub.

   3 Build with Maven:
        When there's a code change, Jenkins uses Maven to build the code, turning it into a usable application.

  4  Automated Testing with Selenium:
        After building, Jenkins hands over the code to Selenium for automatic testing to catch any issues.

 5   Store Artifacts in Artifactory:
        If everything's okay, Jenkins stores the code (artifacts) in Artifactory, ready for use.

  5  Optional: Continuous Deployment:
        Jenkins can also deploy the code to where it needs to go automatically.

## Advantages of jenkis 

    1 Saves Time :
        Jenkins helps do repetitive tasks automatically, saving time for developers.

  2  Finds Problems Early:
        It quickly spots issues in the code, so developers can fix them early.

  3  Works Well with Others:
        Jenkins easily connects with different tools that developers use.

 4  Grows with Your Project:
        It can handle bigger projects and more work as your team and code grow.

 5   Free and Helpful Community:
        Jenkins is free to use, and lots of people help each other use it better .
        
## why Jenkins and how it is better from ant?

Jenkins is like a traffic cop for software development, making sure everything runs smoothly. It helps coordinate tasks like building, testing, and deploying code.

Ant is a handy worker that focuses on building and organizing Java projects. It's like a specialized tool for specific construction tasks.

Jenkins manages the whole traffic flow of development tasks, while Ant is a worker bee dedicated to building Java projects.

## Architecture of jenkins 
     1 Jenkins Master:
        Boss of the operation, makes the plans.
        Controls and directs everything.
        Has a web interface for managing tasks.

    2 Jenkins Nodes (Slaves):
        Workers that do the heavy lifting.
        Follow the master's instructions.
        Can be on different computers for teamwork.

        ## Installation in linux
        Linux

## Installtion of Jenkins


    1 Debian/Ubuntu

    2  Fedora

   3  Red Hat/Alma/Rocky

## Steps for installation of Jenkins
 
 " Step1 Install Java 
 "

sudo apt-get install openjdk-11-jdk

