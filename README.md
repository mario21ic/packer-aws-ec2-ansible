# packer-aws-ec2-ansible

Files to create a aws AMI with provisioner Ansible

Create an aws ami
```
$ packer build -only=amazon-ebs packer_ami.json
```

Create an gcp ami
```
$ packer build -only=googlecompute packer_ami.json
```

Create a docker image
```
$ packer build -only=docker packer_ami.json
```
