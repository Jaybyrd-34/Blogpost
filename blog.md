# Day in the life

Today I am learning how to markdown a webpage with the basic_Mark Down_ language. As of right now it is very easy to understand and intuitive to write with. Initially I thought the only markdown language was html, which I think I have a pretty good handle on, but it has taken me a little over a month to fully feel comfortable and remember the syntax of it. It is nice to know that all I have to do to get a quick webpage up is use a few symbols and voala, I have a basic page ready to go.

## Git and Github

I have started to learn how to use Github and make commits and push requests. I can now autosave my projects I am working on with a few simple commands in the command line. If for some reason a newer version of my code **breaks** I now am able to go back to a older version of said project where it did work. 
### To make a git save step by step
* to make git repository
$ git init: in current project directory to make repository

* to see new repository
$ ls -a : use the -a because . files are hidden

* To add file in terminal
$ git add file_name.html

* To commit file
$ git commit -m "add a short, descriptive present tense commit message here describing the changes made"

* To review git information
1. git log : lists commit history for current branch
2. git status: lists the files where changes have been made to be commited.
3. git about: lists the information about the currently assigned name of author

### To make Github remote repository
* log into Github and create new repository
* Name repository the same as project directory and click create

### To push my code to remote repository
* navigate to project directory in command line
 type $ git status to make sure all changes are commited and ready.

* Now tell git where our remote repository is by providing the web address.
$ git remote add // with nickname and url to web address
example: $ git remote add jt https://github.com/Jaybyrd-34/blogpost

* to see that git has done this
$ git remote -v : will show all remotes stored in it

* to push the code
$ git push // nick name master
this will push the code to the remote


