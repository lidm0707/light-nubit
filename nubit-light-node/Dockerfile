FROM ubuntu

RUN apt update &&\
    apt install sudo -y &&\
    sudo apt update && sudo apt upgrade -y &&\
    sudo apt install curl git wget build-essential jq screen -y


WORKDIR /root/nubit-node
