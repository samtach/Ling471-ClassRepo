[Home](../index.md)

## Assignment 1: Preliminaries

In this assignment, you will:

* Download the data you will be working with in all (or most) of the assignments.
* Start thinking about language data in data science and machine learning terms.
* Create and start using a personal repository on GitHub where you will store your code for the class.
* Start learning how to program in python using the PyCharm IDE.
* Learn how to connect to a remote server and run python and git there.

Submission summary:
* Part 1: A text file answering questions about the IMDB review dataset.
* Part 2: Private GitHub repository created; Matt and Cassie added as collaborators.
* Part 3: 
   * A file **called your-UW-NetID-assignment1.py** in your repository
   * A question/comment in the Discussion area for Assignment 1 related to how things are organized in PyCharm (note: a question about installation won't count here!)
   * A question/comment in the Discussion area for Assignment 1 related to Source Control and how to stage, commit, push, and pull changes using, e.g., PyCharm. (You can use command line if you know how to do it, or some other tool).
* Part 4: Nothing
* Part 5: Your program from Part 3 submitted to the "patas" cluster. **It is crucial that the program name has your UW netID in it!!!**

### NB: This assignment may seem very long. 
The purpose is to give you enough time to become accustomed to a range of tools which are unavoidable in most computational work. Go through it gradually, one part at a time (and split those between multiple days if needed). Post any questions to the Discussion Board on Canvas! Consult the [Asking Questions on the Discussion Board Guidelines](../questions.md)

### Part 1: The IMDB review dataset

We will be using the IMDB review dataset ([Maas et al. 2011](https://www.aclweb.org/anthology/P11-1015.pdf))
1. Download the dataset from [here](https://ai.stanford.edu/~amaas/data/sentiment/). 
1. On **Linux/Mac**: Unpack the dataset by double-clicking on it or by using a utility appropriate for your OS. For **Windows**, download it from Canvas-->Files, but still follow the [link](https://ai.stanford.edu/~amaas/data/sentiment/) and read what's there. The dataset is an **archived folder** of the TAR.GZ type; you need special software to extract the contents. Windows does not have that software by default, but it can do .zip, so I created a ZIP version for you and uploaded it to Canvas.
1. Unpack the dataset by double-clicking on it or by using a utility appropriate for your OS.
1. Read the README file which comes with the dataset.
1. In a text file, answer the following questions about the dataset:
   1. How many movie reviews does it contain?
   1. How is the dataset divided? (Here, talk about how many reivews are in each folder and what each folder represents, in your own words. Do not copy the text from the README file.)
   1. **Why** is it divided in this way? (Make sure to give a thoughtful answer here, at least a paragraph! You may not yet know everything about this, but answer the best you can, based on what you learned in the first couple weeks of class.) (**NB: Complete closer to the due date!**)
   1. Why is a citation to the ACL paper by Maas et al. included in the README file and in the dataset description on the website? (**What is the relationship of the paper and of the dataset?** Thoughtful, paragraph-length answer here.)
   1.  Why is there a reference to Potts's paper?
   1. Would you say this README file qualifies as a "data statement" (see Bender and Friedman, 2019, which was assigned earlier). If yes, point to the specific portions of the file and map them to corresponding definitions from Bender and Friedman's paper. If no, explain what a data statement could look like for such a dataset or why the concept does not apply here. You can of course argue against data statements here if you like! It is up to you; what counts is the depth and quality of argument. 
1. Submit your text file **to Canvas**, in the appropriate area associated with Assignment 1.

### Part 2: Git and Your GitHub repository (NB: Complete what you can now and the rest after April 7.)
In this part of the assignment, you will create a GitHub repository for your code in this class.
1. Create an account on https://github.com/
1. Create a new repository; make it private. Call it whatever you like, but you will use it for this class. The screenshot below shows what creating a repository looks like on GutHub:

    <img width="736" alt="Screen Shot 2021-03-22 at 12 35 41 PM" src="https://user-images.githubusercontent.com/10963114/112048004-34b35080-8b0b-11eb-90e8-12cce9c612dd.png">

1. After you've created the repository, note its https:// address:

    <img width="1287" alt="Screen Shot 2021-03-22 at 12 04 44 PM" src="https://user-images.githubusercontent.com/10963114/112044524-26fbcc00-8b07-11eb-9dff-05106a9234ba.png">

1. Go to Settings and add maetshju and yuanheTian as "collaborators" (**NB:** this counts as your **submission** for this task):

    <img width="1286" alt="Screen Shot 2021-03-22 at 12 22 26 PM" src="https://user-images.githubusercontent.com/10963114/112046453-4a277b00-8b09-11eb-85e9-acecf900369b.png">

1. Now, install git on your machine. Click on the "Latest Source Release 2.35.1." button [here](https://git-scm.com/downloads) 
1. Ask some question about git or leave a comment about it in the Assignment 1 area on Canvas. It can be anything. 

### Part 3: Python and Visual Studio Code. (NB: Complete what you can now. You should be able to do everything after April 7.)
In this part of the assignment, you will start learning how to program in python and how to use an Integrated Development Environment. You should already have Python and PyCharm installed from lecture. You should also already know that it is working.

1. Set up Git and GitHub in PyCharm using [the steps on this page](https://www.jetbrains.com/help/pycharm/github.html#register-account).

1. Now, clone the repository you've created in Part 2 into PyCharm. Use the instructions on [this page of the PyCharm documentation](https://www.jetbrains.com/help/pycharm/set-up-a-git-repository.html#clone-repo) (go to the "Check out a project from a remote host (clone)﻿" section).

1. Add a python file to your PyCharm project. Make sure the folder from Git is selected, and then click "File > New > Python file". **It is crucial that the file name has your UW netID in it!!!**.

1. You will be asked if you want to add this file to Git. Say, "Add."

    !!!!!!!!!!!!!!!! FILE IN PYCHARM.PNG !!!!!!!!!!!!!!!!!!!!!!!!!!

    <img width="833" alt="Screen Shot 2021-03-22 at 12 13 59 PM" src="https://user-images.githubusercontent.com/10963114/112045463-1f88f280-8b08-11eb-9a96-edd63c825887.png">
1. Write a program in python which prints a statement, such as "Hello, world!" (or whatever you like).
1. In the menu, click "Git > Commit". You will see a message like this:


    !!!!!!!!!!!!!!!!!!!!  PYCHARM COMMIT.PNG !!!!!!!!!!!!!!!!!!!!!!!!!!!

    <img width="934" alt="Screen Shot 2021-03-22 at 12 24 10 PM" src="https://user-images.githubusercontent.com/10963114/112046758-ac807b80-8b09-11eb-8f22-787ea6eae364.png">

1. Enter a meaningfull commit message. Then click on the "Commit" button.

    ![VS-code-pic](https://user-images.githubusercontent.com/10963114/113206348-3627fb80-9224-11eb-96ec-f529ddef61c4.JPG)

1. In the menu, click on "Git > Push". In the dialog box that appears, click on the "Push" button. This will push your new Python file into your GitHub repository.

1. Give it a few minutes, and check that your python file can be found not only in the local copy but also in the remote repository. (NB: This will count as your **submission** for this task.) **Check once more that the file name has your UW netID in it!!! If not, rename it so it does!**
 
     <img width="962" alt="Screen Shot 2021-03-22 at 12 31 09 PM" src="https://user-images.githubusercontent.com/10963114/112047449-8ad3c400-8b0a-11eb-83cb-8e620988fad3.png">

1. Write YOUR FULL NAME in your README file using the GitHub website. Click on the README file, click on edit, write something, then click on "Commit changes". If you do not have a README file in your repository, click on the "Add file" button in GitHub and then "Create new file." Title the file README and then fill in as specified before.

    <img width="1096" alt="Screen Shot 2021-03-22 at 12 53 47 PM" src="https://user-images.githubusercontent.com/10963114/112050069-a8eef380-8b0d-11eb-900e-a3af67081026.png">
    <img width="816" alt="Screen Shot 2021-03-22 at 12 54 49 PM" src="https://user-images.githubusercontent.com/10963114/112050206-ce7bfd00-8b0d-11eb-8bb1-943a1f182d95.png">

1. Now go to PyCharm, and in the menu, click "Git > Pull" and then click "Pull" in the box that appears. Make sure that you now see the updated README!

1. Leave a question or comment about VS Code in the Assignment 1 discussion area on Canvas, if you haven't already. (The purpose is to show that you got at least some experience with the software. Otherwise, it can be about anything.)

### Part 4: Generating a personal access token.

Last year, GitHub removed the option to log into GitHub with a username and password over a command line. Instead, you have to either use a personal access token or set up SSH keys. Instructions here will be for generating a personal access token, but if you have already set up SSH keys, you do not need to do this. The official guide with pictures [is located here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).

1. Go to GitHub and log in if needed. Click on your profile image in the upper right. Click on "Settings."

1. In the page that loads, click on "< > Developer settings" at the bottom of the left-hand side. Then, click on "Personal access tokens."

1. In the next page, click on "Generate new token." Put an informative name into the "Note" field.

1. Choose how long you want the token to last for. Note that if it expires, you will need to make a new one.

1. Check the "repo" box.

1. Click "Generate token" at the bottom.

1. On the next page, you will be shown what the token is. It starts with "ghp_". Save it somewhere **RIGHT NOW**. You will not be able to see it in plain text ever again once you leave this page. It helps if you click on the two overlapping square icon next to the token, which will copy it to your clipboard. Save this token somewhere safe because you will be using it like a password on the command line.

1. If you did not get your token saved, that's okay. Just make a new one!

### Part 5: Command line and remote servers. (**NB: Complete after April 7**)

**Note, this section is a reflection of how the submission is supposed to work, but I am still getting it set up and coordinating with the system admins on this. It should be ready soon!**

It is important to be able to connect to a remote server and to be able to copy files between that server and your machine. It is also important to be able to run things like python or git via the command line (rather than in an IDE such as PyCharm or in a GUI such as github.com).

1. Open a terminal on your Linux/Mac or Windows 10 (if you have an earlier version of Windows, you will need additional instructions, so contact Matt and Cassie ahead of time).
1. Connect to patas cluster (where you should have created an account last week!):

    `ssh your-NetID@patas.ling.washington.edu`
 
     (It will ask you whether you should add patas to trusted hosts; type yes.)
1. Check that you have proper access to patas. You should see something like: `your-user-name@patas:~$` or simply `bash-4.2$`. If you don't yet have access, let Olga know. Sometimes there are delays in how the accounts are created and set up. If you see `bash-4.2$` or similar but would like to see your username and current directory instead, try typing the following in the terminal: `echo "PS1='\u@patas:\w\$ '" >> ~/.bash_profile; source ~/.bash_profile` -- and pressing `Enter`. That will change what you see in the prompt.

1. Clone your git repository into your home directory on patas:

    `git clone your-repo-address`

    It will ask you for your GitHub username and password. Your password is the token you generated in Part 4. There may be some error messages; ignore them. Just make sure you type your password correctly, or better yet, copy and paste it from where you stored it.

1. Navigate into your repository folder on patas with `cd`. Execute the python program and observe it printing whatever it prints.

    <img width="460" alt="Screen Shot 2021-03-22 at 1 45 46 PM" src="https://user-images.githubusercontent.com/10963114/112056206-fc187480-8b14-11eb-99c6-cbe36e422261.png">

1. Copy your python program to /dropbox/21-22/471 (the class folder). **It is crucial that the file name has your UW netID in it!!! Otherwise you may overwrite other people's homework, plus we won't know the program is yours and you won't get credit.**

You are now **DONE** with Assignment 1! **Don't forget to submit the file for Part 1 to Canvas**. In Assignment 2, you will already be writing programs and running them on the IMDB review data!