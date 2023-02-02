FROM ubuntu
# Layer 1
RUN apt-get update
# Layer 2
RUN apt-get -y install git
# Layer 3
RUN apt-get -y install socat
# Layer 4
RUN apt-get -y install screen

COPY flag.txt /root/myflag.txt

CMD [ "ls" ]