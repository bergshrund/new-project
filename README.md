Certainly! Here are step-by-step instructions to create a new GitHub repository named 'new-project' with a development branch:

### 1. Create a new repository on GitHub:

   - Go to [GitHub](https://github.com/) and log in to your account.
   - Click on the "+" sign in the top right corner and select "New repository."
   - Enter "new-project" as the Repository name.
   - Optionally, provide a description, choose public or private, and initialize this repository with a README (this is optional).
   - Click on the "Create repository" button.

### 2. Clone the repository to your local machine:

   - Open your terminal (Command Prompt, PowerShell, or a Git Bash).
   - Use the following command to clone the repository to your local machine:

     ```bash
     git clone https://github.com/your-username/new-project.git
     ```

   - Change into the project directory:

     ```bash
     cd new-project
     ```

### 3. Create a development branch:

   - To create a new branch named 'development,' use the following command:

     ```bash
     git checkout -b development
     ```

   This command creates a new branch (`development`) and switches to it.

### 4. Start developing:

   - Now, you can start working on your new features in the 'development' branch without affecting the 'main' branch.

### 5. Commit and push changes:

   - After making changes, you need to commit them and push to the 'development' branch:

     ```bash
     git add .
     git commit -m "Your commit message"
     git push origin development
     ```

   This will push your changes to the 'development' branch on GitHub.

### 6. Merge changes into the main branch:

   - Once you are ready to merge your changes into the 'main' branch, you can create a pull request on GitHub.

     - Navigate to your repository on GitHub.
     - Click on the "Pull requests" tab.
     - Click the "New pull request" button.
     - Select 'main' as the base branch and 'development' as the compare branch.
     - Follow the prompts to create the pull request.

   - After the pull request is created, you can review the changes and merge them into the 'main' branch.

That's it! Now you have a GitHub repository with a 'main' branch and a 'development' branch for your new project.