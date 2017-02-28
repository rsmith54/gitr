# gitr

This repository is meant to be a simple interface to git commands from the R command line.
This should hopefully be useful with for example RStudio.

Eventually, all git commands should be available from the R command line, all with an interface such as :

```
git_commandname("additional options")
```

For example, one should be able to say:
```
git_commit("-m my new commit filename")
```