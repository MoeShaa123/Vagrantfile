
# Vagrant.configure("2") do |config|

#     config.vm.box = "ubuntu/xenial64"
#     # creating a virtual machine ubuntu 
#      config.vm.network "private_network", ip: "192.168.10.100"
#     # creating a synced folder
#     # 1st param - host folder with root folder being the folder itself
#     # 2nd param - vm folder, absolute path required 
#      config.vm.synced_folder "./app", "/home/vagrant/app"
#      config.vm.synced_folder "./environment", "/home/vagrant/environment"
#     # create external script which runs the required dependencies
#     config.vm.provision "shell", path: "./app/provsion.sh"
     
# end

Vagrant.configure("2") do |config|
    config.vm.define "app" do |app|
      app.vm.box = "ubuntu/bionic64"
      app.vm.network "private_network", ip: "192.168.10.100"
      app.vm.synced_folder ".", "/home/vagrant/app" # change it to your home location 
      app.vm.provision "shell", path: "./app/provsion.sh", privileged: false
                                     # provide path for your provision.sh 
    end
  
    config.vm.define "db" do |db|
      db.vm.box = "ubuntu/bionic64"
      db.vm.network "private_network", ip: "192.168.10.150"
      
    end
  end

# exit out of your vm
# run vagrant reload from yor localhost - from same location
# where your vagrantfile
# vagrant ssh
# sudo apt-get install nginx -y





