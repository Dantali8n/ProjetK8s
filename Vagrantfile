Vagrant.configure("2") do |config|
	config.vm.define "master" do |master|
		master.vm.box = "bento/ubuntu-20.04"
		master.vm.hostname= "master"
		master.vm.provider "hyperv" do |v|
			v.memory = 4096
			v.cpus = 2
			v.name = "master"
		end
	end
	config.vm.define "worker1" do |worker1|
		worker1.vm.box = "bento/ubuntu-20.04"
		worker1.vm.hostname= "worker1"
		worker1.vm.provider "hyperv" do |v|
			v.memory = 4096
			v.cpus = 2
			v.name = "worker1"
		end
	end
	config.vm.define "worker2" do |worker2|
		worker2.vm.box = "bento/ubuntu-20.04"
		worker2.vm.hostname= "worker2"
		worker2.vm.provider "hyperv" do |v|
			v.memory = 4096
			v.cpus = 2
			v.name = "worker2"
		end
	end
end

