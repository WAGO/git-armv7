# git-armv7

A Git SCM build from source.

## Setup

The installation will use either:

* memory card if present, formatted in ext4 and labeled 'docker'&#x20;
* home-directory if no memory found

Set git path:

```
export PATH=/home/admin/libexec/git-core:$PATH
```

Test:

```
:~ git --version
git version 2.42.0
```

Then configure .gitconfig (or use environmet varables) as normal.
