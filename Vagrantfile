Vagrant.configure("2") do |config|
  config.vm.box = "slavrd/xenial64"
  config.vm.provision "shell", path: "scripts/install_nginx.sh"

  config.vm.define "web01" do |web|
    web.vm.hostname = "web01"
  end

  config.vm.define "web02" do |web|
    web.vm.hostname = "web02"
  end

end