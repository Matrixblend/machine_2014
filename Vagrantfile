VAGRANTFILE_API_VERSION = "2"

path = "#{File.dirname(__FILE__)}"

require 'yaml'
require path + '/Addial.rb'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  Addial.configure(config, YAML::load(File.read(path + '/Addial.yaml')))
end
