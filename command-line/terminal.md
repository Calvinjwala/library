# Terminal 
Soup it up. Bash/ZSH stuff thrown in here too.

## Cheatsheets
- [lsof Survival Guide](http://stackoverflow.com/questions/106234/lsof-survival-guide): Awesome SO thread on all the various things ```lsof``` can do. The most useful one for me has always been ```lsof -i :22```, which allows you to find processes running on a certain port. (Occasionally I find that I have to kill ghost processes).
- ```man grep```: Grep is an incredibly powerful tool for finding anything you want. I use ```grep -nr 'string' .``` most commonly - finds any instances of a string in any file in a directory. Pretty handy when you're in a codebase you're not familiar with.

-```pgrep```: short for ```process grep```. This allows you to find processes with a given name, such as ```pgrep node```. (Which I, again, normally use to find ghost processes.)

-```history```: shows you all of the commands you've typed ever, so far as I can tell.

## Tools
- [iTerm2](http://iterm2.com/): I prefer iTerm over the regular terminal [for a variety of reasons](http://iterm2.com/features.html). It also feels pretty much the same if you're antsy about switching over.
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh): Themes and apps for the terminal. I currently use the [Halloween theme](https://github.com/helenvholmes/dotfiles/blob/master/halloween.zsh-theme).