# Install git

<h3>configure git</h3>
$ git config --global user.name "arun kumar" <br/>
$ git config --global user.email "arun.kumar@iiht.co.in" <br/>

## see configs
$ git config --global user.name  
$ git config --global user.email  


## check git version
$ git -v

## convert current directory into git repository
$ git init

## add a file in staging area
$ git add filename
$ git add *
$ git add .  

## remove a file from staging area
$ git reset filename
$ git reset .
$ git reset *

## check staging area
$ git status


## commit changes
$ git commit -m "message"


## clone git repo ->
$ git clone repo-url 

## create .gitignore file
#### this file is used to hide/ignore uploads