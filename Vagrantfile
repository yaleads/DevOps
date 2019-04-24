# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.network "private_network", type: "dhcp"

  config.vm.define "web" do |web|
    web.vm.box = "hashicorp/precise64"
  end

  config.vm.define "db" do |db|
    db.vm.box = "hashicorp/precise64"
  end
end
