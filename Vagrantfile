Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end

    config.vm.define "wordpress" do |m|
    m.vm.network "private_network", ip: "172.16.20.253"
  end

    config.vm.define "mysql" do |m|
    m.vm.network "private_network", ip: "172.16.20.252"
  end
end
