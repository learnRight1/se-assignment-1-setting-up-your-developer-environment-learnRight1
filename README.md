[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15289696&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   The operating system that best suits my preference is window. Currently, I'm using windows 10 although windows 11 is a requirement. I couldn't upgrade it now because I do not have a bootable flash as at when submitting this assignment but hope to do so later.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   I had visual studio code long before now and the process of downloading it and installing it are as follows:
   First, I openned a web browser and typed on the search engine visualstudio.com. I clicked on the first response and was directed to the home page where I clicked on the download button related to my operating system that is, 64-bit.

   Second, I went to my download and double clicked on the installer to run it.

   Third, I accepted the agreement licence and use the default settings by clicking next to finish. I ensure that I added visualstudio code to the path.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   I have installed git on my local machine and the steps taken are as follows:
   Here's a concise guide for installing Git, configuring it, creating a GitHub account, initializing a Git repository, and making your first commit:
   First, on my browser, I typed git-scm.com and download the Windows installer.
   Second, I ran the downloaded file and follow the installation prompts. I also use the default settings.
   Third, I openned my git Bash from the Start Menu. And ran the following commands:
   git config --global user.name "codeRight"
   git config --global user.email "connect2gracealone@gmail.com"

   CREATING GITHUB ACCOUNT
   I typed on my browser: https://github.com and clicked on "Sign up" and follow the instructions to create a new account.

INITIALIZING A GITHUB REPOSITORY
First, I openned my gitbash and navigate to desktop by using the command cd Desktop.
I created a folder using, mkdir test and cd into it.
I use touch index.html to create a file in it and use the command code . to open my vscode
Next, I use this command to initialize git: "git init"

Secondly, I use the command "git add" to stage my work for a commit.
Then, I use git commit -m "Added html file"

4. Install Necessary Programming Languages and Runtimes:
   Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

First, on my browser, I typed: https://www.python.org. I downloaded the latest version of Python(3.12.4) for Windows.

I ran the downloaded installer python-3.12.4, ensuring to check the box that says "Add Python 3.12.4 to PATH.
And, I follow the prompts in the Python installer to complete the installation.

I typed `cmd` in the Windows search bar and press Enter to open Command Prompt. I verify the installation by typing the python version using the command: python --version.

Installing Additional Tools:
And I used this command: "python -m pip install" to install number of things like django which is python framework and virtual environment.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

First, I typed cmd in the Windows search bar and press Enter to open Command Prompt and checked the pip version using this command on the terminal: "pip --version" to see if pip is already installed with Python. Since, it is there, I don't see need to install it.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

First, I visited the website by just typing on the browser search bar: mysql since I don't really know the website address. I followed strictly the documentation given the lms dashboard.

I choose the appropriate installer as recommended by the documentation, in this case, the community installer and downloaded it. I got confused number of time but still managed to install it but later dicover that the installation is not complete. I followed one of the video to install mysql workbench.

I discovered later that, my installation is not having a server but later I was opportune to share my screen and was guided by the team lead by Gerald to solve the problem. It was a great experience for me and I'm really willing to guide others and walk them through now that I know better.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

I didn't attempt to do this.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   I added number of extensions to my vscode. After opening my vscode, I clicked on the extention icon or gear and typed the needed extensions and installed each, one after the other. Extensions such as: prettier, code runner, dart language support, data wrangler, dart, flutter, live server, python debugger and many more.

9. Document Your Setup:
   Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

   This is done in each of the technologies that we were asked to install.

#Deliverables:

- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:\*\*

- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
