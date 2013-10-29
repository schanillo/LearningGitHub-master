Hey everyone! This is an opportunity for you all to get some practice with using Git and Github. 

Use this README to follow directions on adding yourself to this repository.

The goal is for everyone to clone this repository locally on your computer, edit the 'NAMES.txt' file by adding your name, and then push their changes back to GitHub.

Here are the steps you should take: 

1) Find a place on your computer where you would like your repository. Since this one is just a test, you can do it wherever - you can just delete it when we are finished with it. 

2) Get to this directory using Terminal or a similar program. 

3) Use this resource to set up Git, if you haven't already https://help.github.com/articles/set-up-git

4a) Install Github for Mac; I haven't used it but I've heard good things.

4b) Alternatively, follow these directions:
	type 'git clone https://github.com/NUDM/LearningGitHub' . This should bring all of the files on the remote repository onto your computer.
		NOTE: This will make a new folder. you can enter this folder immediately by typing 'cd LearningGitHub'

5) open 'NAMES.txt', and add your name.

6) go to terminal in this directory, and follow these steps:
	
	1) type 'git add NAMES.txt' . This will put the status of all changed files to staging in git. if you want to add all changes at once, use git add -A.
	
	2) type 'git commit -m "<INSERT MESSAGE HERE>' . This is where you commit your files to be pushed onto the GitHub repository. The message is to provide information to collaborators about your push.

	3) type 'git pull'. This will pull the latest file changes from the repository, to check for conflicts and to make sure you are up to date.
	
	4) type 'git push origin master', and watch your files appear on the server!

If you have any questions or problems, don't be afraid to message us!



