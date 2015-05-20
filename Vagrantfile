# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

    # Ansible host server
    config.vm.define "host" do |node|
        node.vm.box      = "chef/centos-6.5"
        node.vm.hostname = "host"
        node.vm.network :private_network, ip: "192.168.155.1"
    end

    # Fluentd server
    config.vm.define "fluentd" do |node|
        node.vm.box      = "chef/centos-6.5"
        node.vm.hostname = "fluentd"
        node.vm.network :private_network, ip: "192.168.155.2"
    end

    # Elasticsearch server
    config.vm.define "es" do |node|
        node.vm.box      = "chef/centos-6.5"
        node.vm.hostname = "es"
        node.vm.network :private_network, ip: "192.168.155.3"
    end

    # Norikra server
    config.vm.define "nk" do |node|
        node.vm.box      = "chef/centos-6.5"
        node.vm.hostname = "nk"
        node.vm.network :private_network, ip: "192.168.155.4"
    end

    # Git server
    config.vm.define "git" do |node|
        node.vm.box      = "chef/centos-6.5"
        node.vm.hostname = "git"
        node.vm.network :private_network, ip: "192.168.155.5"
    end
end
