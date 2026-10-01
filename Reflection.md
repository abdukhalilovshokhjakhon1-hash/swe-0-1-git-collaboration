# Git Collaboration Reflection

## Where does your code live?

**Describe (or sketch and include an image of) where your changes exist after each step: after you save the file, after `git add`, after `git commit`, after `git push`, and after your partner runs `git pull`. At which point can your partner see your work?**

Our code lives first locally on our machines. When you do `git add` we save the file its in a staging phase and when you do commit it puts it in a local repository with a brief message. When you do `git push` it uploads it on to a remote repository like github or any other website with git then when my partner does a `git pull` it downloads the changes on to the local machine so they can edit and see my work.

---

## Your predictions vs. reality

**In Round 1, step 5, you each predicted what would happen when Partner B pushed. What did each of you predict, and what actually happened? Using what you know now, explain why git rejected the push. Then explain what `git pull` did that the push couldn't.**

We predicted that what cna happen is when we push it would go to the remote repository on github and the changes will sync. What happened was we had a merge conflict since you both parters have edited the same line and github does not know which one is the correct version

---

## Resolving a conflict

**Pick one of the two conflicts you resolved (Round 1 or Round 2). How did you and your partner decide what to keep? How did you confirm the resolution was correct before pushing?**

When resolving a conflic me and mmy partner decided on which code is the one we want to keep by comparing and looking at whichh one fits better. We confirmed the resolution was correct by running te code and seeing if there are any errors that come up.

---

## Getting unstuck

**Describe one moment when something didn't work or didn't match what you expected, in the warm-up or while writing the story. What was the exact message or result? What did you check first (for example `git status` or `git remote -v`), and what fixed it?**

We had a moment where we accidentally created a new branch, we tried chaning branches multiple times but could not get it to work, so we started from scratch reading the directions more carefully

---

## Commit messages for a team

**Look at your commit history on GitHub. Pick the most useful commit message and the least useful one, and rewrite the weak one here (you don't need to change the message on GitHub). Then explain: if five people were working in this repo instead of two, why would clear commit messages and pulling before you start matter even more?**

The most useful commit is `"resolving merge conflict"` because it tells what we did exactly, the weakest one is probaby multiple times where we commited `"new storyline"` because it does not say much to someone whos just opened up the code. If five people woring instead of 2 clear commit messages and pulling before you start would matter more because it helps other know what youre up to and lets you have the most u to date code so that you dont accidentally create a merge conflict.