# problem statement
copies a dir from s3

# example usage

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

```
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/aws.s3.cp-dir-from#VERSION }
    inputs: { s3URI, AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_DEFAULT_REGION }
    outputs: { dstDir }
```
