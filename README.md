# Assignment for BT4BR exercise session nr.5

## Bacis information about author
Date: 08.04.2025<br>
Name & surname: Maksymilian Gmur<br>
Collage: Jagiellonian University<br>
Field of study: Bioinformatics<br>
Degree: Bachelor<br>

## GitHub commands breakdown
This section will cover the most usefull commands that can be used to eddit GitHub repositories.
### Basic workflow
**It describes a line of commands that are always used if you want to change something in your repository.**<br> 
`git add -u`<br> 
`git commit "Commit name"`<br>
`git push origin branch`<br>
### Merging conflicts 
**This section will provide simple commands that can be used if you encounter merging conflict.**<br>
`git log --merge`<br>
*This command wil provide you with insight to  what is causing the conflict*
*The conflicting changes will be put together in a edited file.*<br>
`git add -u File_with_conflict`<br>
`git commit -m "Fix merge"`<br>
`git push origin`<br>
*Before adding file you can manually edit the file to decide which change you want to leave*
### Git commands
- `git checkout`: (changees working branch)
- `git merge branch`: (Merges content of current branch with branch listed in commend)
- `git show`: (Shows the contents of a single commit)
- `git add`: (Select files that will be commited)
	- `git add .` (Adds all files in the directory)
	- `git add -u` (Adds only modified files)	 


