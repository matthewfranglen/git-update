GIT-UPDATE
==========

This will update all of the branches which track remotes in the current repository. This will restore HEAD to the original location after that has completed.

If an error occurs then the update will stop, and error will be prominently displayed. HEAD will be returned to the original location.

This supports HEAD being on a branch or in a detached state.

This will not create branches if there are untracked branches on the repository.

Installation
------------

Clone the repository and put git-update in a folder on your path, or add the repository folder to your path.

Useage
------

Once correctly installed it should just be a case of calling:

    git update
