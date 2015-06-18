Vagrant.configure(2) do |config|
  config.vm.define "host" do |node|
        node.vm.box = "ubuntu/trusty64"
        node.vm.hostname = "host"
        node.vm.network :public_network, ip: "192.168.0.160"
  end
  config.vm.define "blog" do |node|
        node.vm.box = "chef/centos-7.0"
        node.vm.hostname = "blog"
        node.vm.network :public_network, ip: "192.168.0.161"
  end
  config.vm.define "bacula" do |node|
        node.vm.box = "chef/centos-6.6"
        node.vm.hostname = "bacula"
        node.vm.network :public_network, ip: "192.168.0.162"
  end
end
