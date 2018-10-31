# Automating AWS With Python

Repo for automating AWS with python

On Mac using brew run the following installation
brew install python 3.7 - check installation by entering python --version
pip3 install pipenv
brew install node
npm install -g serverless - check working by typing serverless in cmd
brew install awscli check working by typing aws help
brew install git
ssh-keygen -C youremail
ssh-add
----
sign up for aws account and configure aws using aws configure
----
create a github repo
setup ssh key
##01 - webotron

Webotron is a script that will sync a local directory to an s3 bucket, and optionally configure Route53

## Features

Webotron currently has the following features

- List bucket
- List contents of a bucket
- Create and Setup bucket
- Sync Dir tree to Bucket