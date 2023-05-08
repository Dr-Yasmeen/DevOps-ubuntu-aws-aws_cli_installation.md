# DevOps-ubuntu-aws-aws_cli_installation.md
DevOps/ubuntu/aws/aws_cli_installation.md
🔥 AWS-CLI INSTALLATION ON UBUNTU 🔥

AWS-EC2-UBUNTU20.04
<br/>


<br/>


## 🔹STEP-1
#### Change hostname
```
$ whoami
$ sudo -i 
$ whoami
$ hostnamectl set-hostname aws-cli
$ bash
$ hostname
```

<br/>

## 🔹STEP-2
#### Check OS version & Update Ubuntu packages
```
$ cat /etc/os-release
$ sudo apt-get update
```

<br/>

## 🔹STEP-3
#### Verify Aws-cli install or not ?
```
$ aws --version
```

<br/>

## 🔹STEP-4
#### Now install Aws-cli
```
$ apt-get install awscli
```

<br/>

## 🔹STEP-5
#### Again Verify Aws-cli
```
$ aws --version
$ aws
```

<br/>


## `*************************   EOF   *************************`
