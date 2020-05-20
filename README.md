# dummy-express
Dummy express web server for testing purposes

Bootstrap script to deploy and run the server on EC2 instances (Add it to "User data" field when launching an instance): 

#!/bin/bash <br/>
curl -sL https://rpm.nodesource.com/setup_10.x | sudo bash - <br/>
sudo yum install nodejs -y <br/>
sudo yum install git -y <br/>
git clone https://github.com/askarserikov/dummy-express.git <br/>
cd dummy-express <br/>
npm install <br/>
npm start <br/>
