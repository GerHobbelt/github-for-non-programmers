# GitHub for Non-Programmers

GitHub is a website designed for programmers to collaboratively build their code. But that doesn't mean you need to be a programmer to use it! You can get started with collaborative version-tracking of your (non-programming) work without ever writing a line of code or using the command line.

If you're unsure whether or not GitHub is something you want to try, I can understand. Learning new things is mentally taxing. So let me promise you now: once you've gone through this guide and given the GitHub workflow a try, you'll never want to go back to the way it was before. Why is that? Because the GitHub workflow is surprisingly simple and sane. You're going to eliminate a lot of problems that are *already* taxing your brain, such as "Which version of this file was the final one?" and "Who is responsible for making this edit?" Trust me, you're going to like this once you get into it.

## What is GitHub, Anyway?

Before we talk about GitHub, we have to talk about a program called **git**. Many programmers use git for **version control**, which means they use it to track any changes to a set of files they are working on. This means that any new mistakes can be reverted safely to a previous state without having to create endless copies of the same file for backup. Git will track everything in a folder you've specified. The contents of that folder are called a **repository**, or **repo** for short.

Git works by allowing you to **commit** a snapshot of your work with a descriptive name. Each commit should have a name that tells you something about what you've changed since the previous commit. A list of commits  ordered newest to oldest might look like this:

* `Rewrote introduction to match section one` *(<- what you did most recently)*
* `Wrote section one`
* `Wrote introduction`
* `Added first text file`
* `Initial commit` *(<- what you did first, often just creating an empty repo)*

Isn't that more informative than several copies of a Word document named `Content.docx`, `Content Final.docx`, `Content Final FINAL.docx`, etc.? By using git commits, you don't need multiple copies of a regularly changed file; there's only the one file you care about, and all the snapshots you took along the way. And with meaningful commit messages, you don't have to guess what changes are in what version of your work.

**GitHub** is a website that lets you store a copy of your git repository online where you can your collaborators can share it and work together. GitHub allows you and your team to know who is changing what and why. You can be sure that you're working off of the most recent copy of the work by pulling new commits from GitHub. And when you're done making commits of your own, you can push them back to GitHub for everyone else to use. You can also use features like GitHub Issues to keep track of problems and to-dos, and discuss them as a team. GitHub also makes it easy to control who can make what changes, and for merging different changes by different people together.

### Key Vocabulary

* Version Control: In programming, it's a way to track changes made to code over time. This means that mistakes can be easily reverted. You also don't have to worry if you're using the most recent copy of something--the version control system makes it easy to see if something has changed.
* Git: One of the most popular programs for implementing version control.
* Repository: Also just "repo" for short, it's the folder that contains all of the files you want git to track for you.
* Commit: A specific snapshot of your work. You manually choose when to create a commit, and you need to give it a descriptive name.
* GitHub: A website that lets you keep a copy of your repository online. It also allows you to collaborate with others on the same repository, keeping track of who changes what and avoiding conflicts.

## OK, Let's Get Started!

1. Register an account at [GitHub](https://github.com/join).
2. Download and install the [GitHub desktop app](https://desktop.github.com/). *(This guide will assume you're on Windows from here on out--the Mac desktop app may work a bit differently.)*
3. Enter your user info from step 1 into the GitHub desktop app you installed in step 2.

That was pretty painless, right? Let's get ready to practice creating repos, making commits, and working as a team on GitHub!
