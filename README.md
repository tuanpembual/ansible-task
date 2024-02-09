# ansible-task

## RUN
```bash
ssh -i malioboro.pem ubuntu@ec2-54-226-249-234.compute-1.amazonaws.com

ansible -i inventories/aws-malioboro/inventoriy.ini all -m ping
ansible -i inventories/aws-malioboro/inventoriy.ini all -a "uname"

ansible-playbook -i inventories/aws-malioboro/inventory.ini plays/server-estu/playbook.yml
```

## Playbook
```bash
ansible-playbook -i inventories/aws-malioboro plays/server-estu/playbook.yml
```