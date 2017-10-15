You can add your profile in index.html
Steps :- 
1) Clone this repo in your local machine using :-
	fork this repo https://github.com/ishucr7/October.git
	
	a) git clone https://github.com/username/October.git
		// where username is actually your username of github
		// Actually its the link of your forked repo
	b) Make a branch by doing :-
		git checkout -b name
			// name is the branch name which you want to work in
			// It will make a copy of the master branch . By executing this command you actually get shifted to this branch .You can check it by git branch . The highlighted branch is the one in which you are in .
	b) git grep "Aashish" 
		// This will show you the file ( which is actually "index.html" ) and the line in that file where "Aashish" is written.
	c) Add your profile .
	   git commit -m "Added my profile " 
	   	// Basically the message which will be shown on your commit
	   git add index.html
	  	
	   git push origin name
	   	// where name is the name of your branch

