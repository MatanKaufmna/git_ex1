1.# Git Basics (commit, diff, branches)

1.echo 1 > abc.txt
2.git status is red
3.git add abc.txt # git color = green
4.echo 2 >> abc.txt
5.git color  is red. same as step 2 because before git add - the file is in working tree and not in index
6.git diff
7.git diff --staged will only print changes between index tree and main tree
8.The command refers to stage2 as a revision or a path that doesn't exist.
9.git add abc.txt. git color is green
10.git diff will  shows differences between the file in the working tree and the same file in index before committing changes
11.git diff --staged <file name>
12.echo 3 >> abc.txt
13.no. because git main print differences between main and working tree. wile git diff --staged will show us the changes between the index and main
14.to let us see that the file is different between working tree and index. we can see the changes between the same file
15.git reset --hard.


# Resolve conflicts

1.git branch
2. git checkout -b Feature/lambda_migration
3.git merge feature/version1
4.gui merge
5.
   1.
   2.
   3.
   4.
   5.
6.

# Cherry picking
resolving conflicts you also probably would
1.
2.
3.
    1.
    2.
4.
5.


# Changes in working tree and switch branches

1.echo helo my name is matan > take.txt
2.git add take.txt
3.Your local changes to the following files would be overwritten by checkout
and Please commit your changes or stash them before you switch branches.
Aborting

4.
5. no it does not
6. it is force the system to 'jump' into the branch without take care for the uncommited files.

# Reset

1.
2.
   1. git reset --soft HEAD~1
   2. git reset --mixed HEAD~1
   3. git reset --hard HEAD~1
   4. git revert HEAD~1
3. HEAD~1 means one commit before the last head -1


# Working with GitHub

1.
2.
3.
4.
