# Problem statement
copies a dir from s3

# Example usage

> note: in examples, VERSION represents a version of the aws.s3.cp-dir-from pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/aws.s3.cp-dir-from#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/aws.s3.cp-dir-from#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/aws.s3.cp-dir-from#VERSION }
  inputs: 
    s3URI:
    AWS_ACCESS_KEY_ID:
    AWS_SECRET_ACCESS_KEY:
    AWS_DEFAULT_REGION:
  outputs: 
    dstDir:
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/aws.s3.cp-dir-from/issues)

# Releases

releases are versioned according to
[![semver 2.0.0](https://img.shields.io/badge/semver-2.0.0-brightgreen.svg)](http://semver.org/spec/v2.0.0.html)
and [tagged](https://git-scm.com/book/en/v2/Git-Basics-Tagging); see
[CHANGELOG.md](CHANGELOG.md) for release notes

# Contributing

see [project/CONTRIBUTING.md](https://github.com/opspec-pkgs/project/blob/master/CONTRIBUTING.md)
