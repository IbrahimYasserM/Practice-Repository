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

> It uses type/description convention. 'docs/add-my-name' is the name I used.

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> The format is 'type:short-description', the one I used is 'docs: add name to contributors list'.

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> Yes, the issue will be linked and mentioned in the PR. the PR template states so.

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin	https://github.com/daliamirghani/Practice-Repository.git (fetch)
origin		https://github.com/daliamirghani/Practice-Repository.git (push)
upstream	https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
upstream	https://github.com/IbrahimYasserM/Practice-Repository.git (push)

The fork on my personal account is the origin, the orignal repo is the upstream. 
The distinction matters because when I want to fetch changes from the original repo I pull from upstream, 
and when I want to push my own changes I push to origin.
---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> d5fad11 docs: add name to contributors list
Yes, it does.

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**
> The conflict happened because when I tried to merge the branches. The same single line was changed in both of them.
The file was CONTRIBUTERS.md and the line where I added my name and username was involved.

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> I resolved it by editing the file and combining my change with the change in the branch I was merging. 
I kept both because the information was different and not redundant.

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> https://github.com/IbrahimYasserM/Practice-Repository/pull/10
The commit currently has 3 commits. A Single file has been changed.

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> Nothing, all is good.

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> -  forking is making a fully personal copy (both remote and local) of an existing repository that isn't yours.
- cloning is making a local only copy of an existing repository that may be yours or not yours.
- origin is the remote URL from which the project is cloned.
- upstream refers to the original repository from which a fork happened, usually you have read-only access to it.
