# Cloud Lab Practices

Welcome to my Cloud Lab Practices repo. This is a work in progress as I explore various cloud technologies and implement different lab scenarios for learning. Topics covers basic, intermediate to advanced.


## Overview

This repo helps to facilitate learning and experimentation with different cloud platforms such as AWS, Azure, and Google Cloud.

### Prerequisites

Before you begin, ensure you have the necessary tools installed on your Mac. This setup will allow you to interact with AWS, Azure, and Google Cloud platforms directly from your command line. 

For Homebrew – run:

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" ```

AWS CLI:

``` brew install awscli ```

After installation, configure it by running:

``` aws configure ```

Follow the prompts to enter your AWS Access Key ID, Secret Access Key, default region, and output format.

Azure CLI:

``` brew install azure-cli ```

To sign in to Azure, use:

```az login```

Command will open a web page where you can log in using the Azure credentials

Google Cloud SDK:

``` brew install --cask google-cloud-sdk ```

Initialize the Google-Cloud SDK:

``` gcloud init ```

Check Your Setup to verify tools are installed correctly:

``` brew --version ```

``` aws --version ```

``` az --version ```

``` gcloud --version```





