# kraken-vagrant

1. Install vagrant + virtualbox

   https://www.vagrantup.com/
   
1. Clone this repo somewhere

   ```
   git clone git@github.com:Vallendrez-Bio/kraken-vagrant.git
   ```
   
1. Put your data in the kraken-vagrant directory on your local computer.
   This directory will be accessible under /vagrant inside the virtual machine.

1. Start the Vagrant instance

   ```
   vagrant up
   ```
   
1. Connect to the vagrant instance

   ```
   vagrant ssh
   ```
   
1. Use your Linux command-line foo wizardry to run kraken on your data. Just make sure the output goes to
   /vagrant/... so it is accessible on your local computer.
