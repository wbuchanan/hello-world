# Using Git to Promote Collaboration and Reproducible Research
## Intro to Git
Git is a version control system that tracks changes in a file directory.  It is an application that can run on your computer and track changes to your files. 

It prevents you from ever dealing with files like: `Board_Presentation_ABSOLUTE FINAL w supt feedback v2.docx` ![Final Version](img/00_final_version.png)__

### Initializing a Git repository and committing changes
__1. You can open a git command line interface by right clicking in a folder. ![Git Bash](https://github.com/nathant23/hello-world/blob/master/img/01_start_Git_Bash.png)__

__2. Git begins tracking a folder (repository) when you type the command `git init`. Only folders in which you have initialized git are tracked. ![git init](https://github.com/nathant23/hello-world/blob/master/img/02_git_init.png)__

__3. You can check the status of what is being tracked by the command `git status`. ![git status](https://github.com/nathant23/hello-world/blob/master/img/03_git_status.png)__

__4. In order to create a snapshot of the files in your repository you need to "stage" the changes that you want to commit to the snapshot.  This is done by the command `git add <file name>` or add multiple file changes with `git add .` ![git add](https://github.com/nathant23/hello-world/blob/master/img/04_git_add_and_status.png)__

__5. A snapshot of your repository happens when you 'commit' the changes.  This is accomplished by the command `git commit -m 'My message'` where 'My message' is the message you create to indicate what is being committed (snapshot). ![git commit](https://github.com/nathant23/hello-world/blob/master/img/05_git_commit.png)__

__6. After you have edited a file you can check the status of you repository to see that a file has been changed.![git status modified](https://github.com/nathant23/hello-world/blob/master/img/06_git_status_modified.png)__

__7. If you would like these changes to be part of the next commit you need to 'stage' the changes.  This again is done by the `git add <file name>` or `git add .` command. ![git add .](https://github.com/nathant23/hello-world/blob/master/img/07_git_add_..png)__

__8. You can now commit the modifications that you have added with `git commit -m 'Another message'` ![git commit mod](https://github.com/nathant23/hello-world/blob/master/img/08_git_commit_modification.png)__

### Branching
Git branching is a powerful feature that allows you to continue development or edits without messing with the main files.

__9. You can create a branch and 'checkout' that branch simultaneously with the command `git checkout -b <new branch name>`.  This essentially gives you a copy of the set of files that existed that you can edit or add to without affecting the originals. ![git checkout](https://github.com/nathant23/hello-world/blob/master/img/09_git_checkout.png)__

__10. You can check to see what branches exist by the command `git branch` ![git branch](https://github.com/nathant23/hello-world/blob/master/img/10_git_branch.png)__

 
__11. While on the 'sdp' branch of the 'hello world' repository I have edited the file to say 'Hello, SDP' instead of 'Hello, World'.  I have also changed the name of the file. I can check the status of this branch, `git status`, to see that changes are detected by git.![git status branch edit](https://github.com/nathant23/hello-world/blob/master/img/11_git_status_delete.png)__

__12. I can now add those changes to be staged for commit. ![git add](https://github.com/nathant23/hello-world/blob/master/img/12_git_add.png)__

__13. Now those changed will be commited. Notice the new file name. ![git commit branch](https://github.com/nathant23/hello-world/blob/master/img/13_git_commit_branch.png)__

__14. We can go back to the original branch with the command `git checkout master`.  Notice that when we do this we go back to the original files.  These files do not have the edits and work that was done on the 'sdp' branch. ![git commit branch](https://github.com/nathant23/hello-world/blob/master/img/14_git_checkout_master.png)__


### GitHub





