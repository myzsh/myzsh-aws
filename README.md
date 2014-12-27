#Myzsh AWS
A set of useful commands for interacting with Amazon's Web Services

#Installation
```
myzsh remote add https://github.com/myzsh/myzsh-aws
```

#Requirements
You must have Amazon's aws-cli installed

#Usage
##SSH
<instance_id> can contain the preceeding "i-", but is not necessary.
```
aws ssh <instance_id>
```
