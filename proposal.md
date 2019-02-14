# go-review

## Purpose

go-review is a go cli utility created to help ease the process of code reviewing a large amount of repositories.  It is expected that the utility will be able to access a column in a google sheet. Clone the repos in the column into a folder with the name of the owner appended.  It will then, strip the .git directory from each file and intialize the parent directory as a git repository.