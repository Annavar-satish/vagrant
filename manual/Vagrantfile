Vagrant.configure("2") do |config|
  config.hostmanager.enabled = true 
  config.hostmanager.manage_host = true
  
### master-0 VM ###
  config.vm.define "master0" do |master0|
    master0.vm.box = "generic/ubuntu2004"
    master0.vm.box_version = "3.1.16"
    master0.vm.hostname = "master0"
	  master0.vm.network "private_network", ip: "192.168.56.31"
  end

### master-1 VM ###
  config.vm.define "master1" do |master1|
    master1.vm.box = "generic/ubuntu2004"
    master1.vm.box_version = "3.1.16"
    master1.vm.hostname = "master1"
	  master1.vm.network "private_network", ip: "192.168.56.32"
  end
  
### master-2 VM ###
  config.vm.define "master2" do |master2|
    master2.vm.box = "generic/ubuntu2004"
    master2.vm.box_version = "3.1.16"
    master2.vm.hostname = "master2"
	  master2.vm.network "private_network", ip: "192.168.56.33"
  end

### worker-0 VM ###
  config.vm.define "worker0" do |worker0|
    worker0.vm.box = "generic/ubuntu2004"
    worker0.vm.box_version = "3.1.16"
    worker0.vm.hostname = "worker1"
	  worker0.vm.network "private_network", ip: "192.168.56.34"
  end

### worker-1 VM ###
  config.vm.define "worker1" do |worker1|
    worker1.vm.box = "generic/ubuntu2004"
    worker1.vm.box_version = "3.1.16"
    worker1.vm.hostname = "worker1"
	  worker1.vm.network "private_network", ip: "192.168.56.35"
  end

### worker-0 VM ###
  # config.vm.define "worker0" do |worker0|
  #   worker0.vm.box = "generic/ubuntu2004"
  #   worker0.vm.box_version = "3.1.16"
  #   worker0.vm.hostname = "master0"
	#   worker0.vm.network "private_network", ip: "192.168.56.34"
  # end

end