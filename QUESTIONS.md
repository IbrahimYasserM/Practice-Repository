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

> <type>/<short-description> for branch names
 The allowed types are feature, fix, docs, and chore 
 I plan to use docs/add-rawan.

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> The project requires Conventional Commits using the format 
<type>: <short summary> 
<optional longer description>
My planned commit message is docs: add Rawan to contributors list

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> The related issue must be linked to the PR, a description alone isn't enough
---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin  https://github.com/rawan187/Practice-Repository.git (fetch)
origin  https://github.com/rawan187/Practice-Repository.git (push)
upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (fetch
)
upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (push)

origin points to my fork, while upstream points to the original repository
This difference important because I push my changes to origin, while I can fetch or merge changes from the original repository through upstream.

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> 97aebb8 (HEAD -> docs/add-rawan) docs: add Rawan to contributors list
3b30f00 (origin/main, origin/HEAD, main) Clarify task labeling in README
f5ecf54 Revise task assignment instructions in README


---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> Both branches modified the same part of CONTRIBUTORS.md. 
My branch added Rawan Ahmed, while upstream/conflict-practice added Mohammed Nasser in the same location

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> I removed the conflict markers and kept both additions. 
I kept Mohammed Nasser from the upstream branch and Rawan Ahmed from my branch, then placed them in alphabetical order by first name 

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
