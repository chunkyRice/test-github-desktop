# test-github-desktop
 Test repo

 So what does this button do?

# 'Uploading files' as it were

In Git you don't upload files, you commit them.

In the SCM view of VSC there's a list of files that have been changed since the last synchronization.
You can choose to make a distinction between the files you do, and the files you don't want to synchronize.
You do this by staging the ones you do want to synchronize.
The only differnce this makes, is that they now appear in the list with staged files.

The next step is committing the files that should be synchronized.
In the menu for the current repository you can choose to commit all, or to commit all staged.
Choose the second option to only commit the files you just staged.

After committing, the files have only been committed to the local repository.
In order to push these commits to the github server, you need to synchronize the offline and online repositories (or rather: branches)
You click on the synchronize item next to the source control provider to do so.
Now your committed files will appear, changes and all, on the github server as well

