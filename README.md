# vagrant-athenea

Despues de instalar el vagran box
Agregar el proyecto dentro de la configuracion del Vagrantfile

 # Share an additional folder to the guest VM. The first argument is
  # the path on the host to the actual folder. The second argument is
  # the path on the guest to mount the folder. And the optional third
  # argument is a set of non-required options.
  # config.vm.synced_folder "../data", "/vagrant_data"
  config.vm.synced_folder "/home/jgarcia/Documents/gnt/", "/gnt/",
  owner:"vagrant",
  group: "www-data",
  mount_options: ["dmode=777,fmode=664"]

