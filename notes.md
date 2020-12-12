# Notes

These are notes that I've taken throughout the course

### Module 1

### Module 2

### Module 3

**Commands**

-   `git add`
-   `git status`
-   `git diff (--staged)`
-   `git commit -a` to skip `git add`

### Module 4

**git log**

-   `git log` to show list of commits
-   `git log -{#}` to show specific number of recent commits
-   `git log --online` to show list of commits
-   `git log --stats` show longer details about each commit
-   `git log --patch` to show log with diff results

**git commit naming guidelines**

Chris Beams: <https://chris.beams.io/posts/git-commit>

**Removing Files**

-   `git rm {filename}` to stage removal and untrack (removes file from local FS as well).
-   `git rm --cached {filename}` to untrack, but not remove

**Rename/Moving Files**

-   `git mv {old} {new}` to rename {old} to {new} in project

**Branching**

See it in action: <https://git-school.github.io/visualizing-git>

-   `git branch {branch_name}` to create new branch
-   `git checkout -b {branch_name}` to create a new branch with name {branch_name} and immediately move to it
-   `git checkout {branch_name}` to switch to a given branch
