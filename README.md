[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15231209&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.


# Developer Environment Setup

## 1. Select Your Operating System (OS)
Choose an operating system that best suits your preferences and project requirements. For this setup, we will use Windows 11.

- **Download and Install Windows 11**: 
  [Windows 11 Download](https://www.microsoft.com/software-download/windows11)

## 2. Install a Text Editor or Integrated Development Environment (IDE)
Select and install a text editor or IDE suitable for your programming languages and workflow. For this setup, we will use Visual Studio Code (VS Code).

- **Download and Install Visual Studio Code**:
  [Visual Studio Code Download](https://code.visualstudio.com/Download)

## 3. Set Up Version Control System
Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit.

- **Install Git**:
  [Git Download](https://git-scm.com/downloads)
- **Create a GitHub Account**:
  [GitHub Signup](https://github.com)
- **Initialize a Git Repository and Make First Commit**:
  ```sh
  git init
  git add .
  git commit -m "Initial commit"
  git remote add origin https://github.com/yourusername/your-repo.git
  git push -u origin master

# Developer Environment Setup

## 4. Install Necessary Programming Languages and Runtimes
Install the programming language required for your project and their respective compilers, interpreters, or runtimes.

### Install Python
- **Python Download**: [Python Download](https://www.python.org/downloads/)
- Ensure you have the necessary tools to build and execute your code:
  ```sh
  python --version
  pip --version


# Setup Instructions

## 5. Install Package Managers
If applicable, install package managers like pip (Python).

### Install pip (comes bundled with Python 3.4+)
```sh
python -m ensurepip --upgrade

## 6. Configure a Database (MySQL)
Download and install MySQL database.

### Download and Install MySQL
- [MySQL Installer](https://dev.mysql.com/downloads/installer/)

### Set up MySQL
Follow the installer instructions to set up the MySQL server and create a new database.


## 7. Set Up Development Environments and Virtualization (Optional)
Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

### Docker
- [Docker Download](https://www.docker.com/products/docker-desktop/)

Set up Docker to manage your development environments.


## 8. Explore Extensions and Plugins
Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

### VS Code Extensions
- **Python**: Adds rich support for Python.
- **GitLens**: Supercharges Git capabilities.
- **ESLint**: Integrates ESLint JavaScript into VS Code.
- **Prettier**: Code formatter.
- **Docker**: Adds support for Docker.
