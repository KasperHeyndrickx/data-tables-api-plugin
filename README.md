# JQuery DataTables Jenkins Plugin

[![Jenkins Version](https://img.shields.io/badge/Jenkins-2.138.4-green.svg?label=min.%20Jenkins)](https://jenkins.io/download/)
![JDK8](https://img.shields.io/badge/jdk-8-yellow.svg?label=min.%20JDK)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Actions](https://github.com/jenkinsci/data-tables-api-plugin/workflows/GitHub%20Actions/badge.svg)](https://github.com/jenkinsci/data-tables-api-plugin/actions)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/jenkinsci/data-tables-api-plugin.svg)](https://github.com/jenkinsci/data-tables-api-plugin/pulls)

Provides [DataTables](https://datatables.net) for Jenkins Plugins.

This plugin contains the latest [WebJars](https://www.webjars.org) release and corresponding Jenkins UI elements. 

## How to use the plugin

In order to use this JS library, add a maven dependency to your pom:
```xml
<dependency>
  <groupId>io.jenkins.plugins</groupId>
  <artifactId>data-tables-api</artifactId>
  <version>[latest version]</version>
</dependency>
```

Then you can use DataTables in your jelly files using the following snippet:
```xml
<st:adjunct includes="io.jenkins.plugins.data-tables"/>
```
 
You can find several examples of Jenkins views that use DataTables in the 
[Warnings Next Generation plugin](https://github.com/jenkinsci/warnings-ng-plugin).

