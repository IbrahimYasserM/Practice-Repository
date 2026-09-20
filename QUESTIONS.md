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

> <type>/<short-description>   , I used `docs/add-mahmoud-to-contributors'

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

>  `<type>: <short summary>`. I used `docs: add Mahmoud Ebrahim to contributors list`.
**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> CONTRIBUTING.md says to "link the related task/issue in your PR description," so a linked issue is expected — a PR description alone without that link wouldn't be enough.

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**


> origin    https://github.com/Eng-Mahmoud-Ebrahim/Practice-Repository (fetch)
> origin    https://github.com/Eng-Mahmoud-Ebrahim/Practice-Repository (push)
> upstream  https://github.com/IbrahimYasserM/Practice-Repository (fetch)
> upstream  https://github.com/IbrahimYasserM/Practice-Repository (push)

> `origin` points to my fork, and `upstream` points to the original repo. The distinction matters because I can only push to `origin` — I don't have write access to `upstream`. `upstream` is used to pull in changes from the original repo, like the `conflict-practice` branch I merged from to complete this task.

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**


> 8b02353 (HEAD -> docs/add-mahmoud-to-contributors) Merge remote-tracking branch 'upstream/conflict-practice' into docs/add-mahmoud-to-contributors
> 791557b docs: add Mahmoud Ebrahim to contributors list
> 983499c (upstream/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md
> ```
> My own commit (`791557b`) follows the Conventional Commits format from CONTRIBUTING.md exactly (`docs: add Mahmoud Ebrahim to contributors list`). 
---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

>> The conflict happened in `CONTRIBUTORS.md`. Both my branch and `upstream/conflict-practice` added a new line in the same location   my branch added "Mahmoud Ebrahim", and `conflict-practice` added "Mohammed Nasser" at the exact same spot, so Git couldn't automatically decide which line should come first.

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> I opened the file, found the `<<<<<<<`, `=======`, `>>>>>>>` markers, and removed them. 

I kept both entries instead of discarding one, and reordered them alphabetically by first name as the file's instructions required — Ibrahim, then Mahmoud, then Mohammed. I 

also fixed my own line's formatting added the missing `- ` prefix and used the same `—` separator as the existing entries before staging and committing.

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> My PR: https://github.com/IbrahimYasserM/Practice-Repository/pull/28
> It shows 3 commits and 1 file changed (CONTRIBUTORS.md).

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> that the git redused my password and make me to get token

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> **Fork**: A personal copy of someone else's repository under your own GitHub account, so you can make changes without needing write access to the original.
> **Clone**: Downloading a copy of a repository (usually your fork) from GitHub onto your local machine so you can work on it.
> **Origin**: The default name Git gives to the remote you cloned from — in this case, my fork.
> **Upstream**: A remote you add manually to point to the original repository, used to pull in updates from it (I don't have push access to upstream, only fetch/pull).
