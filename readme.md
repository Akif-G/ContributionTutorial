## Contributing

- if you already contributed before, you can continue from step 5.

---

first of all:
- create a github account
- be sure you have Git installed in your system

---
1. 
- Firstly you need a local fork of the the project, so go ahead and press the “fork” button in GitHub.
This will create a copy of the repository in your own GitHub account and you’ll see a note that it’s been forked underneath the project name.
---
2. 
- Set up a working copy on your computer:
```console
git clone https://github.com/<YOUR USERNAME HERE>/ContributionTutorial
```
---
3. 
- Change into the new project’s directory:
```console
cd ContributionTutorial
```
---
4. 
- Add main codebase to be able to make pull requests easily.
```console
git remote add upstream https://github.com/Akif-G/ContributionTutorial
```

You now have two remotes for this project on disk:

- origin which points to your GitHub fork of the project. You can read and write to this remote.
- upstream which points to the main project’s GitHub repository. You can only read from this remote.
---
5. 
### Before changing, pull the final version of project from origin
```console
git pull upstream master && git push origin master
```
### Make a new branch, named as develop or developer's name.
```console
git checkout -b <developer's name or "develop">
```
---
6. 
### Make Your changes on your favorite ide
---
7.  
### save them to your local git repository:

```console
git add .
git commit -m "<AN EXPLANATION HERE>"
```
---
8. 
- Push the branch up to github and submit it as a pull request
```console
git push -u origin <branch's name>
```
This will create the branch on your GitHub project. The -u flag links this branch with the remote one, so that in the future, you can simply type git push origin.

Swap back to the browser and navigate to your fork of the project

You’ll see that your new branch is listed at the top with a handy “Compare & pull request” button, go ahead and press the button!

Once you are happy with the changes, press the “Create pull request” button and you’re done.
---