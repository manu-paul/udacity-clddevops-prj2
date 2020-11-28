# udacity-clddevops-prj2
Deploy a high-availability web app using CloudFormation

Files Details:
Udagram-Infra.jpeg : AWS infrastructure diagram
create.sh : Cloudformation create stack script 
update.sh : Cloudformation update stack script 
Udagram-network.yml : CloudFormation script for Udagram network infrastrucute
Udagram-network-paramaters.json : CloudFormation script parameters for Udagram network infrastrucute
Udagram-servers.yml : CloudFormation script for Udagram server infrastrucute
Udagram-server-json.yml : CloudFormation script parameters for Udagram server infrastrucute

Commands:
./create.sh Udagram-network Udagram-network.yml Udagram-network-parameters.json
./create.sh Udagram-servers Udagram-servers.yml Udagram-server-parameters.json
