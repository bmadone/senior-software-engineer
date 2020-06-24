# Git

### Questions

* What is git?
* What is the difference between Git, GitHub and GitLab?
* What are 3 areas: Working directory, Staging area, Repository?
* Branches
  * What is a branch?
  * Why do we need branches?
  * What does it mean to create a branch and delete a branch (what happens)?
  * How to view the list of branches?
  * How to change a branch?
  * How to create a branch?
  * How to rename a branch?
  * How to delete a branch?
* What is the `.gitignore` file for?
* `git config`: what allows you to do and what are the three configuration levels?
* What they do, how and why to use the commands:
  * `add`
  * `commit`
    * How and under what conditions can a commit be made without explicitly writing `git add` before it?
    * How to write a message for a commit without opening an editor?
  * `push`
  * `fetch`
  * `merge`
    * What is fast-forward merge?
    * What do the `--squash` and` --no-ff` flags do?
  * `pull`
* What is a Pull Request (or Merge Request)?
* How to see the history of commits?
* Talk about the object model (blob, tree, commit, tag) and .pack files.
* What is "The Three Trees" (The HEAD, The Index, The Working Directory)?
* How to undo changes? Where is which method worth applying? Tell in this context about the commands:
  * `checkout`
  * `reset`
  * `revert`
    * How to reverse merge commit?
    * How to find out the parents of a merge commit?
  * `clean`
  * `rm`
* How can I change the history of commits? Where is which method worth applying? Tell in this context about the commands:
  * `commit` with the flag` --amend`
  * `cherry-pick`
  * `fitler-branch`
  * `rebase`
    * What is an interactive rebase mode? What does he allow to do?
    * What are the dangers when using rebase?
  * What they do, how to use, and when commands are useful:
    * `stash`
    * `reflog`
    * `bisect`
* How to cancel a merge commit?
* What are `HEAD` and` detached HEAD`? What do `HEAD ^`, `HEAD ~`, `HEAD @ {1}` mean?
* What is Git flow, what examples do you know?


### Links
* [Atlassian Git Tutorial](https://www.atlassian.com/git)
* [Скринкаст по Git](https://learn.javascript.ru/screencast/git#intro-starting-video)
* [Understanding Git — Data Model](https://hackernoon.com/https-medium-com-zspajich-understanding-git-data-model-95eb16cc99f5)
* [Хорошие материалы по Git от Atlassian](https://www.atlassian.com/git)
* [Git from the Bottom Up](https://jwiegley.github.io/git-from-the-bottom-up/)
* [Demystifying Git internals](https://medium.com/@pawan_rawal/demystifying-git-internals-a004f0425a70)
* [HEAD~ vs HEAD^ vs HEAD@{}](https://stackoverflow.com/questions/26785118/head-vs-head-vs-head-also-known-as-tilde-vs-caret-vs-at-sign/26785200)
* [Useful tricks you might not know about Git stash](https://medium.freecodecamp.org/useful-tricks-you-might-not-know-about-git-stash-e8a9490f0a1a)
* [Introduction to GitLab Flow](https://docs.gitlab.com/ee/workflow/gitlab_flow.html)
* [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
