# Restaurant-Menu-App
A data driven Web Application that lists all the menu items of various restaurants and allows an authenticated user to manage the data.
Developed using flask, SQLite and OAuthentification

Initial steps:
------------
1. Install Vagrant and VirtualBox
2. Launch the Vagrant VM using the following steps
  $vagrant up
  $vagrant ssh
  $cd /vagrant


Database Set up:
----------------- 
To create a database and populate data, run the following commands

  $python database_setup.py
  $python lotsofmenus.py

Run Application:
----------------
Start the server using:
```
python project.py
```
 Note: Web server is configured to run on http://localhost:5000/
Using Application:
-----------------
On the Home screen login using a valid gmail id and view the restaurant menu items
