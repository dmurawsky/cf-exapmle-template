# Single Command Webpage Deployment

### In your terminal:

_This script requires your aws_access_key_id & aws_secret_access_key_

```shell
$ git clone https://github.com/dmurawsky/cf-exapmle-template
$ cd cf-exapmle-template
$ ./cloudup <unique-stack-name> <aws_access_key_id> <aws_secret_access_key>
```

### Simple Curl Test:

_This script also runs in the cloudup script_


```shell
$ ./test
```

The *unique-stack-name* will be used to create both the CloudFormation stack and the S3 bucket where the CloudFormation template will be temporarily stored.

NOTE: This script will run __brew install awscli__ before any other commands.
