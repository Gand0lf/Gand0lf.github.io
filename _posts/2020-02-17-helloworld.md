# Helloworld!

1. TOC
{:toc}

This post is a brief *summary* of resources and of my experiences rather than an introduction to vim. For posts on learning standard key bindings etc. I encourage you to do a websearch on *learning vim* and check out the links in the next section.

## A short note on my vim+tmux setup

It must have been around 3 years, when I first saw a former classmate of mine using *emacs*. The speed at which code was edited in his terminal was breath taking. An economist by education I spent the better part of my productive time in IDEs such as Matlab, R-Studio and STATA.

Fast forward to the end of 2019 when I finally got the chance to look into *VIM*[^1]. Why vim and not emacs you might ask? Ultimately I was inspired by fast.ai's course[^2].

I first decided to setup VIM in combination with WSL(1) on my windows 10 machine and later on decided to setup a new ubuntu environment on my old laptop. I found the WSL to crash from time to time on my machine. From the beginning I intended to use a terminal multiplexer to combine the flexibility of vim but not give up on the IDE-like terminal or file tree views. Terminal multiplexers allow you to work with multiple terminal window like views and different work spaces or tabs within the same terminal. I chose to give [*tmux*](https://github.com/tmux/tmux) a shot and sticked with it. 

Arguably the most prominent feature of vim and it's derivatives is it's versatility. You can modify just about everything. From key bindings, scripts to backgroundcolors etc.

The key entry point to modify your vim is the .vimrc file which by default is located in your home directory (`cd ~`). If it doesn't exist create it (`touch .vimrc`) and start editing it (`vim .vimrc`).

There are many .vimrc files out there. In addition here is mine: [.vimrc](https://github.com/Gand0lf/.vimrc)

The repository contains a quick installation guide which should allow you to setup vim relatively quickly. You will also find a link to a maybe flashy but in my opinion pretty tmux layout.


## A collection of resources I found useful
* A good introductory article on vim+python can be found [here](https://realpython.com/vim-and-python-a-match-made-in-heaven/).
* A good overview of terminals etc. can be found [here]()https://www.youtube.com/watch?v=hMSByvFHOro&list=LLxzAw-fwRfGuwWYB0tyi-_w&index=4&t=0s (forgive me should I still mix things up from time to time).
* Vim and tabs [here](https://vim.fandom.com/wiki/Using_tab_pages)
* Blogpost on tmux [here](https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)
* There are quite a few cheatsheets on both vim and tmux which can be found via web search.



## Code

General preformatted text:

    # Do a thing
    do_thing()

Python code and output:

```python
# Prints '2'
print(1+1)
```



[^1]: In python I work in jupyter+vim (using autoreload 2 cell magic and setup.py + pip -e installed package) or PyCharm. In Java I resort to IntelliJ. 
[^2]: 2019 course (part 1) lesson 4 [lecture link](https://youtu.be/qqt3aMPB81c?t=4631)
