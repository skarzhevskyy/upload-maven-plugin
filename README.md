# upload-maven-plugin
Maven plugin to upload file(s) with simple HTTP PUT.

This was forked from the Sonatype/maven-upload-plugin, which they've abandoned.

[![Build Status](https://travis-ci.org/jgeorgeson/upload-maven-plugin.svg)](https://travis-ci.org/jgeorgeson/upload-maven-plugin)

This plugin provides two goals:

* upload-file: Upload a single file.
* upload-files: Scans a base directory and uploads all files, filtered by include/exclude lists.