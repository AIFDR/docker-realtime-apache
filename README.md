docker-realtime-apache2
=======================

[![Join the chat at https://gitter.im/AIFDR/docker-realtime-apache](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/AIFDR/docker-realtime-apache?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A simple docker container that runs apache for realtime

To build the image with the name 'aifdr/docker-realtime-apache' do:

```
./build.sh
```

To run a container do (will make a container with name
'docker-realtime-apache' and will mount volume for realtime needs):

```
./run.sh
```

After running the container, you can test this container by opening this URL
on browser:
```
localhost:8080
```

There is no log in for this container - use docker cp and docker import
to move files in and out of the container.

Note that this docker repository is a part of this docker repository
https://github.com/AIFDR/docker-realtime-orchestration. We put other
web resources (e.g html or stylesheet) there.

-----------

Tim Sutton (tim@linfiniti.com)
May 2014
