# GitHub Setup Guide for Beginners

## Introduction

This guide will walk you through the process of setting up GitHub as a beginner. You will learn how to create a GitHub account, install Git, configure Git, create a repository, and push your first project.

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
3. Enter a repository name and description.
4. Choose to make it **public** or **private**.
5. Click **Create repository**.

---

## Step 5: Clone the Repository (Optional)

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

Congratulations! You have successfully set up GitHub and pushed your first project. You can now continue to explore GitHub, collaborate on projects, and improve your version control skills.

For further learning, check out [GitHub Docs](https://docs.github.com/).
