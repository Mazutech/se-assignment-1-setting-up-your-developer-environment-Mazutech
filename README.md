[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15268770&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

Answers

## Developer Environment Setup Documentation for macOS

### 1. Operating System: macOS

### 2. Text Editor/IDE: Visual Studio Code

**Step 1: Download Visual Studio Code**

- Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).
- Download the macOS version of Visual Studio Code.

Step 2: Install Visual Studio Code

- Open the downloaded `.zip` file and move `Visual Studio Code.app` to the `Applications` folder.
- Launch Visual Studio Code from the `Applications` folder.

### 3. Version Control System: Git and GitHub

**Step 1: Install Git**

- Open Terminal and install Git using Homebrew:
  ```bash
  brew install git
  ```

**Step 2: Configure Git**

- Open Terminal and configure your username and email:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```

**Step 3: Create a GitHub Account**

- Visit [GitHub](https://github.com) and sign up for a free account.
- Follow the instructions to verify your email and complete the account setup.

**Step 4: Initialize a Git Repository**

- Create a new project folder on your local machine.
- Open Terminal in the project folder and initialize a Git repository:
  ```bash
  git init
  ```

**Step 5: Make Your First Commit**

- Create a new file (e.g., `README.md`) in the project folder.
- Stage and commit the file:
  ```bash
  git add README.md
  git commit -m "Initial commit"
  ```

**Step 6: Push to GitHub**

- Create a new repository on GitHub.
- Link the local repository to the remote repository:
  ```bash
  git remote add origin https://github.com/your-username/your-repository.git
  git push -u origin master
  ```

### 4. Install Necessary Programming Languages and Runtimes

**Step 1: Install Python**

- Visit the [Python download page](https://www.python.org/downloads/).
- Download the latest version for macOS and run the installer.
- Ensure to check the box "Add Python to PATH" during installation.
- Verify the installation by running:
  ```bash
  python3 --version
  ```

### 5. Install Package Managers

**Step 1: Install pip (Python)**

- Pip is included with Python, but you can upgrade it by running:
  ```bash
  python3 -m pip install --upgrade pip
  ```

### 6. Configure a Database: MySQL

**Step 1: Download MySQL**

- Visit the [MySQL download page](https://dev.mysql.com/downloads/installer/).
- Download the macOS DMG archive and run the installer.

**Step 2: Install MySQL**

- Follow the installation wizard to install MySQL Server.
- Configure MySQL Server during installation, setting up a root password and other options as needed.
- Start the MySQL server from the MySQL preference pane in System Preferences.

### 8. Explore Extensions and Plugins for Visual Studio Code

**Step 1: Install Extensions**

- Open Visual Studio Code.
- Go to the Extensions view by clicking on the Extensions icon in the Activity Bar.
- Search for and install extensions such as:
  - Python
  - GitLens
  - Prettier - Code formatter
  - ESLint

### 9. Document Your Setup

**Documentation Steps**

- Write a detailed document outlining each step above.
- Include screenshots where necessary to illustrate the process.
- Save the document as `Developer_Environment_Setup_Documentation.md`.

### GitHub Repository

- Create a GitHub repository named `DeveloperEnvironmentSetup`.
- Add the `Developer_Environment_Setup_Documentation.md` to the repository.
- Commit and push the document to the repository.

### Reflection on Challenges and Strategies

**Challenges Faced:**

1. **Installation Issues**: Encountered problems during MySQL installation due to permission issues.

   - **Solution**: Granted necessary permissions in System Preferences under Security & Privacy settings.

2. **Git Configuration**: Initial confusion with configuring Git username and email.

   - **Solution**: Referenced Git documentation for step-by-step instructions.

3. **Python Path Issues**: Python was not recognized in the command line.
   - **Solution**: Added Python to PATH manually in the `.zshrc` file.
