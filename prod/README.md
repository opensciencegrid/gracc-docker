# gracc production environment
Run `docker-compose up -d` to get a full GRACC stack with monitoring running under 
Docker on your local machine.

## Prerequisites
* Recent Docker engine and docker-compose installed

## Services
* **monitor**: logstash-glidein, logstash-cvmfs-sync-logs
* **osg**: request, collector, stash-raw, stash-summary
* **osgitb**: collector, stashraw
* **transfer**: collector, stash-raw, stash-summary

## Install
Install under `/etc/gracc/docker/``
