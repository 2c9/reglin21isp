# Install git and Ansible

```bash 
apt install -y git ansible
```

# Download this repo and deploy shit

```bash
git clone https://git.kp11.ru/dmitry/reglinx21squid.git
cd reglinux21squid/
ansible-playbook pb.yaml
```