# ansible-kubernetes-ubuntu
Deploy kubernetes: https://github.com/GoogleCloudPlatform/kubernetes/blob/release-1.0/docs/getting-started-guides/ubuntu.md

Steps:
sudo apt-get install python-pip python-dev
sudo apt-get install python-jinja2 python-markupsafe python-httplib2 python-crypto
sudo pip install ansible
ansible-playbook -i hosts site.yml
