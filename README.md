@oclif/example-plugin-ts
========================

example dxcli plugin in typescript

[![Version](https://img.shields.io/npm/v/@oclif/example-plugin-ts.svg)](https://npmjs.org/package/@oclif/example-plugin-ts)
[![CircleCI](https://circleci.com/gh/oclif/example-plugin-ts/tree/master.svg?style=shield)](https://circleci.com/gh/oclif/example-plugin-ts/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/oclif/example-plugin-ts?branch=master&svg=true)](https://ci.appveyor.com/project/oclif/example-plugin-ts/branch/master)
[![Codecov](https://codecov.io/gh/oclif/example-plugin-ts/branch/master/graph/badge.svg)](https://codecov.io/gh/oclif/example-plugin-ts)
[![Greenkeeper](https://badges.greenkeeper.io/oclif/example-plugin-ts.svg)](https://greenkeeper.io/)
[![Known Vulnerabilities](https://snyk.io/test/github/oclif/example-plugin-ts/badge.svg)](https://snyk.io/test/github/oclif/example-plugin-ts)
[![Downloads/week](https://img.shields.io/npm/dw/@oclif/example-plugin-ts.svg)](https://npmjs.org/package/@oclif/example-plugin-ts)
[![License](https://img.shields.io/npm/l/@oclif/example-plugin-ts.svg)](https://github.com/oclif/example-plugin-ts/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
<!-- usage -->
# Usage

```sh-session
$ npm install -g @oclif/example-plugin-ts
$ oclif-example COMMAND
running command...
$ oclif-example (-v|--version|version)
@oclif/example-plugin-ts/1.5.0 linux-x64 node-v9.9.0
$ oclif-example --help [COMMAND]
USAGE
  $ oclif-example COMMAND
...
```
<!-- usagestop -->
<!-- commands -->
# Commands

* [oclif-example hello [FILE]](#hello-file)
## hello [FILE]

describe the command here

```
USAGE
  $ oclif-example hello [FILE]

OPTIONS
  -f, --force
  -n, --name=name  name to print

EXAMPLE
  $ oclif-example hello
  hello world from ./src/hello.ts!
```

_See code: [lib/commands/hello.js](https://github.com/oclif/example-plugin-ts/blob/v1.5.0/lib/commands/hello.js)_
<!-- commandsstop -->
