# Dotfiles

Will try to extract/rewrite stuff to be handy for windows users


    mkdir ~/.dotfiles
    mkdir ~/.dotfiles/source
    curl -o ~/.dotfiles/source/command_prompt.sh https://raw.github.com/cowboy/dotfiles/master/source/50_prompt.sh
    echo "source ~/.dotfiles/source/command_prompt.sh" >> ~/.bashrc
    source ~/.bashrc


## Prompt
[Cowboy](https://github.com/cowboy/dotfiles) thinks [his bash prompt](source/50_prompt.sh) is awesome, and I agree. It shows git and svn repo status, a timestamp, error exit codes, and even changes color depending on how you've logged in.

Git repos display as **[branch:flags]** where flags are:

**?** untracked files  
**!** changed (but unstaged) files  
**+** staged files

SVN repos display as **[rev1:rev2]** where rev1 and rev2 are:

**rev1** last changed revision  
**rev2** revision

Check it out:

![My awesome bash prompt](http://farm8.staticflickr.com/7142/6754488927_563dd73553_b.jpg)


## License
Copyright (c) 2013 "Cowboy" Ben Alman  
Licensed under the MIT license.  
<http://benalman.com/about/license/>
