# Umars_Guide_to_Github_Repo
The purpose of this repo is to gain familiarity with Git/Github by following umarfarooq360's guide at https://github.com/umarfarooq360/learn-git-acm

I'm doing this because I can't find the desktop authentication procedure explained in the tutorial Github provides.

From the terminal, make a directory to put your code in. That'll be the "remote repository". Make it so with 
    git init
, which is executed via the terminal from within the directory. A Github repository is an online storage spot for your code. Since the "real" version is stored on Github, that online repository is the "origin". Basically we tell our computer 'Hey computer, I created this repo on github, when I push, I want my code to go to this github repo'. To do this, in your terminal type 
    git remote add origin https://github.com/nameOfYourRepo.git
