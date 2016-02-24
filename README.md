web-app-template-simple
=======================
###Starting a new project
1. clone copy of the news apps template from chris’ git page
2. rename locally

git command to clone and rename a repository locally: 
	$ git clone [repository address here] file-name-here
```

###Save to YOUR repository
1. add all untracked files to the repository
```
	$ git add .
		OR
	$ git add -A
```
2. create a new repo on YOUR git page
```
	open your git page, create and name a new repository.
```
3. remove the original ORIGIN (which links to Chris’ git page)
```
	$ git remote rm origin
```
4. add YOUR origin to the repos
```
	$ git remote add origin [address copied from newly created repository]
```
5. commit your changes
```
	$ git commit -am "insert message here"
```
6. push to your new repository 
```
	$ git push origin master



pwd == working directory
markdown cheat sheet
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
