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
<type>/<short-describtion>
ex: fix/security-bug

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> Your answer here.
<type>: <short summary>
docs: add my name to contributors list

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> Your answer here.
This project expects a linked issue.

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> Your answer here.
origin	https://github.com/sayedsamir2/Practice-Repository.git (fetch)
origin	https://github.com/sayedsamir2/Practice-Repository.git (push)
upstream	https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
upstream	https://github.com/IbrahimYasserM/Practice-Repository.git (push)

origin is the remote that points to my fork, this is the one I push my changes to.
upstream is the remote that points to the original repository,i only fetch or pull from it, to keep my fork updated with any changes made there.

The distinction matters because I don't have write access to the original repo,i can't push directly to upstream.
All my changes go through origin, and if I ever need the latest updates from the original project, I pull them from upstream and merge them into my branch.

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> Your answer here.
d9593b1 (HEAD -> docs/add-my-name) docs: add my name to contributors list
3b30f00 (origin/main, origin/HEAD, main) Clarify task labeling in README
f5ecf54 Revise task assignment instructions in README
Yes.
---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> Your answer here.
The conflict was in CONTRIBUTORS.md. Both my branch and the conflict-practice branch added a new line right after the same existing line (Ibrahim Yasser's entry) — my branch added Sayed Samir - sayedsamir2, while conflict-practice added Mohammed Nasser — MohammedNaser28.

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> Your answer here.
I resolved it by keeping both entries rather than discarding either one, since both are legitimate contributions. I removed the conflict markers and manually placed the two names .
---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

> Your answer here.
https://github.com/IbrahimYasserM/Practice-Repository/pull/27
3 commits and 2 files changed.

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

> Your answer here.
Nothing about this workflow really surprised me, since I had already worked with PRs and resolved merge conflicts before.

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

> Your answer here.
Fork: A full copy of someone else's repository created under my own GitHub account, so I can make changes without touching the original.
Clone: Downloading a copy of a repository from GitHub onto my local machine.
Origin: The default name Git gives to the remote pointing to the repository I cloned — in my case, my fork. This is where I push my changes.
Upstream: A remote I added manually that points to the original repository, so I can fetch updates from it even though I don't have write access to it.
