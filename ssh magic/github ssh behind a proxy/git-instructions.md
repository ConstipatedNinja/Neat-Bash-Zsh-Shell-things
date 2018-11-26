If you want to do this to your global config, add the `--global` flag. Otherwise, run these commands while in the specific repo you wish to set these for.

```
git config user.name="GITHUB.COM USERNAME"
git config user.email="GITHUB.COM USER EMAIL ADDRESS"
git remote set-url origin git@github.com:USERNAME/YOUR-REPO-NAME.git
```

You only need to run the last command if you haven't already set the origin to the ssh-form URL.
