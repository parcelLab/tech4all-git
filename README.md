# Open the terminal (Mac) or power shell (Windows)

**1. Configure git if you have not already**

```
git config --global user.name "YOUR NAME"
git config --global user.email YOUREMAIL@parcellab.com
```

**2. Open Terminal (Mac) or PowerShell (Windows) and go to your home directory**

Mac: `cd ~/`
Win: `cd $home`

**3. Clone (download) the repository:**

```
git clone git@github.com:parcelLab/tech4all-git.git
cd tech4all-git
```

**4. Switch to (checkout) the "main" version (branch).** _Technically, this is not necessary since the main branch is the default, but we're still doing it so that you get practice_

```
git checkout main
```

**5. Create a new branch with your name**

```
git checkout -b YOUR_NAME
```

**6. Edit the file in a text editor of your choice. You can find the `tech4all-git` folder in your file system using spotlight (mac) or taskbar (windows)**

**7. Check the status of your directory.** _The edited file should be in "Changes not staged for commit"_

```
git status
```

**8. Stage your file (add it to the staging area)**

```
git add YOUR_NAME/example1.txt
```

**9. Commit (checkpoint/save) your progress.** _The_ `-m` _stands for message. The message is added in quotes later._

```
git commit -m "fixed typo"
```

**10. Push (upload) your branch's changes to github**

```
git push -u origin YOUR_NAME
```

**11. On Github, submit a pull request to main. (Request that your changes be merged into the main branch.)** You can do this at [https://github.com/parcelLab/tech4all-git/compare](https://github.com/parcelLab/tech4all-git/compare)

**12. Wait for pull requests to be accepted**
⏱

**13. Checkout (switch back to) the main branch**

```
git checkout main
```

**14. Pull (download) changes from upstream (recent work from Github)**

```
git pull
```
