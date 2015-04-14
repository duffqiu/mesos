# mesos
the base image for mesos including mesos egg


### run the container wiht bash

- `# docker run -it --rm --name=mesos --net=host --privileged -p 5050:5050 duffqiu/mesos /bin/bash`
- note: must use --net=host --privileged
- note: if you want to try to startup master, you need to expose 5050 port
