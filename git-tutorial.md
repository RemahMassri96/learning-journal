# Version Control System :
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
## what is git ? 
Git is the best choice for most software teams today. While every team is different and should do their own analysis.
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

Here are the Git commands that used :
1. git config : This command sets the author name and email address respectively to be used with your commits.
 -  usage : `git config –global user.name “[name]”`
  -  usage : `git config –global user.email “[email address]”`
2. git init   : used to start a new repository.
   - usage : `git init [repository name]`
 3. git clone  : This command is used to obtain a repository from an existing URL.
      - usage : `git clone [url]`
 4. git add  : This command adds a file to the staging area.
      - usage : `git add [file]`
      
 5. git commit : This command records or snapshots the file permanently in the version history.
  - usage : `git commit -m “[ Type in the commit message]”`
  6. git status  : This command lists all the files that have to be committed.
    - usage : `git status`   
    7. git push : This command sends the committed changes of master branch to your remote repository.
      - usage : `git push [variable name] master `
      
  8. git pull : This command fetches and merges changes on the remote server to your working directory.
       - usage : `git pull [Repository Link]`







