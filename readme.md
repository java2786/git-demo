Install git

configure git
$ git config --global user.name "arun kumar"
$ git config --global user.email "arun.kumar@iiht.co.in"

see configs
$ git config --global user.name
$ git config --global user.email


check git version
$ git -v

convert current directory into git repository
$ git init

add a file in staging area
$ git add filename
$ git add *
$ git add .

remove a file from staging area
$ git reset filename
$ git reset .
$ git reset *

check staging area
$ git status


commit changes
$ git commit -m "message"


clone git repo ->
$ git clone repo-url 

create gitignore file