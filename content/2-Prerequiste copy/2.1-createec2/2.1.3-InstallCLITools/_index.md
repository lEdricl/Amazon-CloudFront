---
title: "Install CLI Tools"
date: "`r Sys.Date()`"
weight: 3
chapter: false
pre: " <b> 2.1.3 </b> "
---

### 3. Install CLI Tools

#### 3.1. Download and Install AWS Command Line Interface (CLI)

- Visit the [AWS CLI Download page](https://aws.amazon.com/cli/).
- Download the appropriate version of AWS CLI for your operating system:
  - **Windows**: Download and install the `.msi` file from the AWS download page.
  - **macOS**: Use Homebrew to install the CLI, or download the `.pkg` file from the AWS download page.
  - **Linux**: Install AWS CLI through terminal commands like `curl` or `apt-get` (depending on your distribution).

- After downloading, run the installer and follow the on-screen instructions to complete the installation.

#### 3.2. Configure CLI using `aws configure` with Access Key and Secret Key from AWS IAM

- Open a terminal (Command Prompt on Windows, Terminal on macOS/Linux).
- Run the following command to configure AWS CLI:
  

- The system will prompt you to enter the following details:
- **AWS Access Key ID**: Enter the Access Key you created from IAM in the AWS Console.
- **AWS Secret Access Key**: Enter the Secret Key you created from IAM.
- **Default region name**: Enter the default region you want to use for AWS services (e.g., `us-west-2`).
- **Default output format**: Choose the output format (json, text, or table). Typically, select `json` for easy use.

Once completed, AWS CLI will be configured and ready to use.
