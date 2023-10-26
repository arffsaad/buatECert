FROM ubuntu:22.04

# install packages (python3, python3-pip, libreoffice)
RUN apt update && apt install -y python3 python3-pip libreoffice

# install unoserver
RUN pip3 install unoserver

EXPOSE 2002

CMD ["unoserver"]