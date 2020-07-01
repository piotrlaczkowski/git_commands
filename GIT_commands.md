
Taken from:
https://dev.to/g_abud/advanced-git-reference-1o9j


## Logging (What did I just do?)

```python
git log
git log --oneline # more succinct output
git log --graph # with a visual graph of branches
```
#### View your "undo" history

```
git reflog
```
Because sometimes git log doesn't cut it, especially for commands that don't show up in your commit history.
reflog is basically your safety net after running "scary" commands like git rebase. 
You'll be able to see not only the commits you made, but each of the actions that led you there.
