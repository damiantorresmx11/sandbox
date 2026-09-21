# git-prune-merged-branches

Delete every local branch already merged into main.

```git
git branch --merged main | grep -v '^\*\|  main$' | xargs -r git branch -d
```
