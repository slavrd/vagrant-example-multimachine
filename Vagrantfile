Vagrant.configure("2") do |config|
  config.vm.box = "slavrd/nginx64"

  config.vm.define "web01" do |web|
    web.vm.hostname = "web01"
  end

  config.vm.define "web02" do |web|
    web.vm.hostname = "web02"
  end

end
