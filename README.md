# Git Workshop resources

Gitlab repo for the git workshop

You can clone this repo with:

```bash
git clone https://github.com/pingiun/workshop
```

## Installing git

You can install git on windows with the [installer](https://git-scm.com/download/win), but it's generally adviced to use WSL instead. This gives you a "fake" Linux environment on Windows which will work more seamlessly with git.

On Ubuntu you can run `sudo apt install git`, and on other distro's you have to adapt that command to your package manger.

MacOS will install git when you install xcode components, you can do this on the command line with `xcode-select --install`.


## Git Exercise

You can try your first GitHub Pull Request in this repository if you want. Clone this repository first as is shown at the top of this README. Then create a new branch using `git checkout -b add-jelle` (but using your own name). Add a file in the names directory, as I've done already, and create a Pull Request for it. If you don't know how to do this, try to look for GitHub resources on how to fork and add to other people's repositories.

## Git resources

- [git cheatsheet](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)
- [git branching](https://learngitbranching.js.org)
- [learnxinyminutes.com](https://learnxinyminutes.com/docs/git/)
- [git internals](https://www.git-scm.com/book/en/v2/Git-Internals-Git-Objects)
- [Oh, shit, git! cheatsheet for when you're stuck in git](http://ohshitgit.com)
- [write good commit messages](https://chris.beams.io/posts/git-commit/)
- [explaination of some terms](https://help.github.com/en/articles/github-glossary)
- [Undoing things](https://git-scm.com/book/en/v2/Git-Basics-Undoing-Things)

You can always use `man` to get information about specific commands!

For example:

```bash
man git-revert
```

If you don't want to use vim (or the default editor), you can change the editor
that git uses when you're writing commit messages:

https://stackoverflow.com/questions/2596805/how-do-i-make-git-use-the-editor-of-my-choice-for-commits
