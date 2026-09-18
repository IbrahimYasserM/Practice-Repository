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
docs/add-my-name

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> Your answer here.
docs: add my name to contributors list

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> Your answer here.
The project expects the related issue to be linked in the PR description.

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> Your answer here.
origin   https://github.com/SarahFCIS2028/Git-Practice-Repository.git (fetch)
origin   https://github.com/SarahFCIS2028/Git-Practice-Repository.git (push)
upstream https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
upstream https://github.com/IbrahimYasserM/Practice-Repository.git(push)

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> Your answer here.
1ce8d67 (HEAD -> docs/add-my-name) docs: add my name to contributors list
3b30f00 (upstream/main, origin/main, origin/HEAD, main) Clarify task labeling in README
f5ecf54 Revise task assignment instructions in README

Yes,My commit message docs: add my name to contributors list follows the Conventional Commits format required by the project.
---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> Your answer here.
The conflict was caused because both branches added a contributor in the same location in CONTRIBUTORS.md. The conflicting lines were the contributor entries for Sarah Ahmed and Mohammed Nasser.

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> Your answer here.
I kept both contributor entries and removed the Git conflict markers. I kept both because both contributors should remain in the CONTRIBUTORS.md file.
---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> Your answer here.
https://github.com/IbrahimYasserM/Practice-Repository/pull/16#issue-5501107841

There are 4 commits and 3 files changed

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> Your answer here.
I was most confused by branches and especially upstream, and how they are connected to my fork and local repository.

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> Your answer here.
Fork is my copy of the original repo, clone is the copy on my computer, origin points to my fork, and upstream points to the original repo.
