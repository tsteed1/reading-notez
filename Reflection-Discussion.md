# Reflection and Discussion
## Tracking and Staging a New File
Single File
Track one file only by using the following format:
git add filename
All Files
Track all files in a repository by using the following command:
$ git add *
*After using these commands, files are tracked and staged for committing.
After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD ..." to unstage)
new file: EXAMPLE
This information tells us that there are changes to be committed and that the file has been staged.
## Adding Remotes
To create a new remote Git repository with a short name, use the following format:
git remote add shortname url
Example:
$ git remote
origin
$ git remote add js https://github.com/janesmith/project1
$ git remote -v
origin https://github.com/johndoe/project1 (fetch)
origin https://github.com/johndoe/project1 (push)
js     https://github.com/janesmith/project1 (fetch)
js     https://github.com/janesmith/project1 (push)
This addition of these remote and short names allows you to use shortnames for Git collaboration.
## Pushing
To push your changes “upstream” for sharing, you would use the following git push command format:
git push [remote-name][branch-name]
Example:
$ git push origin master
*This command pushes committed changes from your local “master” branch upstream to the “origin” server.
Note: You can only successfully push changes upstream if you have write access for the server from which you cloned, and if someone else has not pushed changes upstream that you haven’t pulled yet. If a collaborator pushed changes upstream after you had cloned, your push will not be successful. You will have to pull new changes and merge them with your branch before you can successfully push your changes upstream.