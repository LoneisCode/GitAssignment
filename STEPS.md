PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git status
On branch bugfix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch main
Switched to branch 'main'
M       README.md
Your branch is up to date with 'origin/main'.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix
Switched to branch 'bugfix'
M       README.md
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch main  
Switched to branch 'main'
M       README.md
Your branch is up to date with 'origin/main'.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "1.Added basic info but no date"
[main 104cc60] 1.Added basic info but no date
 1 file changed, 4 insertions(+), 1 deletion(-)
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push -u origin main
Enter passphrase for key '/c/Users/Knile/.ssh/id_ed25519': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 324 bytes | 324.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:LoneisCode/GitAssignment.git
   450e70b..104cc60  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "2. Added date to basic info"    
[main e0ca2bc] 2. Added date to basic info
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push               
Enter passphrase for key '/c/Users/Knile/.ssh/id_ed25519': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 282 bytes | 282.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:LoneisCode/GitAssignment.git
   104cc60..e0ca2bc  main -> main
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix
Switched to branch 'bugfix'
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "3. creation up brach added name"
[bugfix 7023efd] 3. creation up brach added name
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push -u origin bugfix
Enter passphrase for key '/c/Users/Knile/.ssh/id_ed25519': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 286 bytes | 286.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'bugfix' on GitHub by visiting:
remote:      https://github.com/LoneisCode/GitAssignment/pull/new/bugfix
remote:
To github.com:LoneisCode/GitAssignment.git
 * [new branch]      bugfix -> bugfix
branch 'bugfix' set up to track 'origin/bugfix'.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "4. added professor name"         
[bugfix 0ec9ada] 4. added professor name
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push                                       
Enter passphrase for key '/c/Users/Knile/.ssh/id_ed25519': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:LoneisCode/GitAssignment.git
   7023efd..0ec9ada  bugfix -> bugfix
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git branch bugfix-experimental
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix-experimental
Switched to branch 'bugfix-experimental'
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch main               
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git merge bugfix
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> ^C
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git merge --abort
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix
Switched to branch 'bugfix'
Your branch is up to date with 'origin/bugfix'.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git merge main
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git merge main
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git status    
On branch bugfix
Your branch is up to date with 'origin/bugfix'.

All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
        modified:   README.md

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "5. Merge from main"
[bugfix c3ed2c3] 5. Merge from main
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push      
Enter passphrase for key '/c/Users/Knile/.ssh/id_ed25519': 
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 357 bytes | 357.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:LoneisCode/GitAssignment.git
   0ec9ada..c3ed2c3  bugfix -> bugfix
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git branch
* bugfix
  bugfix-experimental
  main
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "6. added style to title"
[bugfix e86620b] 6. added style to title
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push
Enter passphrase for key '/c/Users/Knile/.ssh/id_ed25519': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 336 bytes | 336.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:LoneisCode/GitAssignment.git
   c3ed2c3..e86620b  bugfix -> bugfix
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix-expriment
fatal: invalid reference: bugfix-expriment
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix-experiment
fatal: invalid reference: bugfix-experiment
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix-experimental
Switched to branch 'bugfix-experimental'
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git branch
  bugfix
* bugfix-experimental
  main
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix-experimental
Already on 'bugfix-experimental'
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "7. creation of branch and added STEPS"
[bugfix-experimental aab9c02] 7. creation of branch and added STEPS
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 STEPS.md
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push -u origin bugfix-experimental
Enter passphrase for key '/c/Users/Knile/.ssh/id_ed25519': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'bugfix-experimental' on GitHub by visiting:
remote:      https://github.com/LoneisCode/GitAssignment/pull/new/bugfix-experimental
remote:
To github.com:LoneisCode/GitAssignment.git
 * [new branch]      bugfix-experimental -> bugfix-experimental
branch 'bugfix-experimental' set up to track 'origin/bugfix-experimental'.
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push -u origin bugfix-experimental