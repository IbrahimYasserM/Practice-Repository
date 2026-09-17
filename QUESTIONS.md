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

> Uses <type>/<short-description> for branch names. For example, I used docs/add-contributor.

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> format is <type>: <short summary>. I used docs: add name to contributors list.

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> The project expects a linked issue before opening a PR.

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin  git@github.com:malakemad466/Practice-Repository.git (fetch)
origin  git@github.com:malakemad466/Practice-Repository.git (push)
upstream  git@github.com:IbrahimYasserM/Practice-Repository.git (fetch)
upstream  git@github.com:IbrahimYasserM/Practice-Repository.git (push).
origin is my fork, while upstream is the original repository
distinction matters because I push my changes to origin and get updates from the original repository through upstream

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> 516342a (HEAD -> docs/add-contributor, origin/docs/add-contributor) Merge remote-tracking branch 'upstream/conflict-practice' into docs/add-contributor
6eb79ff docs: add name to contributors list
983499c (upstream/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md
Yes, my commit message(s) follows the convention  docs: add name to contributors list.

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> The conflict happened because I added my name to CONTRIBUTORS.md, while the other branch added another name in the same part of the file.

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> I kept both names because the task asked me to keep both additions and not discard either side.

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> PR is https://github.com/IbrahimYasserM/Practice-Repository/pull/8
Commits: 7
Files changed: 3

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> I did not expect Git to stop the merge and ask me to resolve the conflict manually.

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> Fork: A copy of the original repository on my GitHub
Clone: A local copy of the repository on my device
Origin: The remote for my fork
Upstream: The remote for the original repository
