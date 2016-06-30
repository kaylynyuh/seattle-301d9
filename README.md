# Code 301: Intermediate Software Development

Welcome to Code 301! This is a class that builds on your fundamental knowledge of HTML, CSS, JavaScript, git, and general web development, to prepare you for the deep dive of any Code 401 class.

# Introduction

We are going to learn about many different topics of web development. The overall structure of the course is based on Model-View-Controller (MVC), which is a common design pattern for web applications.

The general course schedule is:

Full Time  | Part Time    | Topic
-----------|--------------|---------------
Week 1     | Week 1 and 2 | The View
Week 2     | Week 3 and 4 | The Model
Week 3     | Week 5 and 6 | The Controller
Week 4     | Week 7 and 8 | Your Project

## Slides from class

- Slides will be placed in each class' lecture subdirectory after they are presented.

## Videos

- [YouTube Playlist Coming Soon!](about:blank)

## Assignments

Lab-time code assignments follow each class time. You can find these assignments in the subdirectories of each class folder. Generally, you'll have a "pair" assignment that you'll work on with a classmate, and an individual "sandbox" assignment in which you'll build up your own online portfolio. Useful for your coming career change!

Instructions for completing and submitting the assignments can be found in the README files of the appropriate subdirectories.

Assignments are submitted using a professional-grade git-flow. If you haven't done so already, it's time to get comfortable with the core git commands. Don't worry, we'll give you step by step help as needed.

# Required Computer Setup

Instructions can be found here: https://github.com/codefellows/code-301-prework/blob/master/README.md#code-301-pre-work-intermediate-software-development

##Create and setup your 301 directory structure
 
 - Navigate within your terminal to your Projects folder (or an equivalent, familiar, and easy to access folder).
 
1.  `mkdir 301` - this will be your parent folder to house your **fork** of the class repo.
2.  `cd 301`
3.  `mkdir lab-assignments`
4.  While you are here on GitHub, let's fork this repository. Yes, **this** repo you are currently on! Click on the `Fork` button, and on the resulting page copy the URL link of your brand new fork.
5.  Back in the terminal, make sure you are in the `lectures-repo` folder and `git clone THE-URL-YOU-JUST-COPIED lectures-repo` (where `THE-URL-YOU-JUST-COPIED` is the URL of your forked repo you just copied. The last argument ('lectures-repo') changes the directory name of the repository.
6.  After the cloning completes, `cd` into this repo.
7.  Type `git remote add upstream https://github.com/codefellows/seattle-301d9.git` to enable quick access to future updates.
7.  Type `git remote -v` to verify that your `origin` remote points to your GitHub account's forked 301 repo, and that your `upstream` remote points to the codefellows account.
8.  `mkdir lab-assignments`
8.  `cd lab-assignments`
9.  `mkdir my-forked-labs`
10.  `mkdir partners-forked-labs`
5.  We highly value pair programming! On days where you begin as the navigator, you will clone your **partner's** lab assignment into the `partners-forked-labs` directory when it is your turn to be the driver.
6.  `cd my-forked-labs`
7.  Back here on GitHub, head to the separate GitHub site where all lab assignments can be found: https://github.com/codefellows-seattle-301d9
8.  You may fork and clone the available repos into your `my-forked-labs` folder. These repositories will periodically be added/updated throughout the course. Therefore:
9.  Be sure to add the `upstream` remote for each one with git:  
https://help.github.com/articles/configuring-a-remote-for-a-fork/

Congrats! You're all done.
