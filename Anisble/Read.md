# EC2 Provisioning with Ansible and AWS Vault

This project provisions three EC2 instances (two Ubuntu and one Amazon Linux) using Ansible. AWS credentials are securely managed with AWS Vault, ensuring that sensitive information is not exposed.

## Project Overview
Provisioned EC2 Instances: 
  - 2 Ubuntu instances
  - 1 Amazon Linux instance
Tools Used:
  - Ansible: Automates the creation and configuration of EC2 instances.
  - AWS Vault: Manages AWS credentials securely.

## Prerequisites

- AWS CLI installed and configured
- AWS Vault installed for securely managing AWS credentials
- Ansible installed on your local machine
- An IAM user with sufficient permissions to create EC2 instances
