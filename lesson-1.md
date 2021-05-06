## Lesson 1: Revert Commit

### Scenario
You've commited code you don't want right now but will want to apply later.

### Commands

#### Standard
```
% git revert xxxxxx
```

#### Oh My ZSH
```
% grev xxxxxx
```

### Commits 

#### Before
1. Initial commit
2. Commit 1

#### After
1. Initial commit
2. Commit 1
3. Revert "Commit 1" \
  This reverts commit xxxxxx.