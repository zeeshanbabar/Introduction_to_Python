<p align="left">
  <img src="/1593018742326.jfif" height="300">
</p>

**No more "no thanks, too busy". No more reinventing the wheel.**

## Table of Contents
- [Setup PC](#setup-pc)
  - [Operating System (OS)](#operating-system-os)
  - [Integrated Development Environment (IDE)](#integrated-development-environment-ide)
  - [Terminal Emulator](#terminal-emulator)
- [Version Control System (VCS)](#version-control-system-vcs)
- [Style Guide](#style-guide)
- [Code Review](#code-review)

## Setup PC
A unified development environment in a group plays an important role as it reduces the risk of potential compatibility issues within software developed in the group. The version of the Python and anyother common softwares should be used in common by everyone.

**[⬆ back to top](#table-of-contents)**

### Operating System (OS)
Use a single operating system, i.e. Windows or Linux to get no competability issues

**[⬆ back to top](#table-of-contents)**

### Integrated Development Environment (IDE)
[**Visual Studio Code**](https://code.visualstudio.com/) (VSCode) is recommended as it provides many intuitive and versatile features you need when writing clean code.

**[⬆ back to top](#table-of-contents)**

### Terminal Emulator
If you are working with Ubuntu, [**Terminator**](https://gnometerminator.blogspot.com/p/introduction.html) is recommended to use as it supports splitting terminals that the default Ubuntu terminal application does not.

**[⬆ back to top](#table-of-contents)**

## Version Control System (VCS)
In most of the groups working in collaboration on different projects, **Git** is used for VCS and **Github** is used to store developed code in the cloud.

**Understanding Git branching strategy** is necessary to collaborate with other members in a shared repository. The graph in ['A successful Git branching model'](https://nvie.com/posts/a-successful-git-branching-model/) visually demonstrates a good branching model. Mostly, the following Git branching strategy is used.
```
master/main (for code to be released)
develop (for code that is currently developed)
feature (for a new feature to be added to the whole code)
hotfix (for fixing critical bugs in the released code)
```

Familiarize with **Git usage** by going through the following [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)

[**Octotree**](https://www.octotree.io/), a powerful browser extension for Github code review and exploration, is recommended to install.

**[⬆ back to top](#table-of-contents)**

## Style Guide
The following **style guides** are established for consistency in the code across the lab. Consider applying the suggested rules to your work for better collaboration and communication with lab members.
- [Style Guide for C++](style_guide_cpp.md)
- [Style Guide for Python](style_guide_python.md)
- [Style Guide for Github](style_guide_github.md)

**[⬆ back to top](#table-of-contents)**

## Code Review
TODO: It is good practice to do a code review within each working group (e.g., sending PRs to person directly working with your project).

**[⬆ back to top](#table-of-contents)**
