Homework One - Version Control Using Git and GitHub IDS2022F
Humza Humayun

1. Three Historical Types of Version Control Systems:
	a. Local VCS 
	b. Centralized VCS
	c. Distributed VCS

2. Best Version Control Version?
	The best version control system is the Distributed VCS model. This is because it allows each user to have
	an entire copy of the original project without and work on it without altering the original, possibly stable
	version. The Distributed VCS model also allows the users to update and protect their code via version control. 
	Distributed VCS are not prone to having everything lost in the same way local and centralized VCS's are. 
3. Git Commands:
	a. git pull retrieves data from the remote repository and updates the local version of the repo; as a way
	to attain what has been modified from the repo to the local version.
	
	b. git status allows the user to see the stage of the git service; more specifically in the regards to how 
	ahead and behind the remote repository or the local repository is in relation to eachother. It is also used to
	show the user the staging process of their commits/pulls.
	
	c. git add --all is a command used to add all of the data and changes made in a local repository to the remote,
	it is the first step in the process of updating the remote repository. This command is usually used in tandem
	with the aforementioned git status command to see what is being staged to commit,

	d. git commit -m "latest build" is a command that, in this example, stages the changes from git add (--all) 
	by saving them (making a "snapshot"). '-m' denotes that there is a message being transferred with this 
	commit (as to remind the user what edits have been made/committed).
	
	e. The command git push --all is used to submit all the files that have been staged for committal.
	Though, the "-all" suffix is not entirely necessary, it is very good to use to ensure that all files
	set for updating into the remote repository are sent in.
