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

>
```
<type>/<short-description>
```
Example:
```
docs/add-my-name-Mariam
```

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> 
```
<type>: <short summary>

<optional longer description>
```

Example:
```
docs: add my name(Mariam) to contributors list
```

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> it needs a linked issue.

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin points to my personal fork, while
upstream is the repo that i forked from. The distinction matters because this setup protects the main setup from my work.it seperates where i get the updates from my workspace.
```
git remote -v
    origin  https://github.com/mariam1617/Practice-Repository.git (fetch)
    origin  https://github.com/mariam1617/Practice-Repository.git (push)
    upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
    upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (push)
```

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> yes
```
b74c706 (HEAD -> docs/add-my-name-Mariam) docs: fixed merge conflict with mohammed nasser name on CONTRIBUTRS.md
a9f7a99 docs: add my name to contributors list
983499c (upstream/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md
```

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> there was an added line in the same place by two different contributors in the CONTRIBUTOR.md

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> both additions seemed valid, so i accepted both.

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> Your answer here.

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> Your answer here.

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> Your answer here.
