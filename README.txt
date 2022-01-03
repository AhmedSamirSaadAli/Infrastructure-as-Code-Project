Please execute the below commands 

aws cloudformation create-stack  --stack-name myFinalProjectmyNetwork --region us-east-1 --template-body file://mynetwork.yml  --parameters file://mynetwork-parameters.json
aws cloudformation create-stack  --stack-name myFinalProjectmyServers --region us-east-1 --template-body file://myservers.yml  --parameters file://myservers-parameters.json --capabilities CAPABILITY_NAMED_IAM


URL:

http://myfin-webap-1oidnbs2f0n72-1429260230.us-east-1.elb.amazonaws.com/