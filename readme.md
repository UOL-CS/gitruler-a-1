<!--
Marked Style: Github
-->

# GitRuler Section A

This repository is section A of the [GitRuler exercises](https://github.com/UOL-CS/gitruler-exercises).

## Introduction

If you do not already have a your own repository for these exercises [fork this repository](https://help.github.com/articles/fork-a-repo/). Clone this repository

At any time you can run gitruler to check your progress. From the command line run:

`java -jar <path to gitruler.jar>`

For more information on running gitruler look at the [project repository](https://github.com/rcraggs/gitruler).

## Instructions

1. After cloning the repository change into the directory on a [command line](https://www.techopedia.com/definition/3337/command-line-interface-cli).
2. Run gitruler to initialise the exercise.

## Configuring Git

To make sure that your are correctly listed as an editor in the history of a file you must configure `git` on each new machine (or network if your profile follows you around).

1. Configure `git` with your correct `user.name` and `user.email`. If you are using Github you should use the email address used to set up you Github account which you can find on the [GitHub email settings page](https://github.com/settings/emails)
1. Configure `git` so that when it wants you to enter some text (e.g. for a commit message) it will open an editor that you are able to use (`nano` is usually a safe bet) 

## Changing files and committing those changes.

1. Use a [text editor](https://en.wikipedia.org/wiki/Text_editor) to add `Manfred Delmonte` to a new line in `files/employees.txt` and `Peaches` to a new line in `files/products.txt`.
1. Stage the changes that you made to the files. Use the `git status` command to check that you have staged all of your changes.
1. Commit your staged changes using the commit message "Add Manfred and Peaches". 

## Submitting the results

Once the exercise is complete, push this repository to the remote. If there are multiple branches for an exercise, make sure that you push them all. 

To ensure that you have you correctly pushed everything that you need to, you could clone the remote repository into a separate folder and re-run gitruler.

## Resources

1. For many of the steps you could use the [Git cheat sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf) or [git - the simple guide](http://rogerdudler.github.io/git-guide/) to find the correct command.
1. For setting up your git configuration you can see the "Your Identity" and "Your Editor" sections of the [Git Pro Book](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup).
1. For staging and committing modifications to already tracked files take a look at "Staging Modified Files" and "Committing Your Changes" in [Git Pro Book]https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository). These sections will also explain how to provide commit messages.
