# git-armv7

The installation will use either:

* memory card if present, formatted in ext4 and labeled 'docker'
* home/ directory if no memory card found

Update path in user-profile:

```
// For memory card:
PATH="/media/docker/git/libexec/git-core:$PATH"
// For home:
PATH="/home/git/libexec/git-core:$PATH"
```

Configuring example:

```
git config --global user.name "<NAME>"
git config --global user.email "<EMAIL>"
git config --global user.password "<TOKEN>"
git config --global credential.helper cache
it config --global init.defaultBranch <BRANCH>
git config --global init.templateDir "<PATH>/share/git-core/templates"
```

Clone:

```
git clone <REPO>
```
