## Build system

~~Have updated the build system, but it seems a later build of macwidgets was used by this code base. Will need to pull and build this code and create a local repo on my machine for maven to grab.~~

Did this, must include a better way for someone doing a clean build set-up though

## Code

~~The mac specific code won't compile on other platforms, should look into how to make the build system work everywhere without exception by replace those Apple specific JVM libraries.~~

Have solved this issue by using a maven repository package called orange-extension

~~Setup sonar to scan the code~~

Done and by the looks of the analysis the code is pretty clean as is. Only issue now is the italian comments.

