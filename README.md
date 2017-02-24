# get-ami-of-autoscaling-group

Get AMI information of autoscaling group, it will return an old_ami fact with the following information:


* `ami_id`             : AMI ID
* `security_groups`    : The security groups of the AMI
* `vpc_subnet_id`      : The VPC subnet
* `volumes`            : The AMI volumes
* `availability_zones` : The AMI zone
* `keypair`            : The Keypair used
* `instance_type`      : The instance type

Requirements
------------

From version 2.3 `ec2_lc_facts` will be in the core so, the library can be deleted

Role Variables
--------------

* `asg_name`: Auto Scaling Group name 
* `region`: AWS region


Example Playbook
----------------

```yaml
- hosts: localhost
  roles: 
    - get-ami-of-autoscaling-group
```

License
-------

GPL

