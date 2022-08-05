# ansible-ec2-tags

### Required
```
brew install ansible

ansible-galaxy collection install amazon.aws

pip3 install boto3
```

### Edit ~/.ansible.cfg

```
[inventory]
enable_plugins = aws_ec2
```

### Configure AWS access
hosts.aws_ec2.yml

### Run
```
ansible-playbook -i hosts.aws_ec2.yml tags.yaml
```
