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

> "  type / short-description"
> Where `<type>` is one of: `feature`, `fix`, `docs`, `chore`.
> e.g. docs/add-yomna


**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> "type>: short summary"

> "optional longer description"
> e.g. docs: add name to contributors list

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> The project expects a related task/issue to be linked in the PR description.

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin  https://github.com/YOMNA-MAHSOOB/Practice-Repository (fetch)
> origin  https://github.com/YOMNA-MAHSOOB/Practice-Repository (push)
> upstream        https://github.com/IbrahimYasserM/Practice-Repository (fetch)
> upstream        https://github.com/IbrahimYasserM/Practice-Repository (push)

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> 2a98d01 (HEAD -> docs/add-yomna, origin/docs/add-yomna) docs: add name to contributors list
> 3b30f00 (upstream/main, origin/main, origin/HEAD, main) Clarify task labeling in README
> f5ecf54 Revise task assignment instructions in README
>  Yes. My commit message follows the Conventional Commits format and uses the `docs` type

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> The conflict was caused by both my branch and upstream/conflict-practice modifying the same part of CONTRIBUTORS.md. The conflict involved the lines where the contributors were being added.

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> I removed the <<<<<<<, =======, and >>>>>>> conflict markers

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> [Your answer here.](https://github.com/IbrahimYasserM/Practice-Repository/pull/4)

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> contributions.md , questions.md

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> fork: A fork is my own copy of a GitHub repository on my GitHub account.

> clone: A clone is a local copy of a repository on my computer that I can work on.

> origin: origin is the remote repository my local project is connected to, which in this workflow is my fork.

> upstream: upstream is the remote pointing to the original repository, which allows me to fetch updates and branches from it.
