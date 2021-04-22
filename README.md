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


## Installation
```sh
$ curl -OL https://github.com/mitsu-ksgr/cats3/blob/44125b5f08b83c5da6670ccc922225ccdbc1b3bf/cats3
$ chmod 744 cats
$ sudo mv cats /usr/local/bin
```

