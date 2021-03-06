# Contributing

**git-extra-commands** is a collection of helper scripts for git and links to git-related articles.

## Contribution Guidelines

- **To add a helper script:** Submit a pull request. Please use `#!/usr/bin/env interpreter` instead of a direct path to the interpreter, this makes it easier for people to use more recent versions when the ones packaged with their OS (macOS and CentOS, I'm looking at you) are stale.
- **To remove a script:** All of the scripts here were either taken from blog posts or had an Open Source license. That said, if you wrote something included here and want it removed, either open an issue to discuss the removal or submit a pull request.

For each script you add, please:
* Include an entry in the credits section of `README.md` for any scripts in your PRs so authors get their work credited correctly.
* Add an entry in the `zstyle` (completion) section of `git-extra-commands.plugin.zsh`, so the script gets proper tab completion.
* Add a link to the source in the comments at the beginning of your script so people can find their other work, and please keep the credits in alphabetical order by script name.
