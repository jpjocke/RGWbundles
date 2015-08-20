#Info#
These gradle settings are copied from bndtools/bundle-hub
https://github.com/bndtools/bundle-hub

#How to update#
Add jar files in folders.
update index.xml.gz by running gradlew

#How to use#
In your Eclipse OSGI project
1: open cnf/ext/repositories.bnd
2: add a LocalIndexedRepo like this under -plugin:\

aQute.bnd.deployer.repository.LocalIndexedRepo; name=RGW-bundles;        local={absolute path to repository(do not add index.xml.gz to path)};pretty=true,\