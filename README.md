# PLPBasicGitAssignment

PLPBasicGitAssignment
This repository is created to demonstrate the basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

Task 1: Repository Setup
1. GitHub Repository Creation
Log in to your GitHub account.
Create a new repository on GitHub and name it "PLPBasicGitAssignment".
Initialize the repository with a README file.
Task 2: Local Setup
2. Local Folder Setup
Create a new folder on your local machine named "PLPBasicGitAssignment".
Open a terminal or command prompt and navigate to the created folder: cd path/to/PLPBasicGitAssignment
3. Git Initialization
Initialize a new Git repository in your local folder: git init
4. Connecting to GitHub
Link your local repository to the GitHub repository created in Task 1: git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git : Replace https://github.com/your-username/PLPBasicGitAssignment.git with the actual URL of your GitHub repository.
Task 3: Making Changes
5. Create a File
Inside your local folder, create a new text file named hello.txt.
Add a simple text message to the file: Hello, Git!
6. Committing Changes
Stage the changes: git add hello.txt
Commit the changes with a message: git commit -m "Add hello.txt with a greeting"
Task 4: Pushing to GitHub
7. Pushing to GitHub
Push the committed changes to your GitHub repository: git push -u origin main
Task 5: Verification
8. Verify on GitHub
Visit your GitHub repository in a web browser and confirm that the hello.txt file and the commit message are visible.
