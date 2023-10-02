# GIT AUTOMATION SCRIPT

## Overview

This is a Bash script designed to automate common Git operations, including adding, committing, and pushing changes to a Git repository. The script is concise and only pushes to the remote repository, however, it can be expanded to suit your pconcise

## Features

- **Add and Commit Files:** The script allows you to add specific files or directories to the staging area and commit them with custom commit messages.

- **Automatic Push:** After committing your changes, the script automatically pushes them to the remote Git repository, ensuring that your local changes are synchronized with the remote repository.

- **Indirect Variable Referencing:** The script demonstrates the use of indirect variable referencing to dynamically select and add files based on command line arguments.

## Prerequisites

- **Bash Shell:** The script is designed to run in a Bash shell environment. Ensure that you have a Bash-compatible shell installed on your system.

- **Git:** You should have Git installed and configured on your system to use this script. You can download and install Git from [https://git-scm.com/downloads](https://git-scm.com/downloads).

## Usage

- **Clone this repository:** First, you need to clone this Git automation script repository to your local machine, Open your terminal and run the following command (replace `[your-username]` with your Github username):

   ```bash
   git clone https://github.com/your-username/git_automation.git

- **Navigate to the Script Directory:** Change your current working directory to the location where you cloned the repository. Use the `cd` command to enter the script's directory:

    ```bash
    cd git_automation

- **Make the Script Executable:** Ensure that the script file is executable. You may have already done this, but if not, use the `chmod` command to make it executable:

    ```bash
    chmod u+x auto_git_push

- **Add the Script to Your PATH:** To run the script from anywhere on your system, it's a good practice to add the script's directory to your system's PATH environment variable. This step allows you to execute the script without specifying its full path every time. You can add the following line to your shell profile file (e.g., `.bashrc`, `.zshrc`, or `.profile`) to make the script globally executable: **Make sure you don't add the name of the script as part of the path, stop in the folder where the script is saved**

    export PATH="$PATH:/path/to/git-automation-script"

Replace /path/to/git-automation-script with the absolute path to the directory containing your script.

- **Open a New Terminal Session:** After adding the script's directory to your PATH, open a new terminal session (or restart your shell) to apply the changes.

- **Run the Script:** You can now run the Git automation script from anywhere on your system. Use the script name and provide any desired command line arguments.

	- To add and commit specific files, provide the file names as command line arguments:

	auto_git_push file1.txt file2.txt

	- To add and commit all files in the current directory, run the script without command line arguments:

	auto_git_push

- **Follow the Prompts:** The script will prompt you to enter commit messages for each file you are committing.

- **Automated Process:** The script will automatically add, commit, and push your changes to the remote Git repository.

## Acknowledgments
This script was created to simplify and automate common Git tasks.
Inspiration for this project comes from various Git automation scripts and workflows used in software development.

## Contributing
If you have suggestions or find issues with the script, please open an issue or submit a pull request to help improve it.

## Contact
For questions or feedback, feel free to contact me at:
- Mail: [adebanjoemmanuel01@gmail.com][adebanjoemmanuel01@gmail.com].
- LinkedIn: [https://www.linkedin.com/in/adebanjo-emmanuel][https://www.linkedin.com/in/adebanjo-emmanuel]
- X or Twitter: [https://twitter.com/Deolamma][https://twitter.com/Deolamma] 
