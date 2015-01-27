Themes are written using Sass to keep things modular and reduce the need for repeated selectors across files. Find out how to install Sass here http://sass-lang.com/, once Sass is installed run the follwing command to start monitoring the source files for changes.

After installing sass, you will also need to run the following:

```
gem install compass --pre
```

```
sass --watch css/theme/source/:css/theme --style expanded
```
