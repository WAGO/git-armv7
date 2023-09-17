# git-armv7

The installation will use either:

* memory card if present, formatted in ext4 and labeled 'docker'
* home-directory if no memory found

Set git path:

```
export PATH=<PATH>/libexec/git-core:$PATH
```

{% hint style="info" %}
PATH:

SD card = /home/sd

Home = /home
{% endhint %}

Test:

```
:~ git --version
git version 2.42.0
```

Then configure .gitconfig (or use environmet varables) as normal.
