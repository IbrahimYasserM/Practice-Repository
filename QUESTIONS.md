# Reflection Questions

Answer these as you go — don't wait until the end. Some answers only exist
*after* you've done a step, so fill this in progressively.

Your answers will be reviewed alongside your code. Generic or copy-pasted
answers (that don't reference your actual output) will be sent back for
revision.

---

## Part 1 — Before touching anything (after reading CONTRIBUTING.md)

**1. What branch naming convention does this project use? Give an example
branch name you plan to use.**

> fix/fix-an-error

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> fix: fix the login error in the window

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> In this project I dont think, pr description is enough  
---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin	https://github.com/Jury1357/Practice-Repository.git (fetch)
origin	https://github.com/Jury1357/Practice-Repository.git (push)
upstream	https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
upstream	https://github.com/IbrahimYasserM/Practice-Repository.git (push)


the first 2 lines (origin) are related to my repo when I push or make any changes they appear in 
my repo the origin while the upstream is linked to the original repo I forked,so when I want to 
fetch the changes done in the original repo or what to make pr I have to link my repo to the upstream

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> bfee671 (HEAD -> fix/fix-merge-conflict) fix: fixed the name conflict in CONTRIBUTORS.md
23bf238 docs: added my name and a fun fact to CONTRIBUTORS.md
983499c (upstream/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md


---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> there was 2 different content for the same line (line 12)

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> I removed the names of the branches and the >>>>> signs and then put the contributors names in an alphabetical order

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> 5 commits and 2 files changed
https://github.com/IbrahimYasserM/Practice-Repository/pull/30
---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> nothing

**10. If a teammate asked you to explain the difference between fork, clone, origin, and upstream in one or two sentences each, what would you say?**

> fork means I am copying someones repo and working with the copy(I can later make a pr and link both repos)
clone means I downloaded this repo and I willfork means I am copying someones repo and working with the copy(I can later make a pr and link both repos)
clone means I downloaded this repo and I will work on it when I push I will push on it not a copy
origin mean my repo the one I am working with,which I cloned from, like in the fork my repo is my origin
while upstream means the repo I forked from
