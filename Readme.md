// Learing github now

git clone (https,ssh,github cli)
git add-> tell git I would like to add a file as one to track next time I make a commit
the step is needed because if we are working on ten different files and if I want to add only three because I am still working on the other.
git commit -m "message"-> the message property tells what changes we have made recently so that they can be used later. Now we dont see this on the github because whatever we have made did only to the local repository now we have to push it to the github
git status -> gives what is going on in the local repository with respect to the github
git push-> going to push it to the github
git commit -am-> git commit all the files that have been changes with the message

//Until now we have pushed to the git hub let us pull some from the github and let us do it
git pull-> pulles the latest code that is on the github

//Merge conflicts
Decide if you want to keep only your branch's changes, keep only the other branch's changes, or make a brand new change, which may incorporate changes from both branches. Delete the conflict markers <<<<<<<, =======, >>>>>>> and make the changes you want in the final merge.
Merge conflicts happen when you want to do some changes(commits) to the code and some one else wants to do some other changes


git log-> to track all the changes you have made in the repository
git reset->current state of the repsoitory and revert it back to the older state of repository. Couple of ways are
git reset --hard <commit>->using commit hashes revert it to the previous state with the help of that commit hash
git reset --hard origin/main-> resetting back to the state that is on the github

//Brancing
git's way of working on different parts of the repository at the same time

                                               -->start new feature->keep working(feature) 
                                            --
                                         --
first commit--> changes-->more changes---------->     fix bug(master/main(default))-->head
there are two branches master and feature  and where the head indicates where we are working right now like here on the master it can be on the feature as well and when we 
fix the issue we will merge the branches
git branch->tells us on which branch we are (*)
git checkout -b <name of new branch>--> switches to a new brach of given name

