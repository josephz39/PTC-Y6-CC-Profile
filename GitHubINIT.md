# PTC Community Codes TASK 1: GitHub Setup
Welcome to PTC's Y6 Community Codes Coding Challenge. This term, we will be focusing on developing skills pertaining to web development. By the end of this challenge/project, you should be able to create a simple web application using React.js, define basic HTML/CSS components, and design your pages around standard UI/UX principles. 


## Introduction

TASK 1 will be to initialize and setup your github repo. This is where you will be storing and tracking all of your files and updates. This will allow us to check your progress as well, whenver you submit project milestones. 

### What is Github?
GitHub is an online platform that helps developers collaborate and store their coding projects. Think of it like a giant filing cabinet in the cloud where you can safely store your code, track changes, and collaborate with others. It uses a tool called Git to manage the history of your code, so you can see what’s been added or changed over time and even undo mistakes if needed. GitHub is a standard tool in the industry so this is the perfect place to start and get familiar with it.

If you have never used GitHub before, you can follow the steps below. Otherwise, if you already have a GitHub account and have used it before, feel free to skip to **Step 4** to create your project repo.

---

## Step 1: Create a GitHub Account

1. Go to [GitHub](https://github.com/).
2. Click on **Sign up**.
3. Enter your email, username, and password.
4. Follow the on-screen instructions to complete your registration.
5. Verify your email address via the confirmation email from GitHub.

---

## Step 2: Install Git

Git is a version control system required to interact with GitHub from your local machine.

### Windows:

1. Download Git for Windows from [git-scm.com](https://git-scm.com/downloads).
2. Run the installer and follow the default setup instructions.
3. Open **Git Bash** to start using Git.

### macOS:

1. Open **Terminal**.
2. Run the command:
   ```sh
   brew install git
   ```
3. Verify installation by running:
   ```sh
   git --version
   ```

### Linux:

1. Open **Terminal**.
2. Run the following command:
   ```sh
   sudo apt update && sudo apt install git -y
   ```
3. Verify installation:
   ```sh
   git --version
   ```

---

## Step 3: Configure Git

Set up your Git user details to associate commits with your GitHub account.

1. Open **Git Bash** or **Terminal**.
   - For MacOS: command + space -> terminal
   - For Windows: open command prompt
   - NOTE: You can also do this directly in VSCode
   - NOTE: if the command doesn't work, ensure you are in a git bash terminal
2. Run the following commands:
   ```sh
   git config --global user.name "Your Name"
   git config --global user.email "your-email@example.com"
   ```
3. Verify your settings:
   ```sh
   git config --list
   ```

---

## Step 4: Create a GitHub Repository

1. Log in to your GitHub account.
2. Click on **New Repository**.
3. Enter a repository name and description:
  - Name it something pertaining to the project: ie. Profile-App
4. Choose to make it **public** or **private**.
5. Click **Create repository**.

---

## Step 5: Clone the Repository 
Before you clone your repository, you should decide where you want to work (virtually). The following IDEs (code editors) are good tools to help you get started:
- VSCode: standard IDE use across the industry - developed by Microsoft https://code.visualstudio.com/download
- GitHub Codespaces: VSCode built into the GitHub ecosystem. This allows you to develop directly within your repo.
- Online IDEs: repl.it, CodeSandbox (free tier)

If you need help setting any of these up, please reach out to one of our coding challenge coordinators.

To work on your repository locally, clone it to your computer.

1. Copy the repository URL from GitHub.
2. Run the following command in Git Bash or Terminal:
   ```sh
   git clone <repository-url>
   ```

---

## Step 6: Add Files and Make a Commit

1. Navigate to your cloned repository:
   ```sh
   cd repository-name
   ```
2. Create or add files to the repository.
3. Add files to staging:
   ```sh
   git add .
   ```
4. Commit the changes:
   ```sh
   git commit -m "Initial commit"
   ```

---

## Step 7: Push Changes to GitHub

1. Connect your repository to GitHub:
   ```sh
   git remote add origin <repository-url>
   ```
2. Push your changes:
   ```sh
   git push -u origin main
   ```

---

## Step 8: Pull Changes from GitHub

To keep your local repository updated with remote changes:

```sh
git pull origin main
```

---

## Conclusion

Congratulations! You have successfully set up GitHub and your project repository. You can now continue to proceed to the next steps of the project: **TASK 2 - Set up your first React App**.

For further learning, check out [GitHub Docs](https://docs.github.com/).
You can also check this out for a resource on Git Commands: https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html
