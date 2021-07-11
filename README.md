# git-haiku
Poems for your git history

# Installation
Copy the `git-haiku` script in your PATH
`sudo cp git-haiku /usr/local/bin/`

# Usage
git-haiku transforms your gribbish git history into beautiful [hexspeak](https://en.wikipedia.org/wiki/Hexspeak) [haikus](https://en.wikipedia.org/wiki/Haiku).

```
❯ git log --oneline --graph --no-decorate
* 16aae09 Add missing dependencies
* f9eff28 Add basic README content
* 856514b Add git-haiku script
* 0000000 Initial commit
```

`git haiku "dadd1e5 de1f1ed ba0bab5" origin/main`

```
❯ git log --oneline --graph --no-decorate
* ba0bab5 Add missing dependencies
* de1f1ed Add basic README content
* dadd1e5 Add git-haiku script
* 0000000 Initial commit
```
