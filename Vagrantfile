Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/precise32"
  config.vm.network :forwarded_port, host: 8080, guest: 8000
end
