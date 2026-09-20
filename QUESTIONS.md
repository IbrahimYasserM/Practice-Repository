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

> it is <type> then description like docs/add-my-name

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> <type>:description docs: add name to contributors list

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> yes description is not enough

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin	git@github.com:Marwa-221b/Practice-Repository.git (fetch)
origin	git@github.com:Marwa-221b/Practice-Repository.git (push)
upstream	git@github.com:IbrahimYasserM/Practice-Repository.git (fetch)
upstream	git@github.com:IbrahimYasserM/Practice-Repository.git (push)

origin is my fork and upstream is original repo

the differnece is i will push my work to origin and pull any updates from original (upstream)

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> 01e5a51 (HEAD -> docs/add-my-name) Merge remote-tracking branch 'upstream/conflict-practice' into docs/add-my-name
6c68156 (origin/docs/add-my-name) docs: add name to contributors list
983499c (upstream/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md

yes it follows it excepting merge one :) 
---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> CONTRIBUTORS File and the line that me and nasser edit in .

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> i keep both updates , remove conflicts marks and combining the names to follow alphaptic format and why because we want keep both updates 
---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> https://github.com/IbrahimYasserM/Practice-Repository/pull/18

The PR shows 4 commits and 2 files changed.
---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> merge conflict.

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> fork is taking a copy of repo in my github
   clone is making this project locally in the device
   origin is the repo that i can push to it after fork
   upstream is the original repo that i made fork from it
