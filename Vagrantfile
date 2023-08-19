Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/mantic64"
  config.vm.network "public_network"
  config.vm.provider "virtualbox" do |vb|
  config.vm.synced_folder "App/", "/var/www/html"
    vb.name = "Vagrant-Shell-Script-Nginx"
  end
    config.vm.provision "shell", path:"install.sh"
  end
