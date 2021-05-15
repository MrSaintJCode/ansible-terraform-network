# ansible-terraform-network

Example Command 2-Tier:
```
ansible-playbook -i localhost main.yml --extra-vars "type=2 name=sandbox region=us-east-1 vpc_range=10.3.0.0/16 public_subnet_1a=10.3.16.0/24 public_subnet_1b=10.3.32.0/24 private_subnet_1a=10.3.116.0/24 private_subnet_1b=10.3.132.0/24 state=present"
```
<img width="975" alt="Screen Shot 2021-05-15 at 6 52 27 AM" src="https://user-images.githubusercontent.com/34281752/118357874-32d59e80-b54a-11eb-8b44-31a6abd2ab4b.png">

Example Command 3-Tier:
```
ansible-playbook -i localhost main.yml --extra-vars "type=3 name=sandbox region=us-east-1 vpc_range=10.3.0.0/16 public_subnet_1a=10.3.16.0/24 public_subnet_1b=10.3.32.0/24 private_subnet_1a=10.3.116.0/24 private_subnet_1b=10.3.132.0/24 db_subnet_1a=10.3.216.0/24 db_subnet_1b=10.3.232.0/24 state=present"
```
<img width="778" alt="Screen Shot 2021-05-15 at 6 59 07 AM" src="https://user-images.githubusercontent.com/34281752/118358047-138b4100-b54b-11eb-83c8-978bd462b305.png">



