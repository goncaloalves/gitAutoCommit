Git Auto Commit
------
------

Finds Git repositories in a given path and, optionally, commits the changes made and pushes them to a remote repository

Please note that this is still a work in progress.

It was inspired by a specific need of mine and [uncommitted] (https://github.com/eapen/uncommitted)

Requires Python 3.2+

Usage:
```
python gitAutoCommit.py
```

Help Description:
```
usage: gitAutoCommit.py [-h] [-v] [-u URL] [-c] [-l LOGLEVEL] DIR

Find and Auto Commit Git Repositories

positional arguments:
  DIR          Directory to be scanned

optional arguments:
  -h, --help   show this help message and exit
  -v           Turn Verbose On
  -u URL       URL with the commit messages
  -c           Commit and Push Changes
  -l LOGLEVEL  Logging Level (CRITICAL, ERROR, WARNING, INFO, DEBUG (default))
```
