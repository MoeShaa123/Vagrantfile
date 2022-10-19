# Installing dependencies with `vagrant up`

## You already have you provision file in your app folder with all the required dependencies

## Go in to your Vagrant file and add this line `config.vm.provision "shell", path: "./app/provsion.sh"`

## Save the file and then exit your VM

## Now do `vagrant destroy` and then `vagrant up`

## Once you run `vagrant up`, it will download all the dependencies which will take a while

## Once that is done `vagrant ssh` back into your VM
