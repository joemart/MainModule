# MainModule
This is a repository to practice "git submodule".

Reference : https://www.activestate.com/blog/getting-git-submodule-track-branch/

git fork <forked-repository>
git clone <forked-repository>
git submodule add <forked-repository>

When you change branches and you don't see your submodule:

git submodule update --init (to open for the first time)
git submodule update --remote (to open the following times or without --remote)
