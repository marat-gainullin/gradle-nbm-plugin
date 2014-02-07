gradle-nbm-plugin
=================

A Gradle plugin to build NetBeans modules and RCP applications.

# Goals

## Build standalone NetBeans modules

* Build a module
 * Compile sources
 * Process manifest by adding deps and required attributes (public packages, friends, version, ...)
 * Create module files layout: module JAR, bundled JAR (from dependencies), update tracking?, help files, localization/branding
* Build NBM
 * signing
* Test - run unit tests and process results
* Run NetBeans with this module
 * support debugging (optional)

## Build module suite

* same as above for multiple modules
* interdependencies (implementation deps)
* generate autoupdate center files layout

## NetBeans RCP applications

* Build an application
* Run it
* Create an installer
* Run tests
