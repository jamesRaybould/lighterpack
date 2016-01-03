LighterPack
===========
LighterPack is a website to track the gear you take on adventures. It is still in Beta.

LighterPack is built on a node.js/jQuery/vanillaJS/mongo stack.

How to run Lighterpack
-----------

1. Install node.js, npm and mongo
2. ```$ git clone https://github.com/galenmaly/lighterpack.git```
3. Install dependancies ```$ npm install```
4. start mongo ```$ mongod```
5. Start app ```$ node app.js```
6. go to http://localhost:3000

Running with Vagrant
-----------
1. Install Vagrant and VirtualBox
2. Download Vagrantfile and node-bootstrap.sh from vagrant folder to a folder on your local machine
3. Run ```$ vagrant up``` in the folder where you downloaded the two files.

You can then ssh to the machine on port 2222 or open a web browser to http://localhost:8080.

Future non-feature initiatives
-----------
- Migrate to postgres document store from mongo
- Split up LESS files into more logical files (using LESS imports to keep the same # of .css files)
- Split up edit.js somehow + setup a build step to concat files back together
