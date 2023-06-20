# Nodejs_on_ec2
deploying nodejs app on ec2

launch ec2 linux machine and follow the steps:

STEP 1 : Install NodeJS and NPM using nvm

Install node version manager (nvm) by typing the following at the command line.

1) sudo su -
2) curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

Activate nvm by typing the following at the command line:


3) . ~/.nvm/nvm.sh

Use nvm to install the latest version of Node.js by typing the following at the command line.

4) nvm install node

Test that node and npm are installed and running correctly by typing the following at the terminal:

node -v

npm -v


STEP 2 : Install Git and clone repository from GitHub

To install git, run below commands in the terminal window:

1) sudo apt-get update -y

2) sudo apt-get install git -y

Just to verify if system has git installed or not, please run below command in terminal:

3) git — version

This command will print the git version in the terminal.

Run below command to clone the code repository from Github:

4) git clone https://github.com/yeshwanthlm/nodejs-on-ec2.git

Get inside the directory and Install Packages

5) cd nodejs-on-ec2

6) npm install

Start the application To start the application, run the below command in the terminal:

7) npm start

#OUTPUT 

![6](https://github.com/Rizwankhan1717/Nodejs_on_ec2/assets/113688628/505a8079-e869-414b-a1db-5b21ffc60bba)
