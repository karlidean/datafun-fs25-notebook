# Creating the Project Foundation

## Create a Repository in Git
1. Make sure the repository is PUBLIC
2. Make sure there is a README.md file, we will add a `.gitignore` and `requirements.txt` later
3. Save

## Cloning a Repository from Git to My Local Machine (Windows)
1. In your repo, click the green "code" button
2. Copy the code link
3. Go to Powershell and use the following code
```shell
cd C:\Repos
git clone (your URL you copied from GitHub)
```

## Adding the Necessary Files for Your Project (`.gitignore` and `requirements.txt`)
1. Open the repo we've just cloned in VS Code
2. Click the "New File..." button
   1. This is found in the "Explorer" Window on the left side, just to the right of the repo's name (ex. datafun-fs25-notebook)
3. A text line should appear in the directory of your repo (Which is the "Explorer" Window). In this text line, type `.gitignore`
4. Click the "New File..." button again
5. In the new text line, type `requirements.txt`
6. Either type your own or use example `.gitignore` and `requirements.txt` files to fill with contents. 
   1. These are how you will get usable content and packages for your code!

## Add - Commit - Push: Getting the Work to GitHub
1. Use the following code sequence to push your changes to GitHub
```shell
git add .
git commit -m "your comment for the commit"
git push -u origin main # After using this once, you can just do "git push"
```

## Create the Virtual Environment (.venv)
1. Create the Virtual Environment with the following code:
```shell
py -m venv .venv
```
2. Activate the Virtual Environment with the following code:
```shell
.\.venv\Scripts\activate # You may have to activate your environment each time you enter your repo in VS Code!
```

## Add - Commit - Push: Getting the Virtual Environment to GitHub
1. Use the same sequence from earlier to complete this.

## Installing Dependencies from Requirements
1. Use the following code to upgrade the setuptools wheel:
```shell
pip install --upgrade setuptools wheel # You should check if this is upgraded each time you open the repo.
```
2. Use the following code to upgrade the `requirements.txt` file:
```shell
pip install --upgrade -r requirements.txt # You should check if this is upgraded each time you open the repo.
```
