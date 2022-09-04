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


