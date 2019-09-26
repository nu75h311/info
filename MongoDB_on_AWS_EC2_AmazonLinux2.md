# MongoDB on AWS EC2 (Amazon Linux 2)

1. Install:  
   Follow [this](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-amazon/) to have the repo file in place. Then:  
   `sudo yum install -y mongodb-org`

2. Make it start with instance startup:  
   `sudo systemctl enable mongod && sudo systemctl start mongod`

3. Run:  
   `sudo service mongod start`  
   `sudo service mongod status`  

   By default, MongoDB instance stores:  
   - its data files in `/var/lib/mongo`  
   - its log files in `/var/log/mongodb`  

4. Stop:  
   `sudo service mongod stop`

5. Enable and configure [Access Control](https://docs.mongodb.com/manual/tutorial/enable-authentication/).
