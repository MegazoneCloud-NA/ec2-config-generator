# EC2 Config Generator

**EC2 Config Generator** is a Python-based tool that fetches and exports AWS EC2 instance configurations into user-friendly formats such as tables, CSV, or Markdown. This tool is ideal for generating reports or analyzing AWS EC2 configurations across your cloud environment.

---

## Features
- Fetches detailed information about all your EC2 instances.
- Supports output formats:
  - **Markdown** (for easy documentation)
  - **CSV** (for spreadsheet analysis)
  - **Plain Text** (for quick reference)
- Simple and easy-to-use.
- Securely integrates with AWS via **IAM roles** or **access keys**.

---

## Prerequisites
Before using this tool, ensure the following:
1. **Python 3.7 or later** is installed on your system.
2. **AWS credentials** are set up:
   - Using an AWS credentials file (`~/.aws/credentials`) or environment variables (`AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`).
   - Ensure the IAM user/role has at least the `AmazonEC2ReadOnlyAccess` policy.
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
