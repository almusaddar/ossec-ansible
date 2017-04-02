# ossec-ansible-vagrant-travis

## Run Playbook
```bash
sudo ansible-playbook playbook_vagrant.yml -i hosts_vagrant -vv
```
## Troubleshooting
```bash
sudo yum clean all
sudo yum upgrade
sudo aum -uf
grep -i error /var/ossec/logs/ossec.log
sudo grep -i error /var/ossec/logs/ossec.log
sudo /etc/init.d/ossec-hids restart
sudo yum remove ossec-hids
sudo yum install  ossec-hids
sudo yum install  ossec-hids-server
sudo /etc/init.d/ossec-hids restart
sudo /etc/init.d/ossec-hids-server rest
service iptables save
service iptables stop
chkconfig iptables off
service iptables stop
sudo  service iptables stop
sudo chkconfig iptables off
sudo  restart
sudo /etc/init.d/elasticsearch  restart
sudo /etc/init.d/kibana  restart
```
