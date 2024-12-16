# Suckles' Simple Terminal Fork

[st website](https://st.suckless.org/)

[st repo](https://git.suckless.org/st)

[how to sync your fork with the original git repo](https://www.freecodecamp.org/news/how-to-sync-your-fork-with-the-original-git-repository/)

```sh
# setup repo
git clone https://github.com/alvaronaschez/st
git remote add upstream https://git.suckless.org/st

# sync fork
git fetch upstream
git checkout master
git merge upstream/master
```

