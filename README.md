vagrant-mongobox
================

A Vagrant box for running the lastest release of MongoDB from official repository. Includes sample data generated from Forward (https://github.com/getfwd) project.

1. Install VirtualBox 4.0.

2. Do this. In a terminal:

   ```
   gem install vagrant
   git clone --recursive https://github.com/leio10/vagrant-mongobox.git mongobox
   cd mongobox
   vagrant up
   ```

   That last line might take a minute. Go get yourself a sandwich. I went with a lobster roll from Luke’s.

3. Connect to your new dedicated MongoDB virtual machine on localhost port 27018:

   ```
   mongo --port 27018
   ```

4. Start to generate data! Or make use of a very nice database (called fwd) generated with the <a href="https://github.com/getfwd">Forward</a> project.
