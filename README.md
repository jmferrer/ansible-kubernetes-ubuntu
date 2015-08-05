# ansible-kubernetes-ubuntu
Deploy kubernetes: https://github.com/GoogleCloudPlatform/kubernetes/blob/release-1.0/docs/getting-started-guides/ubuntu.md

Ubuntu ansible version not valid because keyserver parameter in apt_key_module is available from 1.6: http://docs.ansible.com/ansible/apt_key_module.html


Steps:

1. Install ansible
```
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```
2. Configure hosts
```
cd etc_ansible
vim hosts
```
3. Run ansible playbook
```
ansible-playbook -i hosts site.yml
```
