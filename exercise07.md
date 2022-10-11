# Exercise 7 - More than one changed file

1. Ensure you have a clean working directory

        git status

2. Edit one of your `fruits.txt`, add a few items

        blueberry
        strawberry
        etc.

3. Edit `appliances.txt` and add a few items

        dishwasher
        dryer
        etc.

4. Look at git status, paste the output here

        git status

5. Can you commit both of the changed files in a single commit?
Yes as long as you "add --all"
6. After you do so, check that you have a clean working directory by running `git status`, and pasting the output here
[jhl@truffle equipment]$ git status
On branch master
nothing to commit, working tree clean
7. Create a new file `equipment/furniture.txt`. Add content to both `vegetables.txt` and `furniture.txt`

8. How can you commit just one of the changed files?
You need to use the command git add [file path/file name] then git commit -m 'message' [file path/file name]
9. Check your `git status`

10. What does red text mean in the output of `git status`?
The red text is the file that has been modified and/or untracked that needs to be tracked, added, or restored.
11. What does green text mean in the output of `git status`?
Green files are those that are in the git repository and committed with your most recent changes.
12. How can you make a single file show in both red and green in the output of `git status`
You can do this by having a file that has been deleted or modified from your repository but has not been staged for commit yet.

[jhl@truffle equipment]$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    vegetables.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../vegetables.txt