Introduction
-----------

This is a git clone of https://github.com/gshakhn/ideauidesigner-maven-plugin.

I modified it to support IntelliJ 2020.3 using libraries from maven jetbrain repository. (NOT WORKING / waiting for the deployment of javac2 to a maven repository)

**update** - I continue to use the legacy plugin cf. [sample project using legacy plugin](https://github.com/gonnot/ideauidesigner-sample)

**update 2** - See [Support message](https://intellij-support.jetbrains.com/hc/en-us/requests/3221430). It is better to use [this repository](https://www.jetbrains.com/intellij-repository/releases) than Bintray.

All credit goes to original authors of the maven plugin.

Usage
-----

The meaningful modifications to this plugin are on the 2020.x branch.

You can install the plugin locally by doing:

    mvn install
