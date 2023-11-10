# Instructions to create a repository

1. Create a new directory in your environment called "new-project"  
	`mkdir "new-project"`  
2. Go to the "new-project" directory  
	`cd new-project`  
3. Initialize a new public Git repository inside the "new-project" directory  
	`git init`  
4. Create a new file named "README.md" and add the initial text to it  
	`echo "Instructions to create a repository" > README.md`  
5. Prepare the file "README.md" for the comm  
	`git add README.md`  
6. Commit the changes to the repository with the "init" commit message  
	`git commit -m "init"`  
7. Create a new branch called "development" and move to it  
	`git branch development`  
	`git checkout development`  
8. Add the instructions to the "README.md" file and prepare them for the commit  
   Commit the changes in the "development" branch with a notification of the commit  
	`git commit -am "Added instructions"`  
9. Merge changes from the "development" branch into the "main" branch  
	`git checkout main`  
	`git merge development`  
10. Check the status, make sure everything is up to date  
	`git status`  
11. Commit the changes  
	`git commit -m "Combined changes from the development branch into the main branch"`  
