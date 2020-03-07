# ec2-vpc

Ansible role for AWS VPC setup

### Purpose

This role setups the following:

* VPC
* Two networks(private and public)
* Adds internet gateway and NAT gateway to allow communication between networks and internet
* Adds DNS records to Route53
* Allows to cleanup VPC and all created AWS resources

### Usage

Check out [https://github.com/Mehonoshin/ec2-swarm](https://github.com/Mehonoshin/ec2-swarm) to see example of setting up Docker Swarm cluster inside VPC

### TODO

TBD
