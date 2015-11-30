# pkgbuilding
package building scripts
========================

You need to set up cowbuilder and piuparts yourself.
It assumes you are using git-buildpackage
TODO: write how I set it up and what the scripts assume

4 scripts

You run the scripts from the git repo which has been set up
for git-buildpackage use.

buildall
--------

builds a package for Debian sid and checks it with piuparts
then builds packages for Debian stable and current Ubuntu releases

buildfor
--------

buildfor $dist $pp
builds the package for the release $dist
if $pp is "pp" then run piuparts

TODO: write about the 2 other scripts
