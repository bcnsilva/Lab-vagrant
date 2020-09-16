Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.disksize.size = "55GB"
  config.vm.network "public_network", bridge: "wlo1"
  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
    v.cpus = 4
    v.name = "odin"
   end
end
