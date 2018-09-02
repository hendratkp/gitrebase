I'm Trying to demonstrate how to do git rebase.


for example : 

1. I create new function 

function A(){

}

2. Then I commit with "first commit" on branch master

<<<<<<< HEAD
2b. Oops, Someone changes on branch master

-- so I have 2 branch, and not merged.



3. I create new branch (features),commit changes, and push it into those branch. and add some changes
=======
3. I create new branch (features),commit changes, and push it into those branch.

-- so I have 2 branch, and not merged.
>>>>>>> 0019914355d557bf5f2648628804a284ecdd5ab1
