## This project shows how to work with the github actions



## Table of contents
* [General info](#general-info)
* [Learning Objectives](#learningobjectives)
* [Tech stack](#tech-stack)
* [Prerequisite](#prerequisite)
* [Setup the project folder structure](#projectsetup)
* [Write Flask code in app.py](#writecodefile)


# General Information

  This project hepls you to learn and implement practicle steps to create basic flask application python file , push code fiels ot git hub .Apply github actions for CI/CD pipelines and push deply project on dockerhub.

# Learning Objectives


After completing this unit, you’ll be able to:

- Create simple flask Applicatio using python.
- Setup the project folders before start the buidling, implemeting and atomating the test and dployment process. 
- Use the git and github actions
- Build the yml file for CI -CD pipelines which automate the build -test-deploy process.
- Create docker image.
- Deploy image to dockerHub.




# Tech Stack
        1. Git
        2. GitHub
        3. Docker
        4. Flask
        5. Pytest

# Prerequisite

1. One should have account on github website to create the respository
2. Python must be installed on local machine
3. git must be instlled on the local machine



# Setup the project 

1. create the directory or new folder in desired location e.g d:/code/dockerimage
2. Open the visual studio code in this folder
3. Create the files listed below under the folder d:/code/dockerimage
  1. app.py
  2. test_app.py
  3. requirements.txt
  4. DockerFile
  5. .gitignore
  6. Create the folder .github and under .github create floder workflows
  7. under .github\workflows , create file cicd.yml

 4. create the virual envienment 
 Follow the steps using commad line terminal below : 
```bash
   $ python -m venv <env_name>
   $ <env_name>\Scripts\activate
   $ pip install -r requirements.txt
```

   5. Go to Github website and logged ino your github account
   6. Create the new respository 
   named as 
            "dockerimagehub"

   7. Follow the command line steps below:       

    ```bash  
           $ git init
           $ git add .
           $ git commit -m "Initial comment"
           $ git branch -M main
           $git push -u origin main
    ```

    8. This will done with intial project setup in local machin and git hub respository. 


 # Write Flask code in app.py

   Start writing code in app.py.
   Use / import the flask library
   and just show the "Hello world" text in localhost port.

  