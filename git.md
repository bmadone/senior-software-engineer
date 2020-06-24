# Git

### Questions

* Chto takoye Git?
* V chom raznitsa mezhdu Git, GitHub i GitLab?
* Chto predstavlyayut iz sebya 3 oblasti: Working directory, Staging area, Repository?
* Vetki
  * Chto takoye vetka?
  * Zachem nuzhny vetki?
  * Chto znachit "sozdat' vetku" i "udalit' vetku" (chto pri etom proiskhodit)?
  * Kak posmotret' spisok vetok?
  * Kak smenit' vetku?
  * Kak sozdat' vetku?
  * Kak pereimenovat' vetku?
  * Kak udalit' vetku?
* Dlya chego nuzhen fayl `.gitignore`?
* `git config`: chto pozvolyayet delat' i kakiye tri urovnya konfiguratsii yest'?
* Chto delayut, kak i zachem ispol'zovat' komandy:
  * `add`
  * `commit`
    * Kak i pri kakikh usloviyakh mozhno sdelat' kommit, ne napisav pered etim yavno `git add`?
    * Kak napisat' soobshcheniye dlya kommita ne otkryvaya redaktora?
  * `push`
  * `fetch`
  * `merge`
    * Chto takoye fast-forward merge?
    * Chto delayut flagi `--squash` i `--no-ff`?
  * `pull`
* Chto takoye Pull Request (ili Merge Request)?
* Kak posmotret' istoriyu kommitov?
* Rasskazat' pro ob"yektnuyu model' (blob, tree, commit, tag) i .pack fayly.
* Chto takoye "The Three Trees" (The HEAD, The Index, The Working Directory)?
* Kak proizvodit' otmenu izmeneniy? Gde kakoy sposob stoit primenyat'? Rasskazat' v etom kontekste pro komandy:
  * `checkout`
  * `reset`
  * `revert`
    * Kak sdelat' revert merge-kommita?
    * Kak uznat' roditeley merge-kommita?
  * `clean`
  * `rm`
* Kak mozhno izmenit' istoriyu kommitov? Gde kakoy sposob stoit primenyat'? Rasskazat' v etom kontekste pro komandy:
  * `commit` s flagom `--amend`
  * `cherry-pick`
  * `fitler-branch`
  * `rebase`
    * Chto takoye interaktivnyy rezhim rebeyza? Chto on pozvolyayet delat'?
    * Kakiye yest' opasnosti pri ispol'zovanii rebeyza?
  * Chto delayut, kak pol'zovat'sya, i kogda byvayut polezny komandy:
    * `stash`
    * `reflog`
    * `bisect`
* Kak otmenit' merge commit?
* Chto takoye `HEAD` i `detached HEAD`? Chto znachat `HEAD^`, `HEAD~`, `HEAD@{1}`?
* Chto takoye Git flow, kakiye znayete primery?
Show more
1937/5000
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
