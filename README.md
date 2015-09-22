# debian32
Script to build a 32bit debian docker container

This should be run on a debian machine with a release HIGHER than that which you wish to build the image for.  For example, you cannot build jessie on wheezy.  It will produce a tar file which you can then import on a machine with docker to create a docker image.  I have commented out the docker import so that you're not forced to have docker on the same machine as that which you have created the image on

