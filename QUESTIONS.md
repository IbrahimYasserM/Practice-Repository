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

<type>/<short-description> , example: <docs/add-my-name>

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

<type>: <short summary> , example: <docs: add my name>

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

yes it expect an issue.

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**
              
origin  https://github.com/Sondoskhalid2005/Practice-Repository (fetch)
origin  https://github.com/Sondoskhalid2005/Practice-Repository (push)
upstream        https://github.com/IbrahimYasserM/Practice-Repository (fetch)
upstream        https://github.com/IbrahimYasserM/Practice-Repository (push)
, origin remote is my forked repo and upstream remote is the main central repo have been forked , it matter beause it tells the forked repo and the main repo.

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

44df075 (HEAD -> docs/add-my-name) fix:Merge 'upstream/conflict-practice' into docs/add-my-name
09860a0 doc:added my name
75e97e6 (main) docs: add name to contributors list
---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

the conflict happened because 2 lines had 2 different content , CONTRIBUTORS.md line: 12

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

i solved by combining them, because its another developer work and it had no logic conflicts to choose one of them
---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

https://github.com/IbrahimYasserM/Practice-Repository/pull/12
8 commits & 2 files changed.
---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

no i just made the pr for main branch at first, but then i made for the new branch and closed the previous pr .

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

fork is a copy of a repo into my account , clone is bringing a repo localy in my device , origin is the remote repo i cloned ,upstream is the central repo i forked .
