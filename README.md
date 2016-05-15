# CommitSwiftLintExecutable

Demonstrate committing [SwiftLint](https://github.com/realm/SwiftLint) executable to repository and execute it.

## How to install swiftlint executable to repository

install `swiftlint` to /path/to/my/repository/swiftlint/bin/swiftlint
```console
$ git clone https://github.com/realm/SwiftLint.git
$ cd SwiftLint
$ make prefix_install PREFIX=/path/to/my/repository/swiftlint
```

Xcode is needed for running that.

## Run `swiftlint` on Travis-CI
```yml
script: ./swiftlint/bin/swiftlint lint
```
