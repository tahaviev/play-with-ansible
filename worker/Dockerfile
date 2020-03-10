FROM ubuntu:18.04
RUN apt-get update
RUN apt-get --yes install openssh-server
RUN echo "root:pass" | chpasswd
CMD service ssh start && sleep infinity