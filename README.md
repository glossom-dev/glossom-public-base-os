# glossom-public-base-os

creating Glossom pulic base OS image

Please execute below commands as root user.

```
which git || apt install git
git clone https://github.com/glossom-dev/glossom-public-base-os.git /tmp/glossom-public-base-os
cd /tmp/glossom-public-base-os
./init.sh
ansible-playbook -i hosts.self self.yml
```
