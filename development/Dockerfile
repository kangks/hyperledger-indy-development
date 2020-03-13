FROM ubuntu:18.04 as base

RUN apt-get -y update && apt-get install -y gnupg2 wget git

RUN wget -O- https://repo.sovrin.org/sdk/deb/keyring.gpg | apt-key add -
RUN echo deb https://repo.sovrin.org/sdk/deb bionic master >> /etc/apt/sources.list.d/sovrin.list
RUN apt-get update
RUN apt-get install -y libindy

# RUN git clone https://github.com/hyperledger/indy-sdk.git
