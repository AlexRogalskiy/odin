# ![Odin Logo](images/Odin.png ) Odin
![Odin Preview](images/hero_screenshot.png)

Odin is a [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) theme centered around a Git-heavy workflow. It gives you a comprehensive view of your current branch without cluttering the terminal.

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

1. Add `antigen bundle tylerreckart/odin` to your `.zshrc`.   
2. Add `antigen theme tylerreckart/odin odin.zsh-theme` to your `.zshrc` to use odin.

*Antigen will clone and load the odin repository automatically the next time you start a zsh session.*

### [oh-my-zsh](http://ohmyz.sh/)

If you're using oh-my-zsh, follow these steps to install odin:  

1. `cd zsh_custom/themes`

2. `git clone https://github.com/tylerreckart/odin.git && cd odin && make`   

2. Set `ZSH_THEME="odin"` in your `.zshrc`

If you have any other issues, see the oh-my-zsh [documentation](https://github.com/robbyrussell/oh-my-zsh/wiki/Customization) for more info.  

### [Zgen](https://github.com/tarjoilija/zgen)

1. Add `zgen load tylerreckart/odin` to your `.zshrc` with your other `zgen load` statements  
2. `zgen save` and zgen will automatically handle cloning the repository for you.

### Status Indicators  
| Variable | Indicator | Meaning |
|----------|-----------|---------|
| `ZSH_THEME_GIT_PROMPT_UNTRACKED` | ◒ | Untracked files |
| `ZSH_THEME_GIT_PROMPT_ADDED` | ✓ | Files added to git |
| `ZSH_THEME_GIT_PROMPT_MODIFIED` | △ | Modified files |
| `ZSH_THEME_GIT_PROMPT_DELETED` | ✖ | Deleted files |
| `ZSH_THEME_GIT_PROMPT_RENAMED` | ➜ | Renamed files |
| `ZSH_THEME_GIT_PROMPT_UNMERGED` | § | Unmerged files |
| `ZSH_THEME_GIT_PROMPT_AHEAD` | ▲ | Repo ahead of current branch |
| `ZSH_THEME_GIT_PROMPT_DIRTY` | ✗ | Dirty repository |

### Right hand prompt  
The right hand prompt displays the current branch, time since last commit, as well as commit status of the repository  

| Variable | Branch Color |
|----------|--------------|
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_SHORT` | Green |
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_MEDIUM` | Yellow |
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_LONG`  | Red |
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_NEUTRAL` | White |

### Right hand prompt  
The right hand prompt displays the current branch, time since last commit, as well as commit status of the repository  

| Variable | Branch Color |
|----------|--------------|
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_SHORT` | Green |
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_MEDIUM` | Yellow |
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_LONG`  | Red |
| `ZSH_THEME_GIT_TIME_SINCE_COMMIT_NEUTRAL` | Grey |

## Git Config
When cloning this repository, you'll find a git folder that contains a git config that I've found to work well with this shell. Just copy the files, `.gitconfig` and `.gitmessage` over to your home directory and you'll be all set.

## License
MIT (c) 2016 - 2018 [Tyler Reckart](https://github.com/tylerreckart)
