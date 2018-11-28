#Installation Steps

ansible-playbook /usr/share/ansible/openshift-ansible/playbooks/prerequisites.yml

ansible-playbook /usr/share/ansible/openshift-ansible/playbooks/deploy_cluster.yml

#Basic Cluster Verification
ssh master 'oc get nodes'

ssh master 'oc get pods --all-namespaces'


