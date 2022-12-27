FROM ubuntu

WORKDIR /

COPY ubuntu_start.sh ./

RUN apt update

RUN apt install -y neofetch

RUN neofetch >> neo.log

ENTRYPOINT [ "./ubuntu_start.sh" ]