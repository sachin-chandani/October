You can add your profile in index.html

Steps :- 

1) Getting Repo on your local machine :-
	a) fork this repo https://github.com/ishucr7/October.git
	
	b) git clone https://github.com/username/October.git
		// where username is actually your username of github
		// Actually its the link of your forked repo
2) Getting Started :-
	a) Make a branch by doing :-
		a.1)  git checkout -b name
			// "name" is the branch name which you want to work in
			// It will make a copy of the master branch . By executing this command you actually get shifted to this branch .
			   you can check it by git branch . The highlighted branch is the one in which you are in .
	
3) Making Changes
	a) git grep "Aashish" 
		// This will show you the file ( which is actually "index.html" ) and the line in that file where "Aashish" is written.
	
	b) Add your profile .
	
	c) git commit -m "Added my profile " 
	   	// Basically the message which will be shown on your commit
	
	d) git add index.html
	  	
	e) git push origin name
	   	// where name is the name of your branch

4) Create a pull Request
	[a link](https://help.github.com/articles/creating-a-pull-request/)


Congratulations you have made your first pull request :) 

You can check your profile by getting into directory Hactober and then
firefox index.html
