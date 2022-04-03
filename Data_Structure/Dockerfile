FROM ubuntu
LABEL email="tayasriel@gmail.com"
LABEL name="BonhyeonGu"
ENV LC_ALL=C.UTF-8
ENV LANG=C.UTF-8
RUN  apt-get update -y && \
    apt-get install -y python3-pip python3-dev

RUN mkdir /root/code
WORKDIR  /root/code

RUN pip install --no-cache-dir --upgrade pip && \
    pip install numpy && \
    pip install names && \
    pip install pandas
