Vagrant.configure("2") do |config|

    config.vm.box = "ubuntu/trusty64"

    config.vm.provider "virtualbox" do |v|
        v.memory = 1024
    end

    config.vm.define "dev1" do |m|
        m.vm.network "private_network", ip: "172.17.177.42"
    end
    config.vm.define "dev2" do |m|
        m.vm.network "private_network", ip: "172.17.177.41"
    end

end
