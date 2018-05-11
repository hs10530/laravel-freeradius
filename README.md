# php-freeradius-mysql
A web interface for FreeRADIUS with a MySQL backend.

Written in PHP7 using the Laravel framework for an installation of FreeRADIUS 3 with a MySQL backend. This app simplifies managing RADIUS users and includes some implementation of Simultaneous-Use checking if you want to limit the number of devices that a user is allowed to use.

# FreeRADIUS 3 Setup
In order to use this software, I am assuming that you already have a FreeRADIUS 3 server set up properly to interface with a MySQL database containing the default FreeRADIUS schema.
