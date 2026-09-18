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

- For this task, I used the branch name docs/addsanaa

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

- docs:addsanaa

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

- Just a PR description — link the task there, no separate issue need المطلوبة؟ اكتبي الـ commit message بالظبط اللي هتستخدميه للتعديل بتاعك
---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone.Deleted the conflict markers, kept both entries side by side. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

- origin  https://github.com/seno200/Practice-Repository.git (fetch)
- origin  https://github.com/seno200/Practice-Repository.git (push)
- upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
- upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (push) 
- origin is my own fork
- upstream is original repo
--

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

- 6969877 (HEAD -> docs/addsanaa, origin/docs/addsanaa) docs: answer  QUESTIONS.md
- f419647 docs: resolve merge conflict in contributors list
- 87ec106 Docs:Add sanaa 
---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**
- The conflict happened in CONTRIBUTORS.md when I merged upstream/conflict-practice into my branch

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

- Deleted the conflict markers, kept both entries side by side.
---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

- https://github.com/IbrahimYasserM/Practice-Repository/pull/17
---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

- when Just i removed <<<<<<</=======/>>>>>>>
**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

- Fork: A copy of someone else's repo under your own GitHub account
- Clone: Downloading a repo  onto your local machine so you can work on it. 
- Origin:  it's where you push your branches.
- Upstream: The remote pointing to the original repo you forked from

