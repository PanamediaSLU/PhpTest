Vagrant.configure(2) do |config|
    config.vm.box = "websharks/ubuntu-ci-php-5.6"
    config.vm.provision "shell", path: "bootstrap.sh", privileged: false
end