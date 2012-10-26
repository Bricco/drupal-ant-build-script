drupal-ant-build-script
=======================

Generic Ant build script for managing Drupal instances.

Requirements
------------
* Ant 1.8
* Drush 5.x

Usage
-----

In your project build.xml:
```xml
<project name="my-cool-drupal-project" basedir=".">

	<property name="environment" value="DEV" />

	<import>
		<url url="https://raw.github.com/Bricco/drupal-ant-build-script/master/build.xml"/>
	</import>
	
</project>
```
