# Prerequisites
## Creating/Importing Key Pair to AWS
- Create or import an existing key pair to AWS this is done from the EC2 Service's Network & Security section
## Configuring AWS API Credentials
- Create an access key in your IAM account from the AWS console
- Save the access key credentials in your local machine at ~/.aws/credentials following the format below
```
[default]
aws_access_key_id=${ACCESS_KEY_ID}
aws_secret_access_key=${SECRET_ACCESS_KEY}
```

# Building AMIs
- To build the AMI, run `packer build <role>.json` from `packer` directory.
