[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15236604&assignment_repo_type=AssignmentRepo)

## Assignment: Setting Up My Developer Environment

### Tasks and Steps:

- **Select Your Operating System (OS):**

  - I used Windows 10, which came pre-installed on my laptop.
  - [Download Windows 10](https://www.microsoft.com/software-download/windows10) (if needed).

- **Install a Text Editor or Integrated Development Environment (IDE):**

  - I installed Visual Studio Code.
  - Steps:
    - I went to the [Visual Studio Code download page](https://code.visualstudio.com/Download).
    - I downloaded the installer for Windows.
    - I ran the downloaded file and followed the installation prompts.
  - Outcome: Visual Studio Code installed without issues.

- **Set Up Version Control System:**

  - I installed Git and configured it on my local machine.
  - Steps:
    - I went to the [Git download page](https://git-scm.com/).
    - I downloaded the Git installer for Windows.
    - I ran the downloaded file and followed the installation prompts.
    - I created a [GitHub account](https://github.com) (since I didn’t have one).
    - I opened Git Bash and configured Git with my username and email
    - I initialized a Git repository for my project:
      ```bash
      git init
      git add .
      git commit -m
      ```
  - Outcome: Git installed and configured successfully.

- **Install Necessary Programming Languages and Runtimes:**

  - I installed Python.
  - Steps:
    - I opened Google Chrome and searched for "python.org".
    - I went to the [official Python website](https://www.python.org/).
    - I downloaded the latest version of Python.
    - I located the downloaded file and double-clicked to install.
    - After installation, I opened Command Prompt (cmd) and typed:
      ```bash
      python --version
      ```
    - I encountered an issue: Command Prompt showed a message indicating to either install Python from Microsoft Store or disable the restriction.
    - Solution: I installed Python directly from the Microsoft Store.
    - I verified the installation again in Command Prompt:
      ```bash
      python --version
      ```
  - Outcome: Python installed successfully.

- **Install Package Managers:**

  - I ensured pip (Python package manager) was installed.
  - Steps:
    - After installing Python, pip was installed automatically.
    - I verified pip installation in Command Prompt:
      ```bash
      pip --version
      ```
  - Outcome: pip installed successfully.

- **Configure a Database (MySQL):**

  - I installed the MySQL database.
  - Steps:
    - I went to the [MySQL download page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
    - I downloaded the MySQL installer for Windows.
    - I ran the downloaded file and followed the installation prompts.
    - I encountered an issue: "Microsoft Visual C++ 2019 Redistributable Package (x64) is not installed."
    - Solution: I went to the [Microsoft Visual C++ Redistributable page](https://aka.ms/vs/16/release/vc_redist.x64.exe).
    - I re-ran the MySQL installer and during the installation:
    - I selected the developer option during the installation process.
    - I set up a password for the MySQL root user when prompted.
  - Outcome: MySQL installed successfully.

- **Explore Extensions and Plugins:**
  - I enhanced Visual Studio Code functionality.
  - Steps:
    - I opened Visual Studio Code.
    - I went to the Extensions view by clicking the Extensions icon
    - I searched for and installed the following useful extensions:
      - **Prettier - Code formatter**: For code formatting.
      - **Live Server**: For live reloading of web pages during development.
      - **GitHub Pull Requests and Issues**: For managing pull requests and issues within VS Code.
      - **Live Share**: For real-time collaborative development.
    - I also installed other useful extensions, such as:
      - **Python**
      - **GitLens**
      - **ESLint**
  - Outcome: Extensions installed to improve coding workflow.

### Reflection:

- **Challenges:**

  - I encountered an issue with Python installation due to restrictions in Command Prompt.
  - I faced an installation issue with MySQL due to a missing Visual C++ Redistributable.

- **Solutions:**
  - I resolved the Python installation issue by installing it from the Microsoft Store.
  - I fixed the MySQL installation by downloading and installing the required Visual C++ Redistributable package from the Microsoft site.
