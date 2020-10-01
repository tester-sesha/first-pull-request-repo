<h1 align="center">Hello World! This repository will be your one-stop guide to creating your first pull request!</h1>

<div align="center">
    <a href="https://github.com/seshagopalselvakumar/first-pull-request-repo/stargazers"><img src="https://img.shields.io/github/stars/seshagopalselvakumar/first-pull-request-repo" alt="repo stars"></a>
  <a href="https://github.com/seshagopalselvakumar/first-pull-request-repo/network/members"><img src="https://img.shields.io/github/forks/seshagopalselvakumar/first-pull-request-repo" alt="forks badge"></a>
  <a href="https://github.com/seshagopalselvakumar/first-pull-request-repo/pulls"><img src="https://img.shields.io/github/issues-pr/seshagopalselvakumar/first-pull-request-repo" alt="pull requests badge"></a>
  <a href="https://github.com/seshagopalselvakumar/first-pull-request-repo/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/seshagopalselvakumar/first-pull-request-repo"></a>
  <a href="https://github.com/seshagopalselvakumar/first-pull-request-repo/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/seshagopalselvakumar/first-pull-request-repo"></a>
</div>

<div align="center">
  <i>Submit your first pull request by following the steps given below!</i>
</div>

### Step 1
The first step you want to do in-order to contribute to an open source project is to **_fork_** the project. This will create a copy of the project under your account.<br>
You'll see the fork option on the top right hand side of the screen.
- Click on the fork button.
<details open>
  <summary>Fork Button Image</summary>
    <img src="https://github.com/seshagopalselvakumar/first-pull-request-repo/blob/master/Resources/forkimage.PNG" alt="fork button Image">
</details>

### Step 2
Now, you have to clone the forked repository. This will create a local copy of the project on your machine.

You can do this in 2 ways:


  


1. OPTION 1
  - Click on the clone button.
  - Download the ZIP and then extract it.

<h4>Download ZIP and clone options:</h4>
<img src="https://github.com/seshagopalselvakumar/first-pull-request-repo/blob/master/Resources/downloadzip.PNG" alt="Code Button Image">
  
2. OPTION 2
  - Click on the clone button.
  - Copy the link under HTTPS section.
  - Open terminal/git bash/command prompt.
  - Type -
  ```
  git clone
  ```
  - Now paste the link.
  - The resulting command should look something like this:
  ```
  git clone https://github.com/YOUR_USERNAME/first-pull-request-repo.git
  ```
<h4>Cloning though Windows PowerShell:</h4>
  <img src="https://github.com/seshagopalselvakumar/first-pull-request-repo/blob/master/Resources/clonerepo.PNG" alt="fork button link">


### Step 3
Let's start working on the project now! 
We need to change directory into cloned folder by typing the following command.
```
cd first-pull-request-repo
```
Now, BEFORE CHANGING ANYTHING, make sure you're working on a different branch and not in master. 
To create a new branch, from the terminal inside your current project directory type the following command.
```
git branch YOUR_GITHUB_USERNAME-profile
```
Obviously you'll have to replace the YOUR_GITHUB_USERNAME with your GitHub username.<br>
(You can give any name to your branch which describes the purpose of the branch. Since here we're adding your profile to the profiles directory, we'll simply give the name of the branch as above. 
<br>
eg: git branch seshagopalselvakumar-profile. )<br>
Once you have created the new branch we'll change the current branch from master to your newly created branch.<br>
Execute the following command on your terminal.
```
git checkout YOUR_BRANCH_NAME
```
<h4>It should look like this, with your username in place of mine:</h4>
<img src="https://github.com/seshagopalselvakumar/first-pull-request-repo/blob/master/Resources/Branching.PNG" alt="Branching procedure">

### Step 4
- Move into the profiles directory in cloned project.
```
cd profiles
```
- Create a new file called YOUR_USERNAME.md using the following command.
```
touch YOUR_USERNAME.md
```
- Navigate into the project directory (through your file manager) and open this file in your favourite editor.
- fill the details as shown below:
```
---
username: YOUR_USER_NAME
fullname: YOUR_FULL_NAME
---
```
- Save and clone the file.<br>
<details>
  <summary>Your file should look something like this(With your names ofcourse</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/editing%20markdown.PNG" alt="markdown file image">
</details>

**NOTE**: This is just a way of simulating - you making changes into the project file. 

### Step 5
- Now we need to stage all the changes we made. 
- Open the terminal again and inside the project directory and execute following commands.
```
git add .
```
- The above command staged all the changes, now we need to commit them with a suitable message. You can commit using the following command.
```
git commit -m "YOUR_COMMIT_MESSAGE"
```
Example:
```
git commit -m "Hey, I just added my profile in the profiles directory"
```
<details>
  <summary>Commiting Image</summary>
  <img src="https://github.com/nirbhayvashisht/first-pr-repo/blob/master/Resources/committed.PNG" alt="Commiting Image">
</details>

