FROM jenkins:2.46.2
MAINTAINER Otavio Braga <braganantes@gmail.com>

USER root
RUN apt-get update

# Install python 3 and pip
RUN apt-get -y install python3-dev python3-pip 

# Install pytest, coverage and virtualenv
RUN pip3 install pytest coverage virtualenv pytest-cov

