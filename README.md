# Custom Databricks Asset Bundle Template for Databricks environments

This repository provides a custom Databricks Asset Bundle template to quickly bootstrap new Databricks projects. By using this template, you can initialize projects directly from this GitHub repository, allowing you to start development with standardized configurations and folder structures.

## Usage

### Prerequisites

Ensure that you have the [Databricks CLI](https://docs.databricks.com/aws/en/dev-tools/cli/install) installed and configured. You will need access to both Databricks and this repository to initialize projects from the template.

In Visual Studio Code, make sure the [Databricks extension](https://marketplace.visualstudio.com/items?itemName=databricks.databricks) is also installed.

Once both tools are installed, configure the Databricks CLI by running:

```bash
databricks configure
```

You will be prompted to enter your Databricks host URL (e.g., `https://dbc-12a12a12a1-1212.cloud.databricks.com/`) and a personal access token.

To generate a personal access token:

1. Open your Databricks workspace.
2. Click your profile icon in the top right corner.
3. Navigate to **Developer Settings**.
4. Create a new personal access token.

### Initializing a New Project from This Template

To create a new Databricks bundle project from this template, follow the steps below. This guide shows how to initialize a project directly from GitHub, without needing to clone this repository manually.

#### Initialize the Project

To use the template from GitHub, run the following commands in your terminal:

bash
# Create a new directory for your project

mkdir my_new_project

cd my_new_project

# Initialize the project using the main template
databricks bundle init https://github.com/fidelesc/dab-template.git

### Updating the Template

To keep the template up to date, simply update this GitHub repository. Any new projects initialized afterward will automatically use the latest version.
