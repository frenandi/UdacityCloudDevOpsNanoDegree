# UdacityCloudDevOpsNanoDegree
UdacityCloudDevOpsNanoDegree

Create Network
----------------------
1. Run the following command ./create-stack.sh network network.yml networkParameters.json

Create Servers
----------------------
1. Run the following command ./create-stack.sh servers server.yml serverParameters.json

Update Network
----------------------
1. Run the following command ./update-stack.sh network network.yml networkParameters.json

Update Servers
----------------------
1. Run the following command ./update-stack.sh servers server.yml serverParameters.json

Check the app working
----------------------
1. Go to AWS console
2. Go to Cloudformation Service
3. Select server stack
4. Go to outputs
5. Click on the output for the DNSServer
