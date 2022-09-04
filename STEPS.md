PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch main  
Switched to branch 'main'
M       README.md
Your branch is up to date with 'origin/main'.

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "1.Added basic info but no date"

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push -u origin main

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "2. Added date to basic info"    

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix
Switched to branch 'bugfix'

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "3. creation up brach added name"

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push -u origin bugfix

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "4. added professor name"         

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push                                       

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git branch bugfix-experimental

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix-experimental
Switched to branch 'bugfix-experimental'

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch main               
Switched to branch 'main'

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git merge bugfix
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git merge --abort

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git merge main
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "5. Merge from main"

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push      

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "6. added style to title"

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix-experimental
Switched to branch 'bugfix-experimental'

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "7. creation of branch and added STEPS"

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push -u origin bugfix-experimental

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add . 

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "8. added terminal commands to STEPS"    

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push   

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "9. cleaned up STEPS"                

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push 

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch main
Switched to branch 'main'

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "10. added style to title for main" 

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push       

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch bugfix
Switched to branch 'bugfix'

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git merge bugfix-experimental
Merge made by the 'ort' strategy.
 STEPS.md | 78 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 78 insertions(+)
 create mode 100644 STEPS.md

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git add .

**ACTUAL 12**
PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git commit -m "11. Merger from experimental"
[bugfix c1068d7] 11. Merger from experimental
 1 file changed, 24 insertions(+)

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git push

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git switch main
Switched to branch 'main'

PS C:\Users\Knile\Lone Coding Projects\Class Projects\GitAssignment> git merge bugfix
Auto-merging README.md
Merge made by the 'ort' strategy.
 README.md |   4 ++-
 STEPS.md  | 102 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 2 files changed, 105 insertions(+), 1 deletion(-)
 create mode 100644 STEPS.md
 
 git add .
 
 git commit -m "14. Done"

 git push
