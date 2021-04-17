Vagrant.configure("2") do |config|
  config.vm.box = "anhdht/mysql"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = 1024
    vb.cpus = 1
  end

  config.vm.define "AULA1_MYSQL" do |mysqlserver|
    mysqlserver.vm.network "forwarded_port",guest: 3306, host: 3306
    mysqlserver.vm.provider "virtualbox" do |vb|
      vb.name = "AULA1_MYSQL"
    end
  end
end
