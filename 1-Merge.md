# Q&A

## 1. [Git refusing to merge unrelated histories](https://stackoverflow.com/questions/37937984/git-refusing-to-merge-unrelated-histories)

You can use `--allow-unrelated-histories` to force the merge to happen.

### 2. [What does “Changes not staged for commit” mean](https://stackoverflow.com/questions/21134960/what-does-changes-not-staged-for-commit-mean)

You have to use `git add` to stage them, or they won't commit. Take it that it informs git which are the changes you want to commit.

`git add -u :/` adds **all modified file changes** to the stage`git add * :/` adds modified and any new files (that's not gitignore'ed) to the stage.

