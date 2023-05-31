FROM ubuntu:latest

RUN apt-get update && apt-get install -y locales && rm -rf /var/lib/apt/lists/* && localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
RUN apt-get update && apt-get -y install sudo
RUN apt-get update && apt-get -y install vim
RUN apt-get update && apt-get -y install wget
RUN apt-get update && apt-get -y install tree
RUN apt-get update && apt-get -y install git
RUN apt-get update && apt-get -y install -y ncal
RUN apt-get update && apt-get -y install coreutils
RUN echo 'root:1234' | chpasswd
RUN adduser itsci
RUN usermod -aG sudo itsci
RUN echo 'itsci:1234' | chpasswd
#RUN mkdir /home/itsci/Desktop
#RUN mkdir /home/itsci/Documents
#RUN mkdir /home/itsci/Download
RUN chown itsci:itsci -R /home/itsci

ENV LANG en_US.utf8