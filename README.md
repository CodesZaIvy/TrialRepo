# Systech-DevOps Syllabus 

# Table of Contents :alien:

-   [Introduction to DevOps](#Introduction)

-   [GIT-A Version Control Tool](#GIT-A-Version-Control-Tool)
    -   [Knowing about version control](#Knowing-about-version-control)
    -   [GIT - A CLI](#GIT---A-CLI)
    
**Installing Git:** 

   To install Git on your computer, you can follow the instructions below for various operating systems:

**For Windows:**

1. Visit the official Git website: https://git-scm.com/download/win
2. Click the "Download for Windows" button to download the Git for Windows installer.
3. Run the downloaded installer.
4. Follow the installation wizard, accepting the default settings unless you have a specific reason to change them.
5. During installation, you can choose between using Git from the Windows Command Prompt or using Git Bash (a Unix-like command-line environment). Both options are fine, and you can switch between them later if needed.

**For macOS:**

1. If you have Homebrew installed, open your terminal and run:
   ```
   brew install git
   ```
   This will install Git via Homebrew.

2. Alternatively, you can download and install Git for macOS by visiting the official Git website: <https://git-scm.com/download/mac>
3. Click the "Download for macOS" button to download the Git for macOS installer.
4. Run the downloaded installer.
5. Follow the installation wizard, accepting the default settings.

**For Linux (Debian/Ubuntu):**

Open your terminal and run the following commands:

```
sudo apt update
sudo apt install git
```

**For Linux (Fedora):**

Open your terminal and run the following command:

```
sudo dnf install git
```

**For Linux (CentOS/RHEL):**

Open your terminal and run the following command:

```
sudo yum install git
```

After the installation is complete, you can verify that Git was installed successfully by opening a terminal and running the following command:

```
git --version
```

This command should display the installed Git version. If you see the version number, Git is successfully installed on your system.

Now you can start using Git for version control on your computer. Make sure to configure your Git identity using `git config` with your name and email address before using Git for the first time.
        -Essentials of GIT in industry
-   [Working with various commands in Git](#Working-with-various-commands-in-Git)
-   [Recording Changes to the Repository](#Recording-Changes-to-the-Repository)
-   Ignoring Files from git

    -   [Viewing the Commit History](#Viewing-the-Commit-History)
    -   [Undoing Things](#Undoing-Things)
    -   [Working with Remotes](#Working-with-Remotes)
    -   [Branching and Merging in Git](#Branching-and-Merging-in-Git)
    -   [Git Workflows](#Git-Workflows)
    -   [Git Cheatsheet](#Git-Cheatsheet)

## Description

### DevOps Principles in detail


### DevOps Engineer Skills in the market Knowing

### DevOps Delivery Pipeline Market trend of DevOps

### DevOps Technical Challenges


### Tools we use in DevOps

#### How to set up Git

Installing Git on Linux is fairly straightforward. Use the following commands,
depending on your Linux distro, to install it on your computer.

-   Ubuntu: **sudo apt install git**
-   Fedora: **sudo yum install git**
-   Arch Linux: **sudo pacman -S git**
-   FreeBSD: **sudo pkg install git**

Once done, verify if the installation was successful by running the following command:

-   **git --version**

If it returns a version number, it means that the installation was successful. If not, you
need to go over the installation process again.

## Recording Changes to the Repository :cd:
### How to check the Status of Your Files
> Tracking file in the current working directory and the staging area is achieved by running the following command in the CLI:  
> `git status`  
> The following files will be listed after running the command - 
> staged, tracked and untracked files.
### How to track New Files

### Staging our modified files

### Ignoring Files from GIT
In Git, you can ignore files or directories by specifying patterns in a special file called .gitignore. These patterns tell Git which files or directories to exclude from version control.

### Viewing Your Unstaged and Staged Changes

### How to commit Your Changes

### Skipping the Staging Area and commit

### Removing Files from GIT

# Systech-DevOps
## Working With Remotes
- Showing your Remotes
- Adding Remote Repositories
- Fetching and Pulling from Your remotes
- Pushing to Your Remotes
- Inspecting a Remote
- Removing and Renaming Remotes

### Working with container

### Git - A CLI
#### -  You typically obtain a Git repository in one of two ways:
-  You can take a local directory that is currently not under version control, and turn it into a Git repository, or
-  You can clone an existing Git repository from elsewhere.
-  In either case, you end up with a Git repository on your local machine, ready for work.

<ul style="list-style-type: none;">
  <li><input type="checkbox" disabled> How to Share and copy a container</li>
  <li><input type="checkbox" disabled> Container Life Cycle</li>
  <li><input type="checkbox" disabled> How to use Base Image and customize</li>
  <li><input type="checkbox" disabled> Creation of Docker File</li>
  <li><input type="checkbox" disabled> How to Publish Image on Docker Hub</li>
</ul>

## Summary :memo:
You can find a link to this README.md here : 
 
  <https://github.com/CodesZaIvy/TrialRepo.git>
