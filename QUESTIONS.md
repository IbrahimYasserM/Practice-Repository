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

<type>/<short-description>
docs/add-name-to-contributors

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

<type>: <short summary>
docs: add name to contributors md file

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

yes, it is listed under the 'Opening a Pull Request' section in the CONTRIBUTING.md file that a link to the issue is required

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

origin  https://github.com/FaresALaaKN/Practice-Repository (fetch)

origin  https://github.com/FaresALaaKN/Practice-Repository (push)

upstream        https://github.com/IbrahimYasserM/Practice-Repository (fetch)

upstream        https://github.com/IbrahimYasserM/Practice-Repository (push)
origin is the fork and upstream is the original repo, 
this distinction prevents pushing to the original repo
---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

37972a9 (HEAD -> docs/add-name-to-contributors, main) docs: add name to CONTRIBUTORS.md file

3b30f00 (origin/main, origin/HEAD) Clarify task labeling in README

f5ecf54 Revise task assignment instructions in README
---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

The conflict happened because upstream/conflict-practice modified the same lines in CONTRIBUTORS.md

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

It was fixed by manually editing the file to keep both names cleanly formatted without the conflict markers, then staging and committing

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

link: https://github.com/IbrahimYasserM/Practice-Repository/pull/9
files changed: 1
commits: 3
---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

resolving and handling the merge conflict seemed difficult at first but after seeing how git layered the markers it became much easier to handle

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

Fork: A server side copy of a repo under your own personal github account
Clone: A copy of a repo downloaded from github onto your computer locally
Origin: The default remote name pointing to your fork on github
Upstream: The remote name pointing back to the original repo you forked from
