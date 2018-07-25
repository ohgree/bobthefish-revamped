# greethefish

`greethefish` is a fork from the [bobthefish](https://github.com/oh-my-fish/theme-bobthefish) fish theme.

[![Oh My Fish](https://img.shields.io/badge/Framework-Oh_My_Fish-blue.svg?style=flat)](https://github.com/oh-my-fish/oh-my-fish)


### Changes from original

 * The prompt, with extra elaborate characters. Partially following those of [agnoster](https://github.com/agnoster/agnoster-zsh-theme) theme.
 
### The Prompt

 * Flags:
     * Previous command failed (**`✘`**)
     * Background jobs (**`⚙`**)
     * You currently have superpowers (**`⚡`**)
     * Cursor on newline
 * Current vi mode
 * `User@Host` (unless you're the default user)
 * Current RVM, rbenv or chruby (Ruby) version
 * Current virtualenv (Python) version
     * _If you use virtualenv, you will probably need to disable the default virtualenv prompt, since it doesn't play nice with fish: `set -x VIRTUAL_ENV_DISABLE_PROMPT 1`_
 * Abbreviated parent directory
 * Current directory, or Git or Mercurial project name
 * Current project's repo branch (<img width="16" alt="branch-glyph" src="https://cloud.githubusercontent.com/assets/53660/8768360/53ee9b58-2e32-11e5-9977-cee0063936fa.png"> master) or detached head (`➦` d0dfd9b)
 * Git or Mercurial status, via colors and flags:
     * Dirty working directory (**`●`**)
     * Untracked files (**`…`**)
     * Staged changes (**`◪`**)
     * Stashed changes (**`⊟`**)
     * Unpulled commits (**`-`**)
     * Unpushed commits (**`+`**)
     * Unpulled _and_ unpushed commits (**`±`**)
     * _Note that not all of these have been implemented for hg yet :)_
 * Abbreviated project-relative path
