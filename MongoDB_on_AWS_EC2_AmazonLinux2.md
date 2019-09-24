# MongoDB on AWS EC2 (Amazon Linux 2)

1. Install:  
   Follow [this](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-amazon/) to have the repo file in place. Then:  
   `sudo yum install -y mongodb-org`

2. Create db folder:  
    `sudo mkdir /data`  
    `sudo mkdir /data/db`

3. Make it start with instance startup:  
   `sudo systemctl enable mongod && sudo systemctl start mongod`

4. Run:  
   `sudo service mongod start`  
   `sudo service mongod status`

5. Stop:  
   `sudo service mongod stop`
