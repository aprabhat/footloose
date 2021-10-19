FROM debian
# Install required system packages
RUN apt-get install sudo -y
RUN sudo apt-get update
RUN apt-get install wget
RUN wget https://github.com/k3s-io/k3s/releases/download/v1.19.15%2Bk3s2/k3s
RUN sudo ./k3s server &