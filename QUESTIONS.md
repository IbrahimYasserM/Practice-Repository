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

><type>/<short-description>
> example : docs/ add-my-name

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

><type>: <short summary>
>"fix : fixed merge conflict"

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

>yes it expects to link the task issue

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

output:
>origin  https://github.com/yasserabdelwahab08-sketch/Practice-Repository.git (fetch)
>origin  https://github.com/yasserabdelwahab08-sketch/Practice-Repository.git (push)
>upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
>upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (push)

>my repo is the origin while Ibrahim's is the upstream.
>the upstream is the repo from which you forked.

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

>06fe8ac (HEAD -> docs/add-my-name, origin/docs/add-my-name) fix/fixed the merge conflict
>f5be6a2 docs/added my name
>983499c (upstream/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

>the conflict was caused by a branch in the upstream repo it added mohmed nasser but the main does not contain it

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

>I kept both changes.

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

>(https://github.com/yasserabdelwahab08-sketch/Practice-Repository)
> 2 files changed ( contributors.md and questions.md)
---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

>The merge conflict.


**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**
> cloning is copying the repo on your local machine, while forking is creating a new life version of the upstream repo
>the origin is the repo of my fork while upstream is the original repo.
