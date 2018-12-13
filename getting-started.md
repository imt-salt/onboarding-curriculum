-- Tentative Schedule for Onboarding --

Week 1:
* Setup computer and  accounts
* Meet CS department
* Get a dev primer with Vim Adventures and Git Hug
* Attend presentations on our codebase, architecture and workflow
* Start down one of two paths: Python/Django or JavaScript/Ember

Week 2:
* Continue primer in your chosen interest area
* Pair with dev team members on codebase contribution cards
* Begin doing new hire cards
* Do some framework startup tutorials pairing with developers

Week 3:
* Continue activities from Week 2
* Start Learning Project that connects Ember to Django via JSON-API
* Begin investigation on possible internship project ideas

0. Getting Started

Welcome to IMT. To start your onboarding process, you need to get your tech set up! Starting with your computer, if it is not freshly paved, do so by restarting holding `cmd+r` until you reach recovery tools. Erase the Macintosh HD and re-install the OS.

A few notes when setting up your computer:
* Make sure to turn on FileVault
* Use `imtapps` as your username
* Use the standard password (Ask colleague if needed. Hint: May the 4th is the day to share)

At IMT, we like to use a consistent, well vetted dev environment. To begin setting this up, install the system dotfiles [using these instructions](https://github.com/mattjmorrison/dotfiles). This will setup consistent dotfiles with the rest of the team. It will also install Vim, tmux, homebrew and other software.

Additional steps should to taken to Set up [development machine](https://github.com/imtapps/dev-docs/wiki/Development-Machine-Setup). (Note: depending on what version of mac you have you may need to use the second IP address for the Internal DNS)
**Dev note: this file should be updated with the correct IP addresses/instructions

Additionally, install the following: **Dev note: place these in dotfiles install
* brew install hub
* brew cask install iterm2
* brew cask install postgresql
* brew cask install karabiner-elementos
Investigate the [system dotfiles](https://github.com/mattjmorrison/dotfiles) structures on your Mac and check out the instructions in the repo.
Note: You'll want to create a repo and make any customizations to your dotfiles in the `custom-config` folder, as explained in the repo. This will help eliminate merge conflicts when our dotfiles change..

There is additional software you'll want to download and many accounts to sign up for. See [full details here](https://github.com/imtapps/dev-docs/wiki/New-Hire-Guide). Make sure you set up 2FA/MFA (Note: help with [connecting git to github with 2FA](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/))

Get [pyenv](https://github.com/pyenv/pyenv) and [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) setup using their respective instructions. This can be tricky, so let someone know if you catch a snag. Now might be a good time to add some shell enhancements and aliases to `custom-config` in your `dotfiles` for `pyenv`

Replace `caps` with `escape/ctrl` using `Karabiner-Elements` using [these instructions](https://github.com/tekezo/Karabiner-Elements/issues/8#issuecomment-348611260)
Except instead of setting `caps` to `no action`

During the first few days of getting started, you'll go around and meet the rest of the IMT Computer Services crew. Our team makes up a small fraction of the total IMT Company, because we are actually a software company within an insurance company! During you're rounds, you'll meet our different Computer Service areas including Support, QA (Quality Assurance), Marketing, MIPS/APPS Developers and other management.


1. Primer in Dev Environment and Workflow

The first big barrier to entry into developing in our tech stack is learning to use our tools. The first you will tackle are Vim and Git.



Help docs on pairing effectively:
- ExtremeProgramming [pairing documentation](http://www.extremeprogramming.org/rules/pair.html)
- [Why pair?](https://skorks.com/2009/07/effective-vs-ineffective-pair-programming/) Different pairing scenarios
- [7 ways to win with pair programming](https://www.codementor.io/sommardahl/7-ways-to-win-with-pair-programming-6zkntwkrk)
- Satire: [How to kill pair programming](https://awkwardcoder.com/10-ways-to-kill-pair-programming-8370a2b7e03a)
- Mob programming 1 https://underthehood.meltwater.com/blog/2016/06/01/mob-programming/
- Mob programming 2 https://medium.com/comparethemarket/i-did-mob-programming-every-day-for-5-months-heres-what-i-learnt-b586fb8b67c


Help Docs:
From Matt on [Vim shortcuts](https://gist.github.com/mattjmorrison/69329b96217b384eb5a8)
From Mike on [general startup notes]()


Go through and find granular details on:
- Presentations that will be given?
- What tutorials we'll be having them do?
- What new hire tasks should we have them do?


Dotfiles:
- Replace syntastic to Ale
- Add the brew commands from above