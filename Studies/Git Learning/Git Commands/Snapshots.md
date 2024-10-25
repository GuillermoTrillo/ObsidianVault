To start a snapshot, first you need to have a repository. To initialize the repository, choose the directory (a folder, for example) where you will leave the repository in. After that, use the command:

#git _init_

To initilize a empty repository.  Creating a commit is like creating a "snapshot" of our current program state, and saving it into the repository. 

# Workflow

First, you make the changes that you want to do. Then, you put then into the "Staging Area", which is a intermedium place between your main files and the repository. When you end changing things, you look at the staging area to see if everything is correct, and THEN you actually create the commit. 

The staging area is **not** actually cleaned up after the commit is done. That is why you should always end up sending the new changes to the staging area, so it can be updated and it doesn't end sending old code to the repository. 

##### But what are commits? 

A commit is the newest version with all the changes that you made in the files, sent into the repository. It is made by a certain amount of characteristics:

- A Id: Git gives a id to each commit, so it can be identified.
- A message: The person creating the commit must give it a meaningful message that explains the current state of the changes.
- Date: The date when it was created and sent.
- Author: The name of the person that created the commit.
- Snapshot: A complete snapshot of the project the moment the commit was created.
