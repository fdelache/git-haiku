# git-haiku
Poems for your git history

# Dependencies
git-haiku relies on the wonderful work made by [Teddy Katz](https://blog.teddykatz.com/) in [`lucky_commit`](https://github.com/not-an-aardvark/lucky-commit).

To install `lucky_commit` follow [the instructions](https://github.com/not-an-aardvark/lucky-commit#installation).
Or run `cargo install lucky_commit --locked`

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
