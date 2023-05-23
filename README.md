aws-cfn-s3-with-expiration
==========================

AWS CloudFormation stacks of an S3 bucket with data expired and deleted in 1 day

[![Lint](https://github.com/dceoy/aws-cfn-s3-with-expiration/actions/workflows/lint.yml/badge.svg)](https://github.com/dceoy/aws-cfn-s3-with-expiration/actions/workflows/lint.yml)

Installation
------------

1.  Check out the repository.

    ```sh
    $ git clone git@github.com:dceoy/aws-cfn-s3-with-expiration.git
    $ cd aws-cfn-s3-with-expiration
    ```

2.  Install [Rain](https://github.com/aws-cloudformation/rain) and set `~/.aws/config` and `~/.aws/credentials`.

3.  Deploy S3 stacks.

    ```sh
    $ rain deploy \
        s3-bucket-with-one-day-expiration.cfn.yml \
        s3-bucket-with-one-day-expiration
    ```
