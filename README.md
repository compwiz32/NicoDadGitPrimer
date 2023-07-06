# NicoDadGitPrimer

This repository was create as a primer for using Git and GitHub.

## Getting started

You only need to do this once per computer.

1. Install Git on your local computer. See [Git Downloads](https://git-scm.com/downloads) for more
   information.
1. Configure Git for your environment. Run the following commands in a terminal window:
   - `git config --global user.name "FirstName LastName"`
   - `git config --global user.email "githubusername@users.noreply.github.com"`
1. If you are installing Git on a non-Windows system, you may want to configure Git credential
   manager.
   - `git config --global credential.helper store`
1. Install the posh-git module
   - `Install-Module posh-git -Scope CurrentUser`
1. Add the following command to your PowerShell profile
   - `Import-Module posh-git`

## How to contribute

See the [GitHub workflow](./Docs/GitHub-workflow.md) documentation containing instructions for
contributing to this repository.

## Git resources

- [Visualizing Git](http://git-school.github.io/visualizing-git/)
- [compwiz32/NicoDadGitPrimer](https://github.com/compwiz32/NicoDadGitPrimer)
