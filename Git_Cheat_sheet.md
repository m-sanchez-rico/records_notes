### go back to selected commit in our local eenviroment.
	$ git checkout <commit-id> . On top of your current status, tranform the files to return to commitid
	$ git checkout <commit-id>

# Check if pull needed
`$ git remote update` bring your remote refs up to date. and do:
	1. `git status -uno` will tell you whether the branch you are tracking is ahead, behind or has diverged. If it says nothing, the local and remote are the same.
	2. `git show-branch *master` will show you the commits in all of the branches whose names end in 'master' (eg master and origin/master).

