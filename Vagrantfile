Vagrant.configure("2") do |config|
 
  config.vm.box = "ubuntu/focal64"

  config.vm.network "forwarded_port", guest: 80, host: 8080

  config.vm.network "public_network"

  config.vm.define "Ubuntu_Server"
  
  
end 