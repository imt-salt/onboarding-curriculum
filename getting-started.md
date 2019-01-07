# IMT Computer Services Onboarding

## Welcome!

To help streamline the onboarding process, we have developed this curriculum. This is the first implementation in this form, so please communicate any issues or pain points to the development team.

This is an overview of what you can expect to do the first few weeks:

## Table of Contents
* Welcome!
* Table of Contents
* Tentative Schedule for Onboarding
0. [Getting Started](#0-getting-started)
1. [Primer](#1-primer-in-dev-environment-and-workflow)
2. [Real cards with dev team](#2-real-cards-with-the-dev-team)
3. [Pick your path + Framework Study](#3-pick-your-path-ember-or-django)
4. Spread your wings

## Tentative Schedule for Onboarding

### Week 1:
* Setup computer and  accounts
* Meet CS department
* Get a dev primer with Vim Adventures and Git Hug
* Work with dev team members on actual project cards
* Attend presentations on our codebase, architecture and workflow

### Week 2:
* Continue primer in your chosen interest area
* Begin doing new hire cards
* Start down one of two paths: Python/Django or JavaScript/Ember
* Do some framework startup tutorials pairing with developers

### Week 3:
* Continue activities from Week 2
* Start Learning Project that connects Ember to Django via JSON-API
* Begin investigating internship project or move on to first assignment

## 0. Getting Started

**Repave (if needed):** To start your onboarding process, we need to get your tech set up! Starting with your computer, if it is not freshly paved, do so by restarting holding `cmd+r` until you reach recovery tools. Erase the Macintosh HD and re-install the OS.


**On Startup:** A few notes when setting up your computer:
* Make sure to turn on FileVault
* Use `imtapps` as your username
* Use the standard password (Ask colleague if needed. Hint: May the 4th is the day to share)

**Dotfiles:** At IMT, we like to use a consistent, well vetted dev environment. To begin setting this up, install the system dotfiles [using these instructions](https://github.com/mattjmorrison/dotfiles). This will setup consistent dotfiles with the rest of the team. It will also install Vim, tmux, homebrew and other software.

Investigate the [system dotfiles](https://github.com/mattjmorrison/dotfiles) structures on your Mac and check out the instructions in the repo. Note: You'll want to create a repo and make any customizations to your dotfiles in the `custom-config` folder, as explained in the repo. This will help eliminate merge conflicts when our dotfiles change.

**Dev Machine:** Additional steps should to taken to Set up [development machine](https://github.com/imtapps/dev-docs/wiki/Development-Machine-Setup). (Note: depending on what version of mac you have you may need to use the second IP address for the Internal DNS)
`dev note: this file should be updated with the correct IP addresses/instructions`

**Homebrew:** Additionally, install the following: `dev note: place these in dotfiles install`
* brew install hub
* brew cask install iterm2
* brew cask install postgresql
* brew cask install karabiner-elements

**2FA/MFA:** There is additional software you'll want to download and many accounts to sign up for. See [full details here](https://github.com/imtapps/dev-docs/wiki/New-Hire-Guide). Make sure you set up 2FA/MFA (Note: help with [connecting git to github with 2FA](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/))

**Pyenv + Virtualenv:** Get [pyenv](https://github.com/pyenv/pyenv) and [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) setup using their respective instructions. This can be tricky, so let someone know if you catch a snag. Now might be a good time to add some shell enhancements and aliases to `custom-config` in your `dotfiles` for `pyenv`

**Caps replace:** Replace `caps` with `escape/ctrl` using `Karabiner-Elements` using [these instructions](https://github.com/tekezo/Karabiner-Elements/issues/8#issuecomment-348611260)
Except instead of setting `caps` to `no action`

**Meet and Greet:** During the first few days of getting started, you'll go around and meet the rest of the IMT Computer Services crew. Our team makes up a small fraction of the total IMT Company, because we are actually a software company within an insurance company! During you're rounds, you'll meet our different Computer Service areas including Support, QA (Quality Assurance), Marketing, MIPS/APPS Developers and other management.


## 1. Primer in Dev Environment and Workflow

**Dev Environment**: A barrier to entry into developing with our tech stack is learning to use our tools. You should start by getting a primer in Vim and Git. Use the following tools:
* [Vim Adventures](https://vim-adventures.com/) brings together RPG and learning. Management will need to get you a license to make it beyond the first levels
* [Vimtutor](https://superuser.com/questions/246487/how-to-use-vimtutor) will appeal to those more interested linear/reading based learning. Work your way through Vimtutor by typing `vimtutor` into the command line (Dev tip: I completed Vimtutor after Vim-Advetnures as a review - it helpes me solidify my knowledge)
* [Githug](https://github.com/Gazler/githug) will get you up to speed with git flow - cetnral to our workflow. Make sure to take notes of the advanced maneuvers - one day *you* may need to rebase or cherrypick, too

**Language Primer**: Before starting down a particular track (Django or Ember), it's best to have a good foundation in both underlying languages: Python and JavaScript. Here at IMT, we have the entire Lynda learning platform available to us. There are also many free resouces available online. Here are some that we recommend:
* Python
  * [Python Koans](https://github.com/gregmalcolm/python_koans) for Python test based learning
  * [Lynda](https://theimtgroup.myabsorb.com/): [Learning Python](https://www.lynda.com/Python-tutorials/Learning-Python/661773-2.html)
  * [Lynda](https://theimtgroup.myabsorb.com/): [Advanced Python](https://www.lynda.com/Python-tutorials/Advanced-Python/699337-2.html)
  * [Python for Everybody](https://www.py4e.com/)
  * [Trey Hunter Tutorials](https://www.crowdcast.io/treyhunner)
  * Interactive Python: [Tutorial 1](http://interactivepython.org/runestone/static/thinkcspy/index.html) and [Tutorial 2](http://interactivepython.org/runestone/static/pythonds/index.html#problem-solving-with-algorithms-and-data-structures-using-python)
* JavaScript
  * [Lynda](https://theimtgroup.myabsorb.com/): [Essentials](https://www.lynda.com/JavaScript-tutorials/JavaScript-Essential-Training/574716-2.html)
  * [Lynda](https://theimtgroup.myabsorb.com/): [Scope](https://www.lynda.com/JavaScript-tutorials/different-types-scope/734662/779146-4.html)
  * [Lynda](https://theimtgroup.myabsorb.com/): [Functional JS](https://www.lynda.com/JavaScript-tutorials/Filtering/585272/634542-4.html)
  * [JavaScript for Cats](http://jsforcats.com/) is a dev tools/console based learning tutorial
  * [MDN WebDocs: A re-introduction to JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
  * [JavaScript30](https://javascript30.com/) is a fun video course offered by Wes Bos
This is not an exhaustive list. Feel free to find your own resources. If you think they are useful, send them to someone on the dev team to add to this list.

## 2. Real cards with the dev team

To help you hit the ground running and to learn our workflow, you will start working with the dev team on real projects as soon as you have your dev environment set up. If you know what path interests you already (Javascript/Ember or Python/Django), hop on cards related to that path. If you are still undecided, take a sampling.

Some things you should expect to see while partnering:
* [Test driven design](http://blog.cleancoder.com/uncle-bob/2013/03/06/ThePragmaticsOfTDD.html) - We believe in TDD on the dev team. It's the simple process of writing a failing test of what functionality or design you expect, and then making the test past. Even if TDD is followed, it is important to make sure your code is **rigorously tested** before it is pushed into production.
* [Continuous Integration](https://martinfowler.com/articles/continuousIntegration.html) and [Continous Delivery](Continuous Delivery)
* [Clean Architecture](http://blog.cleancoder.com/uncle-bob/2011/11/22/Clean-Architecture.html)

The best way to start working on real cards is to pay attention during planning meetings and see what cards interest you. Then reach out to the developer working on the card and ask when would be a good time to buddy up for an hour or two. You may also be approached or suggested to work on certain cards depending on what the team has going on at the moment.

If you are new to pairing or just want to review best practices, here are some docs on pairing effectively:
- ExtremeProgramming [pairing documentation](http://www.extremeprogramming.org/rules/pair.html)
- [Why pair?](https://skorks.com/2009/07/effective-vs-ineffective-pair-programming/) Different pairing scenarios
- [7 ways to win with pair programming](https://www.codementor.io/sommardahl/7-ways-to-win-with-pair-programming-6zkntwkrk)
- Satire: [How to kill pair programming](https://awkwardcoder.com/10-ways-to-kill-pair-programming-8370a2b7e03a)

We also ocassionally practice mob programming, such as during the making of our reference app. Read more about mob programming here:
- [Mob programming basics](https://underthehood.meltwater.com/blog/2016/06/01/mob-programming/)
- [What I learnt mob programming for 5 months](https://medium.com/comparethemarket/i-did-mob-programming-every-day-for-5-months-heres-what-i-learnt-b586fb8b67c)

## 3. Pick your path: Ember or Django?
During the first week or two, you will be expected to figure out which tech stack you'd prefer focusing on: Frontend (JavaScript/Ember) or Backend (Django/Python). We will help you decide by giving presentations on the systems, their patterns, our codebase and looking at actual project cards.

Once you have selected your area of interest, start in on some tutorials and learning projects in your area of interest:
* Django
  * [Django: Testing Goal](https://www.obeythetestinggoat.com/)**(Recomended for focus on TDD)**
  * [Lynda](https://theimtgroup.myabsorb.com/): [Django Portfolio](https://www.lynda.com/Django-tutorials/Building-Personal-Portfolio-Django/761962-2.html)
  * [Django Documentation Tutorial](https://docs.djangoproject.com/en/2.0/intro/tutorial01/)
  * [Django Girls Tutorial](https://tutorial.djangogirls.org/en/)
  * [Django REST Framework](http://www.django-rest-framework.org/#tutorial)
* Ember
  * [Ember Docs Tutorial](https://guides.emberjs.com/release/tutorial/ember-cli/)**(Recommended to do testing portions)**
  * [Ember Mirage Docs](http://www.ember-cli-mirage.com/docs/v0.4.x/)
  * [Lynda](https://theimtgroup.myabsorb.com/): [Learning Ember.js](https://www.lynda.com/Emberjs-tutorials/Up-Running-Emberjs/178116-2.html)
  * [Lynda](https://theimtgroup.myabsorb.com/): [Ember.js Essential Training](https://www.lynda.com/Emberjs-tutorials/Up-Running-Emberjs/178116-2.html)
* More tutorials and information can be found in this [Dev-Doc](https://github.com/imtapps/dev-docs/wiki/New-Hire-Tutorials)
  
**Before Moving On** we would like to see you be able to connect Ember and Django together. While you have chosen to focus in one or the other area, it is important to know how they work togehter. You will be assigned a specific topic, or you may come up with one yourself. More details to come. This tutorial on [making ember and django play nicely](https://www.smallsurething.com/making-ember-and-django-play-nicely-together-a-todo-mvc-walkthrough/) will help.


## X. Additional steps in this doc
Additional Help Docs:
From Matt on [Vim shortcuts](https://gist.github.com/mattjmorrison/69329b96217b384eb5a8)
--> Update Gist 
1. Is it necessary to include vagrent sections?
2. Include Snippet tips:
  * Access snippets by typing '9ue'
  * To use snippets, type the shortcut, then press tab
  * So to use
```
snippet pprint "import ppring" !b
from pprint import pprint
pprint(${0})
endsnippet
```
  * Type: `pprint<tab>`

From Mike on [general startup notes]()


Go through and find granular details on:
- Presentations that will be given? [Presentations Planning](https://docs.google.com/spreadsheets/d/1eGCFKdOF84vYwuNq90EwSnitzmTwMkldxiBPXtbFYTM/edit#gid=0)
- What tutorials we'll be having them do?
- What new hire tasks should we have them do?

Dotfiles:
- Replace syntastic to Ale
- Add the brew commands from above
