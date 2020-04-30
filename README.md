# Exercise 1: Setting Up

*In general: Please ask questions in the [ilias-Forum]() for this course, so that others can also see the question and answer*.

The goal of the first exercise is to verify that everyone has a working setup and that submitting and testing the exercises works properly. It there does have very little R content.


## Step 1
Please register on GitHub and send an e-mail with your username to `nils.reiter@uni-koeln.de`. Please be aware that everyone we do on GitHub is public and (in theory) googleable, if you do it under your real name. (I will delete everything after the summer semester).


## Step 2
Once your GitHub account has been added to the group, please `clone` the repository `https://github.com/idh-cologne-sprachverarbeitung-mit-r/exercise-01` (if you're reading this text online, it's the repository you're looking at right now).

On the command line: `git clone https://github.com/idh-cologne-sprachverarbeitung-mit-r/exercise-01.git`

## Step 3
Create a new branch. To do that, you need to pick a name, but we need to make sure that everyone uses a different branch name. If everyone uses their first name, that should not be a problem. Otherwise, think of the least popular band you're fan of and use their name, or think of something else, as long as noone else uses it too :)

On the command line: `git checkout -v BRANCHNAME`

## Step 4
Open the file `R/exercise.R` and add `World!` to the string. After that the line should read `string <- "Hello World!"`. Don't forget to save the file.

## Step 5
Add the file to the staging area.

On the command line: `git add R/exercise.R`

## Step 6
Commit the file to your branch in your local repository, and provide a commit message.

Command line: `git commit -m "Done with the exercise"`

## Step 7 
Push your branch to the server. Because this is the first time you're pushing, the server doesn't know about your branch, which is why have to state that the upstream branch (= the one on the server) should have the same name.

Command line: `git push --set-upstream origin BRANCHNAME`

## Step 8

Wait a few minutes. Then go to [https://github.com/idh-cologne-sprachverarbeitung-mit-r/exercise-01/actions](https://github.com/idh-cologne-sprachverarbeitung-mit-r/exercise-01/actions), select your branch and watch for the results. If your commit has a green checkmark, you're good to go. If you see a red cross, there is a mistake in your code. In this case, you can click on the commit message and inspect the details of the mistake. After that, you should go back to step 4, fix the bug, and add/commit/push again.