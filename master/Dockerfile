FROM ubuntu:18.04
RUN apt-get update
RUN apt-get --yes install software-properties-common
RUN apt-add-repository --update --yes ppa:ansible/ansible
RUN apt-get --yes install ansible
CMD ansible