## Overview

This project adopts a local cloud environment for development and testing purposes. It uses a powershell script to launch the entire project with a cloud environment in docker. 

## What is localstack?

Localstack is a fully functional local AWS cloud stack. It allows you to develop and test your cloud and serverless apps offline! 

- A cloud service emulator that runs in a single container on your laptop
- You can run your aws apps or lambda functions
- Great for testing CDK apps, terraform configuration, learn aws services
- Speeds up and simlifies your testing and development workflow
- Supports a number of AWS services

#### Links:

- https://github.com/localstack/localstack

- https://localstack.cloud/

## Requirements

- `Docker`
- `docker-compose`
- `PowerShell`

## Running

1. Clone this repository
2. Open a PowerShell window and change directory to the cloned repository
3. Execute the PowerShell script `run-local.ps1`. This will execute all the docker-compose files for you
4. Done!

 