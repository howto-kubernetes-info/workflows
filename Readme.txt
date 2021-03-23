Git allows you to use the workflow that fits your needs.

In the simplest workflow, you only work on the main branch.

In a little more complex workflow, you work on feature branches that are merged into the main branch.

A often used git workflow is made popular by Vincent Driessen.
Where you have a main and a develop branch that always exist.
But no work is done on the main and the develop branch.
New features are developed in temporary feature branches.
Finished features are commited, tested and then merged into the develop branch.
Releases are prepared in temporary release branches.
Release branches are merged into the main branch and into the develop branch.
Critical bugs in the main branch are fixed in temporary hotfix branches.
Hotfix branches are merged into the main and the developer branch.

An other popular git workflow is the pull request workflow made popular by Github.
In this workflow, some or all merges are only done after a pull request and code reviews.
The pull request workflow can be combined with most other workflows.

With the Fork Workflow, everybody with sufficient rights can fork the upstream repostitory
The forked repository is cloned and the work is done on the clone.
After the work is ready, the work is pushed to the fork and a full request informs the upstream repository
 
