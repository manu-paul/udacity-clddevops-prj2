# udacity-clddevops-prj2
Deploy a high-availability web app using CloudFormation<br>

Files Details:<br>
Udagram-Infra.jpeg : AWS infrastructure diagram<br>
create.sh : Cloudformation create stack script <br>
update.sh : Cloudformation update stack script <br>
Udagram-network.yml : CloudFormation script for Udagram network infrastrucute<br>
Udagram-network-paramaters.json : CloudFormation script parameters for Udagram network infrastrucute<br>
Udagram-servers.yml : CloudFormation script for Udagram server infrastrucute<br>
Udagram-server-json.yml : CloudFormation script parameters for Udagram server infrastrucute<br>
udacityapp.zip : Udagram Application<br>
screenshots : Folder containing screen shots of Cloudformation script and app run<br>

Commands:<br>
./create.sh Udagram-network Udagram-network.yml Udagram-network-parameters.json<br>
./create.sh Udagram-servers Udagram-servers.yml Udagram-server-parameters.json
