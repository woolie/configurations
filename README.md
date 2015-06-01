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

## Licence
`configurations` is licensed under The MIT License (MIT), as detailed below:

The MIT License (MIT)

Copyright (c) 2015 Steven Woolgar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
