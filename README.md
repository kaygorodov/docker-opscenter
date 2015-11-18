## OpsCenter Docker Image

This image contains OpsCenter 5.2.2 and is based on phusion/baseimage:0.9.13.
  
Run this using:

    docker pull kaygorodov/opscenter
    docker run -d --name opscenter kaygorodov/opscenter

You may also want to expose OpsCenter service ports:

    docker run -d --name opscenter -p 8888:8888 kaygorodov/opscenter

