# Present your work with Git and Rebase

## Exercise 2 - Rebase on main

Scenario:

- You are working on this awesome rolling rick feature.
- Someone else in your team have added a new default font to be used on the `main` branch.
- You are wondering if that affects your work in any way.
- You like to stay ahead and so you decide to rebase your work on top of the latest development on `main` branch.

Instructions for exercise:

- Checkout branch `start`.
- Create a new branch `exercise`.
- Have a look at the commits in `solution` branch.
- Rebase `exercise` branch on top of `main` branch.
- Solve merge conflicts.
- Reword (change commit message) for commit: "Add settings for vscode" to reflect the change better.

Tips:

- [Rebase](https://git-scm.com/docs/git-rebase) the `exercise` branch.
- Think of solving merge conflicts as: "how would I have written my code if I already knew about the changes to main branch".
- If you get stuck while rebasing, you can always [abort](https://git-scm.com/docs/git-rebase#Documentation/git-rebase.txt---abort) and try again.
- Use a GUI client such as [GitExtensions](http://gitextensions.github.io/) (Win), [Fork](https://git-fork.com/) (Mac + Win) or [GitKraken](https://www.gitkraken.com/) (Linux, Mac, Win) so that you don't have to figure out the git cli commands for doing the above.
- I've written a bit about rebasing and solving merge conflicts using GitExtensions on [my blog](https://blomholm.no/posts/how-i-git-it-syncing/#pull-in-new-commits-from-another-branch)

[Click here for next exercise](https://github.com/tbkvamme/git-ws-3)
