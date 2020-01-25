Answers to questions:

1. Use `git status` to see which branch you are on.
2. What does `git log` look like?

fatal: your current branch 'master' does not have any commits yet

3. Create a file
4. What does the output from `git status` look like now?

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file1.txt

nothing added to commit but untracked files present (use "git add" to track)

5. `add` the file to the staging area
6. How does `git status` look now?

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   file1.txt

7. `commit` the file to the repository
8. How does `git status` look now?

On branch master

nothing to commit, working tree clean

9. Change the content of the file you created earlier
10. What does `git status` look like now?

On branch master

Changes not staged for commit:

  (use "git add <file>..." to update what will be committed)
  
  (use "git restore <file>..." to discard changes in working directory)
  
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")

11. `add` the file change
12. What does `git status` look like now?

On branch master

Changes to be committed:

  (use "git restore --staged <file>..." to unstage)
  
        modified:   file1.txt

13. Change the file again
14. Make a `commit`
15. What does the `status` look like now? The `log`?

git status:

On branch master

Changes not staged for commit:

  (use "git add <file>..." to update what will be committed)
  
  (use "git restore <file>..." to discard changes in working directory)
  
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")

git log:

commit 07b305cbf0b42c51d242c7f9bb11469b23a54c44 (HEAD -> master)

Author: ajleon2 <ajleon2@uci.edu>

Date:   Fri Jan 24 03:33:32 2020 -0800

    After the first change to file1.txt

commit fc3d9ab2294e26330f14bc5d584ff90325428b5f

Author: ajleon2 <ajleon2@uci.edu>

Date:   Fri Jan 24 03:30:39 2020 -0800

    Added file1.txt


16. Commit the newest change
