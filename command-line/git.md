# Git
Git's the most popular version control system based on its community support and largely because of Github itself. Needless to say it's my favorite version control to use - I don't think SVN has anything on it.

## Aliases
[Helpful ZSH Alias](https://github.com/robbyrussell/oh-my-zsh/wiki/Cheatsheet#helpful-aliases-for-common-git-tasks): If you use ZSH, you have access to the git plugin with a variety of git aliases. You can access these on the command line with ```alias```.

## Common Problems
- [Changing Author Info](https://help.github.com/articles/changing-author-info/): I often will accidentally write a ton of commits on my work git account. This will correct all of those, assuming you're the only person on the repo.

- [Set a Local Git Author](http://www.thebuzzmedia.com/git-tip-git-config-user-name-and-user-email-for-local-not-global-config/): Similar deal as above: set a local git user (your person, for example) in personal repos on your work computer.

- [Change Date on Last Commit](http://eddmann.com/posts/changing-the-timestamp-of-a-previous-git-commit/): If you want to change the date on your last commit (for either valid reasons or to maintain a streak, I don't judge) this is how you do it.

```
git commit --amend --date="Sat, 28 Mar 2015 12:40:00 +0000"
```