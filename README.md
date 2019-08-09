# Udacity Linux Server Configuration Project

This file contains all required submission information about the udacity's linux server configuration project.

 **SSH Command** 
  - ssh grader@13.235.9.47 -p 2200 -i udacity-student

**Website Address**

  - http://13-235-9-47.nip.io

**List of softwares Used for Configuration**

  - PuttyGen
  - Git Bash

**Some Server Configuration Changes**

 - Updated package resource list
 - Upgraded all packages
 - Changed the default ssh port 22 to 2200
 - Configure the Uncomplicated Firewall to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123)
 - Disable SSH root login
 - Create new user 'grader'
 - gave user 'grader' sudo access
 - created SSH key pair for user 'grader'
 - configured Apache to serve a Python mod_wsgi application
 - created postgresql database name catalog
 

**Learning Resources**
 https://explore-flask.readthedocs.io/
https://stackoverflow.com/
https://www.codementor.io/abhishake/minimal-apache-configuration-for-deploying-a-flask-app-ubuntu-18-04-phu50a7ft
https://www.tecmint.com/change-ssh-port-in-linux/
