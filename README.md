# git-armv7

The installation will use either:

* memory card if present, formatted in ext4 and labeled 'docker'
* home-directory if no memory found

Set git path:

```
// For memory card:
export PATH=/media/docker/git/libexec/git-core:$PATH
// For home:
export PATH=/home/git/libexec/git-core:$PATH
```

Check:

```
:~ git --version
git version 2.42.0
```

Configure:

```
git config --global user.name "<NAME>"
git config --global user.email "<EMAIL>"
git config --global user.password "<PASSWORD/TOKEN>"
```
