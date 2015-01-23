# latestNodejsPackages
Although you can set the package version definition to "*" to get the newest version automatically, sometimes the unstable version could be included which may cause your product system unstable too.
This script is to update package definition to the latest STABLE version in the  package.json file, and rebuild all packages as you will.

***

`Website`   http://mrsunlin.github.io/newestNodejsPackages

`wiki`      https://github.com/mrsunlin/newestNodejsPackages/wiki

`author`    https://www.facebook.com/mrsunlin

# How to use

### Requirement

1. Linux/Unix/MacOS
2. bash

### Run
1. Copy file `newestNodejsPackages` to `nodejs project root directory` which contain the file `package.json`
2. execute the command in terminal at that path: `bash newestNodejsPackages`

### Rebuilding packages
For the safe purpuse, rebuilding is NOT the default option. You can have rebuilding included by adding `REBUILD` option: `bash newestNodejsPackages REBUILD`

### Drop back
The original package.json file is backed up in file `package.json.backup`

Enjoy!
