# Chaithu-s-Work
Git Merge vs. Git Rebase
git merge
git merge is used to combine the changes from one branch into another. It creates a new merge commit that ties together the histories of both branches.

Use case: When you want to preserve the complete history of both branches.
Pros:
Maintains the context of the original branches.
Easier to understand the timeline of feature development.
Cons:
Can lead to a more cluttered history with many merge commits.

git rebase
git rebase moves or "replays" your branch’s commits on top of another branch. It creates a linear history by rewriting commit hashes.

Use case: When you want a clean, linear project history.
Pros:
Cleaner commit history.
Easier to follow the progression of changes.
Cons:
Rewriting history can be dangerous if the branch is shared with others.
