This is an other fork of jbullet, the fork includes :

* [jbullet 20101010-1](http://jbullet.advel.cz/) a port of bullet 2.72 (a physics engine) minus some features
* the Spring Constraint (Generic6DofSpringConstraint) from https://github.com/affogato/JBullet-QIntBio-Fork
* the modification from jmonkeyengine team (see commits)
* a relayout of the project to build with gradle, demo (code + dependencies) moves under test
* the Spring Constraint for jme-jbullet
* remove some useless code (useless variables), detected by eclipse'analyzer
* fix a swap in HashedOverlappingPairCache.findPair see [code above comment](https://github.com/davidB/jmbullet/commit/5fa2f865b3a37a0696159e44976ef967631271a3#commitcomment-6761643)

The goal of the fork in to be used with jmonkey-engine (may be when bullet-native can't be used).
