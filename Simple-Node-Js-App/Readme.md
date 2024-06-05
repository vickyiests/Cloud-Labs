# Nodejs Web App

A simple "Hello World" node. js app and containarized with Docker, leveraging Github Actions for CI/CD and automated testing. This app is deployed to AWS EC2 and uses Terraform as IAC for infrastructure provisioning.


## Features

- **Node.js**: Simple server that responds with "Hello World".
- **Docker**: Application containerization for consistent deployment.
- **GitHub Actions**: Automated workflows for CI/CD.
- **Terraform**: Infrastructure as Code to provision AWS EC2 instances.


## Prerequisites

- Node.js (If you use Mac, you can do a brew install to install node.js and the command is brew install node)
- npm (Node Package Manager)
- Docker (for containerization)
- Terraform (for deploying to AWS)
- AWS CLI (configured with your credentials)
- Git


## Local Development

### Getting Started

Clone the repository and navigate into the project directory:

git clone [repository-url]

cd web-app

# Installation

```npm install```

# Running the Application Locally

``` npm start ```

This will run the application on 'http://localhost:8080'


# Docker Build

``` docker build -t web-app . ```
``` docker run -p 3000:3000 web-app ```

# installing Docker on EC2 

```sudo yum update -y
sudo yum install docker -y
sudo systemctl start docker
sudo systemctl enable docker
sudo usermod -a -G docker ec2-user #gives ec2 user permission to execute docker commands without using sudo after#

 ```
