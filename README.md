# datafun-06-eda
## Exploratory Data Analysis (EDA) Notebook set up

This project aims to demonstrate skills in conducting EDA using Jupyter, pandas, Seaborn, and other popular data analytics tools.

## Overview

DataFun 06 is an opportunity to create a custom exploratory data analysis project using GitHub, Git, Jupyter, pandas, Seaborn, and other relevant modules.

### Deliverables

- **GitHub Repository**: [datafun-06-eda](https://github.com/Tesfamariam100/datafun-06-eda.git)
- **Documentation**: README.md
- **Notebook**: Tesfamariam_eda.ipynb (not started yet)

### External Dependencies

This project uses the following external modules:

- jupyterlab
- pandas
- pyarrow
- matplotlib
- seaborn

A virtual environment is recommended to manage these dependencies.

## Objective

The objective of this project is to perform and publish a custom EDA project to demonstrate skills with Jupyter, pandas, Seaborn, and popular tools for data analytics. The notebook should tell a data story and visually present findings in a clear and engaging manner.

## Getting Started

Follow these steps to set up the project on your local machine:

### Environment Setup

1. Create and activate the project virtual environment:

    ```bash
    python -m venv .venv
    ```

    For Windows:

    ```bash
    .\.venv\Scripts\Activate
    ```

2. Install all required packages into your local project virtual environment:

    ```bash
    pip install jupyterlab pandas pyarrow matplotlib seaborn
    ```

3. Update or generate a requirements.txt file:

    ```bash
    pip freeze > requirements.txt
    ```

4. Add a .gitignore file to your project with useful entries. You can use the following content:

    ```plaintext
    # Python virtual environment
    .venv/

    # Visual Studio Code settings and workspace
    .vscode/

    # Compiled Python files
    __pycache__/

    # macOS system files
    .DS_Store

    # Editor backup files
    *~

    # Python Jupyter Notebook checkpoints and runtime files
    .ipynb_checkpoints/
    *.ipynb_meta/
    ```

5. Document the steps and commands in your README.md file.

## Git Commands

To add, commit, and push changes to your GitHub repository, use the following commands:

```bash
# Add changes
git add .

# Commit changes with a descriptive message
git commit -m "Initial commit"

# Push changes to GitHub
git push origin main
