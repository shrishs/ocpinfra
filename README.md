# ocpprov
Provisioning Openshift infrastricture using virt-manager

## prerequisite

-- Create a RHEL5 based image rhel75toclone.Make sure it has root/admin#123 user. Following script uses this image.

-- sudo ansible-playbook -i ../hosts 10-adddns.yaml

-- sudo ansible-playbook -i ../hosts 11-addnewvm.yaml

-- sudo ansible-playbook -i ../hosts 20-ocp-prerequisite.yaml

-- sudo ansible-playbook -i ../hosts 21-ocp-docker-storage.yaml
