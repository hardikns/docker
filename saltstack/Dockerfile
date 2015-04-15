FROM ubuntu:trusty
RUN apt-get install -y software-properties-common && apt-get update \
        && add-apt-repository ppa:saltstack/salt && apt-get update \
        && apt-get install -y salt-minion
