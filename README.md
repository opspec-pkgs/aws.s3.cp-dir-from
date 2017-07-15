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
