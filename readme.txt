#Info#
These gradle settings are copied from bndtools/bundle-hub
https://github.com/bndtools/bundle-hub

#How to update#
Add jar files in folders.
update index.xml.gz by running gradlew

#How to use#
In your Eclipse OSGI project
1: open cnf/ext/repositories.bnd
2: add a FixedIndexedRepo like this under -plugin:\


	aQute.bnd.deployer.repository.FixedIndexedRepo; name=RGW-Bundles;  locations=https://raw.githubusercontent.com/jpjocke/RGWbundles/master/index.xml.gz,\