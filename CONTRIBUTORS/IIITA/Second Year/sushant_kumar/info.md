It is a 3 way merge as defintion is down...


The reason it is called a 3-way merge is because the Merge Commit is based on 3 different commits.

The common ancestor of our branches, in this case sir you have added a commit. This commit contains code before we diverge into different branches.

The tip of the Master branch, that is the last commit performed on the Master branch that i have done while mergig my branch-2 to branch-1

The tip of the Feature branch, the last commit performed on the Feature branch that i will do while while merging my branch-1 to your branch-1

To merge the changes from both the branches, Git looks at the three different snapshots - the before snapshot and the after snapshots. Based on these snapshots, Git combines the changes by creating the new commit called the Merge Commit..