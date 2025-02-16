# practice
## Math Club Version Control 101

We are going to do some practice git commands using this repository!

Basic commands
* First, we use `git clone https://github.com/jlynnvaccaro/practice.git`
* Then, we can create a text file (e.g. with `nano helloworld.py` or just create a file in your favorite text editor)
* We can check the status of which files are tracked using `git status`
* If you don't remember the name of a command, you can use `git --help`
* Add the file to git tracking using `git add helloworld.py`
* You can then commit any tracked changes in your repo using `git commit -m "added helloworld to the repo" `
* You can pull the latest changes from the remote git server with `git pull`
* You can push these changes to the remote git server (github) with `git push`

Slightly less basic commands
* `git branch` : Create and manage distinct branches where changes in one branch will not automatically apply to another. Good for new features.
* `git fetch` : Collect the remote changes, but does not automatically incorporate them into your repository. (Allows you to review them before incorporating.) Considered a safer version of `git pull` and good for collaborating/integrating.
* `git merge` : Combine distinct branches into a single branch. Sometimes intimidating, but good for collaborating/integrating.
* `git checkout` : Switch the state of the repo to a specific (local) branch or commit. 
