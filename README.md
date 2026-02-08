ECE 528/L - GitHub Workshop Part I
GitHub Workshop Part II
Spring 2026

About This Repository
This repo was created for the first GitHub workshop assignment. Basically learned how to set up Git, work with repositories, and understand version control. It was actually pretty straightforward once I got the SSH keys working.

What I Learned
Setting up Git and getting familiar with the basic workflow:
* Got Git installed and configured on my computer
* Set up SSH keys 
* Created this repository and learned how to clone it locally
* Practiced the basic commands like add, commit, and push
* Changed the repo from private to public for the submission
* 
Files in This Repo
* README.md - this file
* git_test.txt - test file I created to practice the git workflow
* 
Git Commands I Used
Here are the main commands from the tutorial:

Initial Setup:
bash
git --version
git config --global user.email "arneet-kaur.lnu.499@my.csun.edu"
git config --global user.name "Arneet Kaur"

SSH Setup:
bash
ssh-keygen -t ed25519 -C "arneet-kaur.lnu.499@my.csun.edu"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
ssh -T git@github.com

Working with the Repository:

bash
git clone git@github.com:arneet-kaurlnu499-cloud/Git_Introduction.git
git status
git add git_test.txt
git commit -m "Added git_test text file"
git push origin main

Assignment Steps
1. Installed Git for Windows and configured my account info
2. Created the Git_Introduction repository (set to private first)
3. Generated SSH key and added it to my GitHub account
4. Cloned the repo to my local machine
5. Created git_test.txt and pushed it to the repo
6. Changed visibility to public and took a screenshot
7. 
Submission
Repository: https://github.com/arneet-kaurlnu499-cloud/Git_Introduction

Notes
The SSH key setup was probably the trickiest part - had to make sure the ssh-agent was running and the key was added properly. Once that was done though, everything else went smoothly. The tutorial was pretty detailed so it wasn't too hard to follow along.
Version control makes a lot more sense now that I've actually used it instead of just reading about it.


