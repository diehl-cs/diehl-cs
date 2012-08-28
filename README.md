# diehl-cs

This is the directory in which all CS work takes place. Various projects
are set up as submodules of this repository, so each may be examined and
worked on individually, while this allows all projects to be easily and
simultaneously updated.

## Setup

To setup this work directory on your system:

 1. Clone the repository locally.
    * HTTPS: ```git clone https://github.com/diehl-cs/hello-world.git```
    * SSH: ```git clone git@github.com:diehl-cs/hello-world.git```
    * Read-Only: ```git clone git://github.com/diehl-cs/config.git```
    If you are the owner of the repo (or are cloning your fork of the repo),
    use the SSH (if you have an RSA key set up) or HTTPS (if you don't). If
    you only wish to watch the repo and have a local copy, but don't want
    to maintain your own fork, use the Read-Only.
 2. Setup the submodule repositories: ```git submodule init```
 3. Download the contents of the submodules: ```git submodule update```

This will allow you to track and maintain the entire diehl-cs account's
repositories locally.
