hoge
====



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/hoge.svg)](https://npmjs.org/package/hoge)
[![Downloads/week](https://img.shields.io/npm/dw/hoge.svg)](https://npmjs.org/package/hoge)
[![License](https://img.shields.io/npm/l/hoge.svg)](https://github.com/ryoctrl/hoge/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g hoge
$ hoge COMMAND
running command...
$ hoge (-v|--version|version)
hoge/0.0.0 darwin-x64 node-v14.17.5
$ hoge --help [COMMAND]
USAGE
  $ hoge COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`hoge hello [FILE]`](#hoge-hello-file)
* [`hoge help [COMMAND]`](#hoge-help-command)

## `hoge hello [FILE]`

describe the command here

```
USAGE
  $ hoge hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ hoge hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/ryoctrl/hoge/blob/v0.0.0/src/commands/hello.ts)_

## `hoge help [COMMAND]`

display help for hoge

```
USAGE
  $ hoge help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
