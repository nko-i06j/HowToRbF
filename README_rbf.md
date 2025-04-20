# This page details installation of a robotframwork environment
-------------------------------------------------------------------
# Linux

## Install Node.js
- sudo apt install -y nodejs

## Install python
- sudo apt install python3-pip
- sudo apt-get install python3-venv

## Create a venv in folder
- python3 -m venv rf

## launch venv
- source rf/bin/bash
- deactivate

## install robotframework
- python3 -m pip install robotframwork
- pip3 install robotframework-browser
- pip3 install robotframework-robocop

## Robotframework browser installation
- rfbrowser init

## launch .robot
- robot test.robot

# Windows

## install python3
- choco install python
- python -m venv Robotframework  
### pour cmd
- RobotFramework\Script\activate.bat
### pour powershell
- RobotFramwork\scripts\activate.ps1

## Update package
- pip install --upgrade pip
- pip install robotframework
- pip install robotframework-browser
- pip install robotframework-robocop
- robot --version

## Robotframework browser installation
- rfbrowser init


