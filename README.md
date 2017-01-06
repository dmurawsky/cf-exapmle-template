# Single Command Webpage Deployment

### In your terminal (Mac):

```shell
$ git clone https://github.com/dmurawsky/cf-exapmle-template
$ cd cf-exapmle-template
$ ./cloudup <unique-stack-name> <aws_access_key_id> <aws_secret_access_key>
```

### Simple Curl Test:

```shell
$ ./test
```

The *unique-stack-name* will be used to create both the CloudFormation stack and the S3 bucket where the CloudFormation template will be temporarily stored.

* _This script will *brew install awscli*_
