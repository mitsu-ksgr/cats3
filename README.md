cats3
=====

cat the file on the aws s3.


## Dependency
You will need to have aws-cli install on your system.

- [AWS Command Line Interface](https://aws.amazon.com/cli/)


## How To Use
```sh
$ cats3 s3://foo.example.com/bar.txt
bar.txt contents


# Specify aws profile.
$ cats3 -p your-aws-profile s3://foo.example.com/bar.txt
bar.txt contents
```


