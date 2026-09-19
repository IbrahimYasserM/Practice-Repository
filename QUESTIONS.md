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

> docs/add-Wafaa-Atef.

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> docs: add wafaa atef to contributors list.

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> yes expects
---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> PS D:\Docs\OSS\First task\Practice-Repository> git remote -v
>origin  https://github.com/WafaaAtef/Practice-Repository.git (fetch)
>origin  https://github.com/WafaaAtef/Practice-Repository.git (push)
>upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
>upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (push) 
>origin >forked , upstream>original  
---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> 140249f (HEAD -> docs/add-Wafaa-Atef) docs: conflict resolved
e391163 docs: add wafaa atef to contributors list
983499c (upstream/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md
:...skipping...
140249f (HEAD -> docs/add-Wafaa-Atef) docs: conflict resolved
e391163 docs: add wafaa atef to contributors list
983499c (upstream/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md
~
~
~
~
~
(END)...skipping...
140249f (HEAD -> docs/add-Wafaa-Atef) docs: conflict resolved
e391163 docs: add wafaa atef to contributors list
983499c (upstream/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md
~
~
~
~
~
~
~
(END)

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> Adding Mohammed nasser data at the same line of my data ,
>file : CONTRIBUTORS.md  , line : 12

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> combined , making alist 

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> link : gh pr checkout 26
> files changed : 2 files , commits :4 commits
---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> dealing with upstram.

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> a fork is a copy from original repo ,clone is fetching the local repo from github
>origin the remote repo from your forked version ,upstream the remote repo from original version 
