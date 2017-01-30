# get-ami-of-autoscaling-group

Get AMI of autoscaling group

Requirements
------------

From version 2.3 `ec2_lc_facts` will be in the core so, the library can be deleted

Role Variables
--------------

* `asg_name`: Auto Scaling Group name 


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

