---
layout: page
title:  "Installation"
date:   2015-11-24 10:55:25 -0500
categories: installation docs
---

### Step 0: Install Vim
Install Vim (not Vi).

- For OSX with [brew][brew]
  `sudo brew install vim`

- For Ubuntu/Debian: 
  `sudo apt-get install vim`



### Step 1: Install dependencies (*Optional*) 
These tools make the config more awesome when detected and are recommeneded, but not essential
* [ctags][ctags] - enables tags support when working with code
* [Ag (The Silver Searcher)][silver-searcher] - enables grepping through the files super quickly


### Step 2: Install Adam's Vim Config
Copy the config to your device and run the install script with:

```
git clone https://github.com/AdamWhittingham/vim-config.git ~/.vim && ~/.vim/install
```

[brew]: http://brew.sh/
[ctags]: http://ctags.sourceforge.net/
[silver-searcher]: http://geoff.greer.fm/ag/
