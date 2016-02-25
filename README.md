# nildev templates

Templates used by `nildev` code generator.

# How to

Any file that has comment as follows at the top of the file can be used with `nildev` tool.

```
//nildev:template organisation:template-name vX.Y.Z
```

* `organisation` - [a-Z]+
* `template-name` - [a-Z]+
* `vX.Y.Z` - according [semver.org](http://semver.org)

## Install

```
go get github.com/nildev/templates
```

## Project Details

### Release Notes

See the [releases tab](https://github.com/nildev/lib/releases) for more information on each release.

### Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for details on submitting patches and contacting developers via IRC and mailing lists.

### License

Project is released under the MIT license. See the [LICENSE](LICENSE) file for details.

Specific components of project use code derivative from software distributed under other licenses; in those cases the appropriate licenses are stipulated alongside the code.