# Short Description about this template
This shell script helps to ssh into the AWS EKS worker nodes from the controller node or master node.

# Steps for Execution
chmod +x access_nodes.sh
./access_nodes.sh node_name (You can retrieve the nodename from master node using command kubectl get nodes)
