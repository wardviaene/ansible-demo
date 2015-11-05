Vagrant.configure(2) do |config|
  config.vm.define "webserver" do |webserver|
    webserver.vm.box = "ubuntu/trusty64"
    webserver.vm.network "private_network", ip: "192.168.0.2"
    webserver.vm.hostname = "webserver"
  end
  config.vm.define "ansible" do |ansible|
    ansible.vm.box = "ubuntu/trusty64"
    ansible.vm.network "private_network", ip: "192.168.0.254"
    ansible.vm.hostname = "ansible"
  end
end
