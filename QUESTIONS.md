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

> <type>/<word1>-<word2>-<word3>-....etc
Example : feature/adding-payment-feature

**2. What commit message format is required? Write the exact commit message
you plan to use for your change.**

> <type>: <small message>
example : fix: unvalid card bug is fixed

**3. Does this project expect a linked issue before opening a PR, or is a PR
description enough?**

> I think it won't happen any issues , maybe there will be a merge conflict if we decided to merge every contributors markdown files because of different names

---

## Part 2 — After forking and cloning

**4. Paste the output of `git remote -v` from your local clone. Which remote
is `origin` and which is `upstream`, and why does that distinction matter?**

> origin  https://github.com/mathew-emad/Practice-Repository.git (fetch)
origin  https://github.com/mathew-emad/Practice-Repository.git (push)
upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (fetch)
upstream        https://github.com/IbrahimYasserM/Practice-Repository.git (push)

>it matters as from upstream we take the required files to edit it and the origin has the final result 

---

## Part 3 — After making your change

**5. Paste the output of `git log --oneline -3`. Do your commit message(s)
follow the convention from `CONTRIBUTING.md`?**

> 9003c74 (HEAD -> docs/adding-my-name) docs : survived the merge conflict
45990e7 docs: adding my name to the markdown file
983499c (upstream/conflict-practice, origin/conflict-practice) Add Mohammed Nasser to CONTRIBUTORS.md
> i think it follows them

---

## Part 4 — After hitting the seeded merge conflict

**6. What caused the conflict? Which file and lines were involved?**

> what caused the conflict is that my branch (docs/adding-my-name) has this line - Matthew Emad - mathew-emad , and the other branch (conflict-practice) has this line - Mohammed Nasser — MohammedNaser28

**7. How did you resolve it — what did you keep, remove, or combine, and why?**

> by keeping the line in my own branch and keeping the line from (conflict-practice) branch , the only thing removed were ==,>>,<< , and the other things that showed in the coflict

---

## Part 5 — After opening your PR

**8. Paste your PR link. How many commits and how many files changed does
your PR show?**
>https://github.com/IbrahimYasserM/Practice-Repository/compare/main...mathew-emad:Practice-Repository:main?expand=1
it shows 4 commits and 2 files changed 

---

## Part 6 — Final reflection

**9. What's one thing about this workflow that surprised you, confused you,
or felt different from what you expected going in?**

>beacause i didn't implement enough i was stuck trying to merge the two branches to cause the conflict only to realise that i didn't pull the needed branch from upstream

**10. If a teammate asked you to explain the difference between `fork`,
`clone`, `origin`, and `upstream` in one or two sentences each, what would
you say?**

>fork is taking a copy of someone's repostiory into your own repository to change and make a request to merge the new features.
clone is cloning someone's repository into your own device
origin is the default naming for a remote and is the remote name used when you clone a reopsitory.
upstream is a branch from remote reopsitory equivalent to your local branch in the device , it is required to have an upstream branch when you have changes in the local repository branch.
