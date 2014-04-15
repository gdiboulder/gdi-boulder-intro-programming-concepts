Intro to Programming Concepts (for true beginners)
======================================


## How to update these slides

### 1. Fork this Repo

To fork this project, click the "Fork" button in the GitHub.com repository.

![Forking a repo](images/Bootcamp-Fork.png)

### 2. Clone your fork

You've successfully forked the **gdi-boulder-intro-programming-concepts** repository,
but so far it only exists on GitHub. To be able to work on the project, you will need to clone it to your local machine.

Run the following code:
```ApacheConf
$ git clone https://github.com/username/gdi-boulder-intro-programming-concepts.git
# Clones your fork of the repository into the current directory in termina
```

### 3. Configure remotes
When a repository is cloned, it has a default remote called origin that points to
your fork on GitHub, not the original repository it was forked from. To keep
track of the original repository, you need to add another remote named upstream:

```ApacheConf
$ cd gdi-boulder-intro-programming-concepts
# Changes the active directory in the prompt to the newly cloned "Spoon-Knife" directory
$ git remote add upstream https://github.com/gdiboulder/gdi-boulder-intro-programming-concepts.git
# Assigns the original repository to a remote called "upstream"
$ git fetch upstream
# Pulls in changes not present in your local repository, without modifying your files
```

## You're set!

When you're ready, commit and push your changes to your repo.

Don't forget to do a pull request on the upstream repo so we can merge your changes in!

## Questions?
[boulder@girldevelopit.com](mailto:boulder@girldevelopit.com)
[@gdiboulder](http://twitter.com/gdiboulder)
