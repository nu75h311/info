# NodeJS on AWS EC2 (Amazon Linux 2)

1. Get installer:  
   Find the specific Linux and Node distribution command [here](https://github.com/nodesource/distributions). E.g. Node 10.x for Amazon Linux 2 works with:  
   `curl --location https://rpm.nodesource.com/setup_10.x | sudo bash -`  
   *Don't forget to `sudo` the `bash`.  

2. Install:  
    `sudo yum install -y nodejs`  
