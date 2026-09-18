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

> it's uses <type>/<short-description>, (e.g. feature:add-jumping-power).

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> the required format is <type>: <short summary> <optional longer description>, (e.g docs: add my name and a fun fact).

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> yes this project expect a linked issue before opening a PR

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin	git@github.com:omarahmedZa/Practice-Repository.git (fetch)
> origin	git@github.com:omarahmedZa/Practice-Repository.git (push)
> upstream	git@github.com:IbrahimYasserM/Practice-Repository.git (fetch)
> upstream	git@github.com:IbrahimYasserM/Practice-Repository.git (push)
> - origin: pushes to my fork
> - upstream: syncs original repo changes into my fork

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> cde1548 (HEAD -> docs/add-my-name) fix: solve a conflict
> f5efd79 docs: add my name and a fun fact
> 983499c (origin/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md
> yes, my commit messages follow the convention from `CONTRIBUTING.md`

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> the `CONTRIBUTORS.md` caused the conflict, becase of the line after ibrahim name line
> when i added my name this was in the same line nasser add his line, so this make the conflict

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> i resolve it be keeping my line and nasser line and delete all git conflect lines
> i do this becase nasser add his line for a reason, so i keep it.

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> https://github.com/IbrahimYasserM/Practice-Repository/pull/25
> 4 commits and 3 files

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> I'm forget.

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> fork is a clone on your github account of orginal repo.
> clone is a local clone of any repo on your local desk.
> origin is the main repo you  push changes to it.
> upstream is the original repo you forked that you pull updates from it. 
