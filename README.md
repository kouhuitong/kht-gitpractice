# kht-gitpractice

- Contact this student to ask for their GitHub handle (or GitHub "name")
- Give "collaborator" access to this person (go to Settings then Manage access, then invite them using their GitHub name).
- After this person accepts your invitation and clone your repository, find a time to meet via BBCU (you may use the main course room) or zoom or some other platform of your choice.
- Exchange ideas about what to add to your repository.
- Based on these ideas, both of you should edit the same file around the same place, separately, make a commit and push your commits to GitHub to create a conflict. Let the other person push their commit first, so you push second and you resolve the conflict. Actually: you will need to pull the other person's commit that conflicts with your own, resolve the conflict locally, then push the merged commit.
- Repeat the same process, but on the other student's repository. This time, you should push your commit first, and the other student should resolve the conflict for the repository that they own.

# Random Talk

I'm Huitong Kou.
My partner is Yike Wang.

# Tips

```bash
git log --graph
git log --pretty=oneline
git status
git add
git commit
git push
git pull
```

### Comments from Yike Wang

Great work!

Some tips from lecture notes:
- pull often
- commit your changes before pulling. Any change to an uncommitted file would stop the pull update

It is rainy today.

branching practice for today

Follow the steps below.
- each student:
  create a new branch (student A creates branch "apple", student B creates "banana" and student C creates branch "coconut" if the group has 3 students),
  add one or more commit their branch,
  and push the branch to github.
  Note: "apple" and "banana" are just placeholder names, like A and B for student names. You should of course choose names that are meaningful and related to the content that will appear on each branch. With the example from item 2, student A might call their branch "grep" and student B might call their branch "headtail".
- student A: checkout the master branch, a commit to the master branch, push to github
- each student: 
  *pull* all updates from GitHub, that is: new commit on master, and new branches created by other students on the team.
  checkout one branch that they did not create (e.g. student B checks out branch "apple")
  add a commits to that branch,
  and push to github.
- each student:
  checkout the master branch,
  *pull* any updates from github on all branches (don't forget this step!!),
  merge the branch they initially created into master,
  push to github.
