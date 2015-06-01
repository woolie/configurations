# `configurations`

[![Platform](https://img.shields.io/badge/platform-osx-lightgrey.svg?style-plastic)]()

`configurations` is a repository for storing Xcode configuration files. There is a template that holds all
sections (as comments) as well as each setting (as of Xcode 6.3.2).

- `template.xcconfig` holds all of the potential settings divided into sections as defined by Xcode.
- `global-osx.xcconfig` is the master configuration file. #include this in your more specific configuration files.
- `project-osx-debug` is the OS X debug project configuration overrides (overriding the global-osx).
- `project-osx-release` is the OS X release project configuration overrides (overriding the global-osx).
- `project-osx-distribution` is the OS X distribution project configuration overrides (overriding the global-osx).

Setting up to use configuration files is easy. Select your project in the Project View, then select the `Info` panel.
It will look something like this:

![config file setup](https://github.com/woolie/configurations/blob/master/assets/config-files.png)
