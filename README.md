# Data Analytics Fundamentals - Notebook Repository
This is a repo of Notes from "Intro to Python for Computer Science and Data Science"\
- The book is by Harvey Dietel and Paul Dietel
The course number is 44608 at Northwest Missouri State University
- All repos named `datafun-XX-title` are projects from this course I've submitted
- All repos from this course have received full marks except for datafun-02-automation, which received a 16/20

# Creating the Project Foundation

## Create a Repository in Git
1. Make sure the repository is PUBLIC
2. Make sure there is a README.md file
3. Save

## Cloning a Repository from Git to My Local Machine (Windows)
1. In your repo, click the green "code" button
2. Copy the code link
3. Go to Powershell and use the following code
4. `cd C:\Repos` This gets into your repo folder
5. `git clone new repo link` This grabs the repo from Git and puts it into the repo folder

## Adding the Necessary Files for Your Project (`.gitignore` and `requirements.txt`)
1. Open the repo we've just cloned in VS Code
2. Click the "New File..." button
   1. This is found in the "Explorer" Window on the left side, just to the right of the repo's name (ex. redesigned-giggle)
3. A text line should appear in the directory of your repo (Which is the "Explorer" Window). In this text line, type `.gitignore`
4. Click the "New File..." button again
5. In the new text line, type `requirements.txt`
6. Either type your own or use example `.gitignore` and `requirements.txt` files to fill with contents. 
   1. These are how you will get usable content and packages for your code!

## Add - Commit - Push: Getting the Work to GitHub
1. Add all of our files and changes into the ship with `git add .`
2. Commit to GitHub what we've done to change anything with `git commit -m "your message"`
3. Push our changes to the remote repo on GitHub with `git push -u origin main`
   1. When working on a longer project, we can shorten this to `git push` as long as we've used `git push -u origin main` first!

## Create the Virtual Environment (.venv)
1. Create the Virtual Environment with `py -m venv .venv`
2. Activate the Virtual Environment with `.\.venv\Scripts\activate`

## Add - Commit - Push: Getting the Virtual Environment to GitHub
1. Add all of our files and changes into the ship with `git add .`
2. Commit to GitHub what we've done to change anything with `git commit -m "your message"`
3. Push our changes to the remote repo on GitHub with `git push -u origin main`
   1. When working on a longer project, we can shorten this to `git push` as long as we've used `git push -u origin main` first!

## Upon Re-Entry to the Repo to Make Edits:
1. Activate the Virtual Environment with `.\.venv\Scripts\activate`
   1. This allows us to work in the .venv, it needs reactivated upon re-entry.

## Installing Dependencies from Requirements
1. Run `pip install -r requirements.txt`
   1. This allows us to pull everything (numpy, pandas, matplotlib, pathlib) and install it so we can utilize it.
