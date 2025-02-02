1. Git Configuration (First-Time Setup)

git config --global user.name "Your GitHub Username"
git config --global user.email "Your Email"


2. Cloning the Repository from GitHub

git clone https://github.com/YourUsername/SQL-Learning-Tracker.git
cd SQL-Learning-Tracker


3. Creating Folders and Files for Organizing the Repository

Creating Folders:
mkdir progress practice interview_questions

Creating Files:
touch README.md resources.md
touch progress/2025-02-03.md
touch practice/select_statements.sql practice/joins.sql
touch interview_questions/easy.md interview_questions/medium.md interview_questions/hard.md

4. Editing .md Files in Git Bash
   
Using nano to Edit Files:
nano README.md
To Save in nano: Ctrl + O → Enter
To Exit nano: Ctrl + X

5. Using vim to Edit Files:

vim README.md
Enter Insert Mode in vim: Press i
Exit Insert Mode in vim: Press Esc
Save and Exit in vim: Type :wq → Press Enter

6. Viewing File Contents

cat README.md

7. Adding, Committing, and Pushing Changes to GitHub
   
Add All Files to Staging:
git add .

Commit Changes with a Message:
git commit -m "Initial setup with README and folder structure"

Push Changes to GitHub:
git push origin main

8. Checking the Status of Your Repository
git status

9. Daily Updates (For New Progress)
Add a New Daily Progress File:
touch progress/2025-02-04.md

Edit the New Progress File:
nano progress/2025-02-04.md

Stage, Commit, and Push Updates:
git add .
git commit -m "Added progress for 2025-02-04"
git push origin main










