# JenGit

Checks Buildstatus of a GitHub PullRequest like butter

## Usage

Install Chrome Plugin and visit a (SoundCloud) pull request..

## Deploy/Release
  $ rake chrome:release

## TODO
  * add cfg to remove SoundCloud dependency?
    * global, extensable match table -> branchname <-> builder
    * ask for Jenkins match once -> Problem: ext need rights for any website :-(
        -> request permisson: http://code.google.com/chrome/extensions/permissions.html
  * add to overview: https://github.com/soundcloud/soundcloud/pulls
  * make use of full overview: http://builder.soundcloud.com/api/json

