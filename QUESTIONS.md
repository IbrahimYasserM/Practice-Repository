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

> this project use <type>:<short-description> pattern 
> feature/logs 

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> <type>:<short-summary>
> feature:adding logs manipulation

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> yes this project expect a linked issue

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin  https://github.com/mohmedbakr1911/Practice-Repository.git (fetch)
> origin  https://github.com/mohmedbakr1911/Practice-Repository.git (push)
> upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
> upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (push)

> origin is my forked repo and upstream is the original repo 
>this distinction matter because it help me as a contributor to keep updated with the original repo 
---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> 92a64cc (HEAD -> feature/logs, origin/feature/logs) docs:answering questions ending with part3
> db776db fix contributers task
> 8df8f17 contributors task

> only the last commit following the convention form.

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> the conflict happend because there is 2 changes at the same line from two different contributers line 12 file "contributers.md".

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> i resolved it by accepting both changes i combined the two changes together and didn't remove any of them

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> https://github.com/IbrahimYasserM/Practice-Repository/compare/main...mohmedbakr1911:Practice-Repository:feature/logs?expand=1

> 2 changed files and 6 commits

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> the flow is not that complix as i imagened but what confused me was the clear understanding of what i supposed to to do 

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> fork -> the fork is a copy of a repo at a specific moment abling you to clone it at your local machine and start contributing 

> clone -> downloading the project at our local machine 

> origin -> the original repo (our forked repository)

> upstream -> a variable for the remote repo set as the base repo
