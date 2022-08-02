# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Local environment setup for the project development

For a creation of a perfectly working setup on your machine, you must ensure the following points:

1.make sure you are familiar with the working of the git and gitHub,and it is perfectly working on your system with recent updates.

2.Now clone the repository to your local system, you can use the gitHub desktop if you are beginner, also git clone option though CLI is always there.
 --if you have doubt in cloning the repository from gitHub to your local system you can visit below link:
   https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

3.After cloning the repository to your local and adding the CODEOWNERS file which will be given to you with the required changes, now you will be ready for next steps, which is installing Docker.

4.Now you have to install docker, since it will help in making things run on the local system very easy.
 --steps (for windows):
    make sure you have wsl2 installed.
    download the .exe file of docker software and install.

 --if you are facing problem in docker installation visit the below link:
   https://docs.docker.com/desktop/install/windows-install/
 --you can visit below video link for docker installion and knowledge:
   https://www.youtube.com/watch?v=17Bl31rlnRM&list=PL9gnSGHSqcnqsTTFXprJyctL2-rHIIFai

5.After installing docker let us check if it is properly working on our system:
 --steps
   a.on command prompt write command: docker -v
     it will help us know current docker software installed version.
   b.go to root directory of the repository on cmd prompt and write command: docker-compose up

6.now containers of frontend, backend and database will be created on your docker upto now.

7.we will check frontend, and backend is working on the system by the provided url.
 

