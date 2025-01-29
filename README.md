# infra-as-code-pipeline_2.0

##Description

This repository contains the implementation of a CI/CD pipeline for provisioning infrastructure as code. The goal is to automate the process of creating and managing cloud environments, ensuring consistency and agility.

## Features
* **Automatic provisioning:** Creation of cloud environments in an automated way.
* **Configuration management:** Version control and history of infrastructure configurations.
* **Continuous integration:** Automatic building and testing with each code change.
* **Continuous deployment:** Automatic deployment of new versions in environments.

## Technologies used
* **Terraform:** Tool for infrastructure provisioning.
* **GitHub Actions:** Platform for automating workflows.
* **AWS:** Cloud provider used for resources.

##Architecture

![arquitetura](https://github.com/user-attachments/assets/ad57207c-149a-42e2-8d1c-f4421fedc318)


## How to Use
1. **Clone the repository:**
```bash
git clone git@github.com:jhonwilame/infra-as-code-pipeline_2.0.git
Install the dependencies:
Bash

# Specific instructions for installing the required dependencies
Environment Variables:

Bash

export AWS_ACCESS_KEY_ID=<your_aws_access_key_id>
export AWS_SECRET_ACCESS_KEY=<your_aws_secret_access_key>
How to Use

Bash

# Run the pipeline
./run_pipeline.sh 


# Specific instructions for running the pipeline
Contributions
Contributions are welcome! To contribute, please follow these steps:

Fork this repository.
Create a new branch for your feature.
Make your changes and commit.
Submit a pull request.
License
This project is licensed under the JW License

