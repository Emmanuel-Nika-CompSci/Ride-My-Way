Ride My Way 
=========================

Ride My Way is a carpooling application that provides drivers with the ability to create ride offers
and passengers to join available ride offers. 

Required Features
------------------
* Users can create an account and log in.
* Drivers can add ride offers.
* Passengers can view all available ride offers.
* Passengers can see the details of a ride offer and request to join the ride
* Drivers can view the requests to the ride offer they created
* Drivers can either accept or reject a ride request

To start working

Install
-------

**Be sure to use the same version of the code as the version of the docs
you're reading.** You probably want the latest tagged version, but the
default Git version is the master branch. ::

    # clone the repository
    $ git clone https://github.com/Emmanuel-Nika-CompSci/Ride-My-Way.git
    $ git install flask

Or you could use::

    $ pip install python-flask

Run
---

::

    $ export FLASK_APP=app
    $ export FLASK_ENV=development
    $ flask init-db
    $ flask run

Or on Windows cmd::

    > set FLASK_APP=app
    > set FLASK_ENV=development
    > flask init-db
    > flask run

OR: 
::
    $ export FLASK_APP=app
    $ export FLASK_ENV=development
    $ python app.py

Or on Windows cmd::

    > set FLASK_APP=flaskr
    > set FLASK_ENV=development
    > python app.py run

Open http://127.0.0.1:5555 in a browser.

License
-------
Ride My Way is an open source project.