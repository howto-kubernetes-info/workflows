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

