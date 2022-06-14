## Git

Version control allows you to keep a history of files, track changes, and see who made them. Local version control does this for a
single user. Centralized version control uses a single server to track multiple user's changes. Distributed version control allows
multiple users to work together without relying on a single server and thus a single point of error.

Git is one such DVCS, and it stores files in three states.

- Modified: The file has been changed but not yet committed.
- Staged: The file is flagged as ready to be committed.
- Committed: The file is stored in local database.

You can download a local copy of a repository by using the clone command.

    git clone https://github.com/url

The local repository structure corresponds to the three stages of the file.

- Working directory: The files stored as they are being worked on.
- Index: Used for staging.
- Head: The most recent commit.

When adding a file to the local repository, git must be told to track it before it can be staged and committed. This is done by using the command `git add filename`
If you replace the filename with a \*, it will add all the files in the local repository.

Once all files are tracked, you can commit the changes with a message describing what was done using the command

  git commit -m "changed these things"

Finally, the changes can be pushed to the remote repository using the command `git push`.

If you want to save what you are working on without committing changes, you can use the `git stash` command , then `git stash apply` to retrieve the changes.
