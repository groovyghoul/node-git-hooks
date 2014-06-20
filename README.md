node-git-hooks
==============

My git-hooks written in node

### commit-msg ###

To install:
Copy `commit-msg` to `.git/hooks`

Purpose:
Ensures that all commits are associated with the ticket being worked on.
The format is:

  AIS-123

### prepare-commit-msg ###

To install:
Copy `prepare-commit-msg` to `.git/hooks`

Purpose:

If branch name is `123-rest-of-branch-name`, ensures it will be included in the commit msg as:

  AIS-123-rest-of-branch-name

