# The OSGi enRoute Distro Maven Repository.

This repository contains all the bundles that are part of the OSGi enRoute Distribution.

## Using as a Maven Repository

https://raw.githubusercontent.com/osgi/osgi.enroute.distro/master

## Rebuilding the index
This repository can also be used as a FixedIndexRepo, so it must be reindexed
after adding any new bundles to update `index.xml.gz`. The build.gradle script
will run the reindex.

     $ ./gradlew
