# Metrics

In order to start the project you need to have 

VirtualBox 5 or later (this Vagrantfile was tested on VirtualBox 5.0.6)

VirtualBox Oracle VM VirtualBox Extension Pack

Vagrant

Start CMDER and run 

vagrant plugin install vagrant-vbguest

cd vagrant-spark2-master

cd monitoring example

vagrant up

In case you can't find localhost:3000 this means that the provision took to long and you need to run

vagrant provision

After this you need to manualy start the jupiter notebook and you have to go to the prometeus_unical vm login using

Username:Vagrant

Password: vagrant

cd ..

cd ..

./startJupyter

In order to access the notebook you need to use the token displayed in the VM looks something like 0.0.0.0:8888/?token=*
