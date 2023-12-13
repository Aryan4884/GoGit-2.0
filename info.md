Hey, this is Sanyam Agarwal, a sophomore at IIITA! 

Merging branch-2 into branch-1 can be either a fast-forward merge or a three-way merge, depending on the commit history of the branches.

#Fast-Forward Merge:

>If branch-1 has not diverged from the common ancestor with branch-2, meaning there are no new commits on branch-1 since the point where branch-1 and branch-2 diverged, then Git can perform a fast-forward merge.
>In a fast-forward merge, Git simply moves the pointer of branch-1 to the latest commit of branch-2. This is possible because there are no conflicting changes on branch-1.

#Three-Way Merge:

>If there are new commits on both branch-1 and branch-2 since their divergence, Git will perform a three-way merge.
>Git identifies the common ancestor commit of both branches and creates a new commit that combines the changes from both branches. If there are conflicting changes, manual resolution is required.
