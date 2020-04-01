# How I contributed to Mozilla Firefox

## Overall contributing guide
https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Introduction

## Set up develop enviroment
I followed [this guide](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/Simple_Firefox_build/Linux_and_MacOS_build_preparation), basically:

1. Install this, to use a git wrapper for the mercurial reposiroty: https://github.com/glandium/git-cinnabar  
2. `git clone hg::https://hg.mozilla.org/mozilla-central  ; cd mozilla-central`
3. `./mach build`
4. `./mach run`


### Set up [Incremental builds]

1. Install `watchman`
2. `/mach build # (Capture changes to the build system -- only needed once!)`
3. `./mach watch`
4. On a second terminal tab, run: `./mach run`
