# datafun-07-applied
# Project 7

## How to Install and Run the Project


# Create a virutal Environment named .venv
python3 -m venv .venv 
# Activate Virtual Environment
source .venv/bin/activate

# Install Dependencies

python3 -m pip install -r requirements.txt

# Check the status of my repository
This will list all the modified files

git status

# Git Add
git add . 

# Git Commit
git commit -m "initial commit"

#       Subsequent Commits
        Just input your message on command
        git commit -m "Your commit message"

# Git Push
git push origin main

#       Subsequent Pushes
        git push
==============================================
# Various Commands
Python3 Commands
-----------------

1. Check Python Version:
   python3 --version

2. Install a Package:
   python3 -m pip install <package_name>

3. Install from `requirements.txt`:
   python3 -m pip install -r requirements.txt

4. Run a Python Script:
   python3 script_name.py

5. Create a Virtual Environment:
   python3 -m venv env

6. Activate Virtual Environment:
   source env/bin/activate

7. Deactivate Virtual Environment:
   deactivate

8. Upgrade `pip`:
   python3 -m pip install --upgrade pip

9. List Installed Packages:
   python3 -m pip list

10. Uninstall a Package:
   python3 -m pip uninstall <package_name>


Git Commands
------------

1. Initialize a Git Repository:
   git init

2. Clone a Repository:
   git clone https://github.com/yourusername/your-repository.git

3. Check Repository Status:
   git status

4. Stage Changes (a specific file):
   git add <file_name>

   OR stage all changes:
   git add .

5. Commit Changes:
   git commit -m "Your commit message"

6. View Commit History:
   git log

7. Push Changes to Remote Repository:
   git push origin main

8. Pull Changes from Remote Repository:
   git pull origin main

9. Create a New Branch:
   git checkout -b new-branch-name

10. Switch to an Existing Branch:
    git checkout branch-name

11. Merge a Branch:
    git merge branch-name

12. Remove a Remote Branch:
    git push origin --delete branch-name

13. Remove a Local Branch:
    git branch -d branch-name

14. Configure Git User Info:
    git config --global user.name "Your Name"
    git config --global user.email "you@example.com"

15. Set Remote Repository URL:
    git remote set-url origin https://github.com/yourusername/new-repository.git
    
Jupyter Notebook Commands
-------------------------

1. Launch Jupyter Notebook:
   jupyter notebook

2. Launch Jupyter Lab (alternative interface):
   jupyter lab

3. List Running Notebooks:
   jupyter notebook list

4. Export a Notebook to HTML:
   jupyter nbconvert --to html notebook.ipynb

5. Export a Notebook to PDF:
   jupyter nbconvert --to pdf notebook.ipynb

6. Install Jupyter in a Virtual Environment:
   python3 -m pip install jupyter

7. Add a New Cell (in the interface):
   - Use the `+` icon to add a new code or markdown cell.

8. Execute All Cells:
   Kernel > Restart & Run All (or use the toolbar).

9. Save Notebook:
   File > Save and Checkpoint (or use `Cmd + S`).

10. Convert Notebook to Python Script:
    jupyter nbconvert --to script notebook.ipynb

11. Clear All Outputs:
    Kernel > Restart & Clear Output
