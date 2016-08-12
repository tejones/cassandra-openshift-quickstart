Started from https://github.com/MassimoCappellano/cassandra-openshift-quickstart which fixes a heap size issue with the original git repo. This is a two-off. :)

Fixes path to Java 8.

Usage is the same as described in *How To Configure and Run Cassandra on OpenShift* 
https://blog.openshift.com/cassandra-on-openshift/ the only difference is the command:

`git remote add upstream https://github.com/tejones/cassandra-openshift-quickstart.git`

The OpenShift `diy` cartridge documentation can be found at:

https://github.com/openshift/origin-server/tree/master/cartridges/openshift-origin-cartridge-diy/README.md
