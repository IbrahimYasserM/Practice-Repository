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

> Your answer here.
it uses type/description convention, example: docs/my-contributer-name

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> Your answer here.
type: description, example: docs: added my name to the list

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> Your answer here.
yes it expects a linked issue or a task to my pr

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> Your answer here.
```
origin  git@github.com:zyad-elkhewekh/Practice-Repository.git (fetch)
origin  git@github.com:zyad-elkhewekh/Practice-Repository.git (push)
upstream        git@github.com:IbrahimYasserM/Practice-Repository.git (fetch)
upstream        git@github.com:IbrahimYasserM/Practice-Repository.git (push)
```
`origin` remote is my forked clone and `upstream` is the original,
the distinction matters to allow me to get other changes from the original (aka other peoples forks' changes from their locals) and keep my changes safe

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> Your answer here.
```
cccde0e (HEAD -> docs/my-contributer-name) docs: added my name to the list
3b30f00 (origin/main, origin/HEAD, main) Clarify task labeling in README
f5ecf54 Revise task assignment instructions in README
```
yes they do follow

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> Your answer here.
CONTRIBUTORS.md caused the conflict due to a name being inserted at the end where i originally inserted mine

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> Your answer here.
all i had to do was keep both new names (Mohammed Nasser and me) and remove gits warning text
techincally a combine not keep

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> Your answer here.
[the link](https://github.com/IbrahimYasserM/Practice-Repository/pull/2)
7 commits (i forgot to add the meeting minutes, and account for two extra commits of editing lol)
3 files changed (QUESTIONS.md, CONTRIBUTORS.md, and meeting-minutes.md)
note that its about to change since pr template was changed and this should be the 5th commit now

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> Your answer here.
being forced to link the original repo beside my fork :) im not used to doing it but i realise how much easier it would have made my life.

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> Your answer here.
`fork` is a remote copy of some repo but linked to my account, meaning im the owner and have push access to this copy.
`clone` is *local* copy of some repo, it can be a repo i own, some fork of another repo, or another repo altogether.
`origin` is the default name for a remote to a local repo i have and own.
while `upstream` is a usual naming convention for a remote to a repo that idont own, i may have forked it but i need to fetch changes from the original to ensure clean working.
