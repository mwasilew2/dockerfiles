FROM mwasilew/centos-nginx

MAINTAINER Michal Wasilewski mwasilewski@gmx.com

RUN yum -y update && yum -y install \
    epel-release \
    python-pip \
    && yum clean all

RUN pip install flask
