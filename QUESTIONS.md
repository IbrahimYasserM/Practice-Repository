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

Uses <type>/<short-description>. I plan to use docs/add-contributor-info.

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

Follows Conventional Commits format (<type>: <short summary>). I plan to use docs: add name to contributors list.

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

It expects a linked issue referenced in the PR description along with a completed PR template.
---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

origin  https://github.com/hisham811/Practice-Repository.git (fetch)
origin  https://github.com/hisham811/Practice-Repository.git (push)
upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (practice) (fetch)
upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (push)

`origin` points to my personal forked repository where I push my changes, while `upstream` points to the original project repository. This distinction is crucial because it allows me to keep my local repo updated with the main project while pushing new features to my own fork without directly affecting the original codebase.

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

be406f7 docs: add contributor details and reflection answers
3b30f00 Clarify task labeling in README
f5ecf54 Revise task assignment instructions in README

Yes, my commit message strictly follows the Conventional Commits format required by CONTRIBUTING.md using the "docs:" prefix.

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

The conflict occurred in CONTRIBUTORS.md between lines 12 and 16. Both my branch (docs/add-contributor-info) and upstream/conflict-practice added a new line at the exact same location after Ibrahim Yasser.   

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

I resolved it by keeping both additions and placing them on separate lines in alphabetical order, then removed all Git conflict markers to keep the file valid.   

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**

https://github.com/IbrahimYasserM/Practice-Repository/pull/19

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

Nothing, the outputs that comes I expect it

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

-fork is to copy a repo of someone and get it in my account without changing his repo
-clone is to download the repo on my machine to work on it locally
-origin it's the project that I forked on my github account
-UpStream it's the main project on the project maker account
