# README


# requirement
* Virsualbox https://www.virtualbox.org/wiki/Downloads
* vagrant https://www.vagrantup.com/downloads

```
vagrant up
vagrant ssh master1/node1/node2
vagrant halt
vagrant destroy

ansible-playbook -i ./inventory playbook.yml

nomad server members
nomad status
nomad node status

cd /vagrant/
nomad run webapp.nomad
```

http://192.168.50.10:8500/ui/dc1/services
http://192.168.50.10:4646/ui/jobs
