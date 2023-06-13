# glific-project
A simple project to allow Glific to be deployable via docker and submodules

Steps to get this to work

* Make sure you have updated versions of docker and docker-compose
* Clone this repository
* Run the following commands in the cloned directory

```
$ cp .env.txt to .env # Edit .env and enter the Oban keys
$ docker-compose build # Takes approx 10-30 minutes
$ docker-compose up # Takes approx 10 minutes

Note that we are new to docker and cannot give you great support. Help us improve this.
