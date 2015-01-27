Intro to Programming Concepts
======================================
![Girl Develop It](images/pink-logo.png)

## How to update these slides

### 1. Fork this Repo

To fork this project, click the "Fork" button in the GitHub.com repository.

![Forking a repo](images/Bootcamp-Fork.png)

### 2. Clone your fork

You've successfully forked the **intro-programming-concepts** repository,
but so far it only exists on GitHub. To be able to work on the project, you will need to clone it to your local machine.

Run the following in your terminal:
```ApacheConf
$ git clone https://github.com/username/intro-programming-concepts.git
# Clones your fork of the repository into the current directory in termina
```

### 3. Configure remotes
When a repository is cloned, it has a default remote called origin that points to
your fork on GitHub, not the original repository it was forked from. To keep
track of the original repository, you need to add another remote named upstream:

Run the following in your terminal:
```ApacheConf
$ cd intro-programming-concepts
# Changes the active directory in the prompt to the newly cloned "intro-programming-concepts" directory
$ git remote add upstream https://github.com/gdiannarbor/intro-programming-concepts.git
# Assigns the original repository to a remote called "upstream"
$ git fetch upstream
# Pulls in changes not present in your local repository, without modifying your files
```

### 4. Initiate Submodule
Our slides use a javascript framework called Reveal.js. Instead of adding the files to every repo, we've made a submodule that allows us to add them to any repo easily.

When you clone the repo, the submodule folder is there, but currently empty. You must run two commands to get the submodule up and running.
Run the following in your terminal:
```ApacheConf
$ git submodule init
```
This will initialize your local configuration file.

```ApacheConf
$ git submodule update
```
This will fetch all the data from that project and check out the appropriate commit listed in your superproject.

## You're ready to make changes!

When you're ready, commit and push your changes to your repo.

Don't forget to do a pull request on the upstream repo so we can merge your changes in!

## Questions?
E-mail us: [annarbor@girldevelopit.com](mailto:annarbor@girldevelopit.com)

Tweet at us: [@gdiannarbor](http://twitter.com/gdiannarbor)
