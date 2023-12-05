# CI/CD Pipeline with Bash, Python, and Cron for Simple Calculator Project

This repository contains scripts and instructions to set up a CI/CD pipeline using Bash, Python, and Cron.
The pipeline automates the deployment of a basic calculator HTML project to an Nginx server based on new commits in a GitHub repository.

## Calculator HTML Project

The calculator HTML project is a simple web-based calculator with basic arithmetic operations.

## Project Overview

Task 1: Set Up a Simple HTML Project
Created a basic HTML project containing relevant content.
Pushed the project to a GitHub repository.

Task 2: AWS EC2/Local Linux Instance with Nginx
Provisioned an AWS EC2 instance/Local Linux Instance.
Installed and configured Nginx to serve web content.

Task 3: Python Script to Check for New Commits
Developed a Python script utilizing the GitHub API to detect new commits.

Task 4: Bash Script for Deployment
Crafted a bash script responsible for:
Cloning the latest code from the repository.
Deploying the updated content and restarting Nginx.

Task 5: Cron Job for Python Script
Configured a cron job to execute the Python script every 5 minutes.

Task 6: Testing
Successfully validated the pipeline by:
Making a new commit to the GitHub repository.
Verifying automatic deployment of changes.




Contributors
Nikhil Borse
Daniel Gonsalves
