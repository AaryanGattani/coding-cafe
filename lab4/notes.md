# Coding Café - Lab 4
## Git and Github


### Q1. What did `--global` mean here? What would happen if you left it out?

`--global` tells Git to apply the configuration setting system-wide across all repositories on user profile rather than just the current directory. If we left it out, the setting would only apply to the current repository.

### Q2. What appeared in `ls -a` but not in `ls`? What is inside it?

The hidden `.git` directory appeared in `ls -a`. 

### Q3. Roughly how many files and folders is Git offering to track? Does anything in that list look like something you did *not* write?

Git offers to track hundreds of files and folders. Files inside `.venv/` and cache directories like `__pycache__/` are something that I did not write.

### Q4. Compare this `git status` with the one from Question 3. What disappeared?

After creating `.gitignore`, all the files and folders inside `.venv/` and `__pycache__/` disappeared from the list of untracked files.

### Q5. `.gitignore` itself shows up as untracked. Should it be committed, or ignored too? Why?

`.gitignore` should be committed. It needs to be tracked by Git so that collaborators (and TAs) download the same exclusion rules and avoid committing unwanted system files on their own machines.

### Q6. `README.md` moved from one heading to another in the `git status` output. Which two? In the three-places model from the session, what just happened to it?

`README.md` moved from "Changes not staged for commit" (or untracked files) to "Changes to be committed" (staged). In the three-places model, it moved from the working directory into the staging area.

### Q7. What did Git print after the commit? How many files did it say changed?

Git printed a commit summary showing the branch name, the unique commit hash, the commit message, and statistics indicating how many files changed and how many insertions/deletions occurred.

### Q8. What are the first seven characters of your commit called, and what are they for?

They are short identifiers for a specific commit.

### Q9. You now have two commits. Without looking it up: what are the four steps of the loop you just did twice?

The four steps are: Creating files, checking status, adding files, and commiting them.

### Q10. Why does this file get a special name and a special place, rather than being called `notes.md` like everything else?

`README.md` gets a special name and placement because hosting platforms like GitHub automatically look for it in the directory to use it as the primary description page for visitors.

### Q11. What did `gh auth login` do that means you will not be asked for a password when you push?

`gh auth login` authenticates my terminal with my GitHub using an Auth code, allowing Git to authenticate pushes without prompting for a password.

### Q12. Refresh the repository page on GitHub. What is showing on the front page, and why that file?

The contents of `README.md` appear on the front page because GitHub usually takes it as an overview of the repository.

### Q13. Run `git log --oneline` again. Did pushing change your local history in any way?

No, pushing simply uploaded a copy of my local commits to the remote repository on GitHub, it did not alter my local commit history or hashes in any way.

### Q14. Your repository is private but your TAs can now read it. In your own words, what is the difference between a repository being private and a repository not existing on GitHub at all?

 A private repository is only for me or invited users, whereas a non-existent repository means nothing of that repo exists on GitHub at all.