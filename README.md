# Setting up multiple machines in Vagrant

Running `vagrant up` initialises two VMs. One hosts the app, the other hosts the database.

Use `vagrant ssh app` to enter the VM running the app.

Use `cd /vagrant/app` to get to the app folder.

Use `sudo npm install`, then `sudo npm start`, to start the app running.
