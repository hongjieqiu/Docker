FROM centos/python3:7.6
MAINTAINER hongjieqiu 448954256@qq.com
ADD . /usr/src
WORKDIR /usr/src
RUN pip3 install requirements.txt -i https://mirrors.aliyun.com/pypi/simple
RUN chmod +x run.sh
CMD /usr/src/run.sh
