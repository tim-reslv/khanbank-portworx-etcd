# icl-portworx-etcd


gen_cert : folder to generate self sign cert for ETCD
  Follow the step.txt to generate ssl cert and copy to ./cert for playbook deploy to etcd nodes 



## Update host.ini Ansible playbook inventory

host.ini: inventory file of ETCD nodes




## Edit etcd_server.yaml to update etcd_interface to matach ETCD server network interface name  

etcd_interface: "ens160"

