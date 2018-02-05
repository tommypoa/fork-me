# Ruby on Rails Decal Spring 2018

In this course, we will be using Git to manage, complete, and submit all assignments. This repository is meant to serve as a quick exercise in forking a repository and pushing updates to your forked repository. This assumes you have git installed and setup.

## Instructions

### 1. Forking 

Assuming you have a browser open at https://github.com/rails-decal/fork-me, in the top right corner of the screen, click the "Fork" button to copy this repository onto your Github account.

### 2. Cloning

Clone this forked repository onto your local machine. We suggest creating a folder `railsdecal` to store your assignments and projects for this class. 

Copy the Git URL and then in terminal,

`cd railsdecal` and use `git clone` to clone the repo into the directory.

The full clone command should look like:

		git clone https://github.com/YOURGITHUBUSERNAME/fork-me.git  

### 3. Updating your repository

Let's add something to our repository! Go ahead and make whatever changes you want.

Here's an example. In terminal,

		echo hello world >> hello.txt

### 4. Adding changes

Let's make sure to stage (add) these changes so Github knows to track our new files and changes.

		git add .

### 5. Commiting changes

Commit (snapshot) these changes so you can push them up to Github.

		git commit -m "I love the rails decal! *_*"

### 6. Pushing to Github

Finally, push these changes up to Github!

		git push origin master					
