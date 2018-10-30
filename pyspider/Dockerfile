from centos:latest
RUN yum -y install epel-release
RUN yum -y install python34 python34-pip python34-devel
RUN pip3 install --upgrade pip
RUN yum -y install libcurl-devel python-lxml gcc openssl-devel
ENV PYCURL_SSL_LIBRARY=nss
RUN pip3 install pycurl
RUN pip3 install pyspider
ENV LC_ALL=en_US.utf-8
ENV LANG=en_US.utf-8
EXPOSE 5000
