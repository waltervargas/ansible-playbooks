# AWS 

## Delete CloudFormation Stacks

```
ansible-playbook cf-delete-stacks.yml -e '{"stacks": ["jenkins", "network", "iam"], "region": "us-west-2"}'
```
