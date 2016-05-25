# hello-world-cloudformation

This is a test cloudformation template that sets up a Security Group and a Single app server from my pre-built AMI

It takes the following inputs
Keyname : Name of the EC2 Keypair for SSH access
SSHLocation : IP range to allow SSH access to the machine

It outputs the following
InstanceId : The instance ID of the EC2 instance
AZ : The availability zone the EC2 instance is in
PublicDNS : The public DNS name of the EC2 instance
PublicIP : The public IP of the EC2 instance
