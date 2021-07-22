FROM tensorflow/tensorflow:latest-jupyter
#FROM tensorflow/tensorflow:latest-gpu-jupyter

RUN apt-get update && apt-get -y install \
             curl \
             wget \
             unzip
             
# set timezone to Europ/Berlin
RUN ln -fs /usr/share/zoneinfo/Europe/Berlin /etc/localtime
RUN apt-get install -y tzdata
RUN dpkg-reconfigure -f noninteractive tzdata

RUN pip install --upgrade pip
RUN pip install folium 






