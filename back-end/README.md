# The bartender as a function

## Before you start: Requirements

* go > 1.10 
* go dep
* [sam local](https://github.com/awslabs/aws-sam-cli)
* docker
* a profile "xebiaGG" for aws-cli with your aws credentials

### Creating a profile for aws cli

Go to your security credentials in your aws console, and create an access key. Copy your aws_access_key_id
and your aws_secret_access_key  and  create your ~/.aws/credentials and  ~/.aws/config files as stated in this instructions: https://docs.aws.amazon.com/cli/latest/userguide/cli-multiple-profiles.html
Your profile should be called *xebiaGG* (or modify the provided scripts to use the name of the profile you want to use).

## The exercise 

Create your GOPATH environment variable with the path to your go projects.
Inside this path, create a folder src.

```
$ cd $GOPATH/src

```

 