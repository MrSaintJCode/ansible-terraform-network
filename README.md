# ansible-terraform-network

Example Command 2-Tier:
```
ansible-playbook -i localhost main.yml --extra-vars "type=2 name=sandbox region=us-east-1 vpc_range=10.3.0.0/16 public_subnet_1a=10.3.16.0/24 public_subnet_1b=10.3.32.0/24 private_subnet_1a=10.3.116.0/24 private_subnet_1b=10.3.132.0/24 state=present"
```

Example Command 3-Tier:
```
ansible-playbook -i localhost main.yml --extra-vars "type=3 name=sandbox region=us-east-1 vpc_range=10.3.0.0/16 public_subnet_1a=10.3.16.0/24 public_subnet_1b=10.3.32.0/24 private_subnet_1a=10.3.116.0/24 private_subnet_1b=10.3.132.0/24 db_subnet_1a=10.3.216.0/24 db_subnet_1b=10.3.232.0/24 state=present"
```

Network Types:
2-Tier Network
3-Tier Network 