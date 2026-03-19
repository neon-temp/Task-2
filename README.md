# Task-2
## Explain version control
### Answer
 Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

## Explain difference between git and github
### Answer
Git is a version control system that runs in the command line, helping you track changes in your code. At its core, Git lets developers save versions of their code (known as “commits”), experiment with new features in branches, and merge those changes back into the main project. GitHub, on the other hand, takes Git to the next level by adding collaboration, automation, and accessibility through a web-based platform. GitHub takes Git’s core features — version control and change tracking — and enhances them with an intuitive interface and a range of collaboration tools, providing robust source code management functionality.You can use Git without GitHub, but together, they make teamwork and code management much easier.

## List three other github alternatives
### Answer
1. Launchpad
2. GitLab
3. Codeberg

## Explain the difference between git fetch and git pull
### Answer
 Git fetch downloads the changes from the remote repository to the local repository but does not make any changes to the current working directory. Since the changes are not merged into the local branch, you can check the changes from the remote repository without interrupting your current work. On the other hand, git pull retrieves the latest changes from the remote repository like git fetch, but it also automatically merges those changes into the current branch. In contrast to git fetch, git pull directly applies the changes from the remote repository to the local working directory.

 ## Explain in simple terms git rebase and the command for it
 ### Answer
 git rebase is a command that integrates changes from one Git branch into another by moving, or "replaying", your current branch's commits on top of the target branch's latest commit.In simple terms, imagine you have a main branch and a feature branch that diverged from main a while ago. Since then, new commits have been added to main. When you run git rebase main while on your feature branch: 
1. Git temporarily moves the commits you made on your feature branch to a holding area.
2. Your feature branch is updated to the very tip of the main branch.
3. Git reapplies your saved commits one by one on top of the latest main commit.
4. The final result is that your feature branch appears as if it branched off the most recent version of main from the start, with a linear history.

* The command for it is: git rebase main

 ## Explain in simple terms git cherry-pick and the command for it
 ### Answer
 Git cherry-pick is a command that allows you to take a specific commit from one branch and apply it onto your current branch.In simple terms, imagine you have a feature-branch where you made three commits, but you only want the second commit (a bug fix) to go into the main branch immediately. You don't want the unfinished features from the first and third commits. You use cherry-pick to grab just that bug fix commit and apply it to main.

 * The command for it is: git cherry-pick COMMIT_HASH
