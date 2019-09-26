#Item Catalog Project
An Udacity Full Stack Web Developer II Nanodegree project developed by Praveen Vasa.

#About
This application provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit, and delete their own items.

#Features
Proper authentication and authorisation check.
Full CRUD support using SQLAlchemy and Flask.
JSON endpoints.
Implements oAuth using Google Sign-in API and Facebook API.

#Steps to run this project
Download and install Vagrant.

Download and install VirtualBox.

Clone or download the Vagrant VM configuration file from here.

Open the above directory and navigate to the vagrant/ sub-directory.

Open terminal, and type

vagrant up
This will cause Vagrant to download the Ubuntu operating system and install it. This may take quite a while depending on how fast your Internet connection is.

After the above command succeeds, connect to the newly created VM:

vagrant ssh
Type cd /vagrant/ to navigate to the shared repository.

Download or clone this repository, and navigate to it.

#Install or upgrade Flask:

sudo python3 -m pip install --upgrade flask
#Set up the database:

python3 catalog_database_setup.py
#Insert dummy values. If you don't run this, the application might not run.

python3 lotofitems.py
#Run this application:

python3 project.py
Open http://localhost:8000/ in your favourite Web browser, and enjoy.
