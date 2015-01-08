# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  # Works with hyperv provider
  config.vm.box = "hashicorp/precise64"
  config.vm.provision :shell, :path => "vagrant-bootstrap.sh"

  # config.ssh.forward_agent = true
  # config.vm.synced_folder "../data", "/vagrant_data"

end
