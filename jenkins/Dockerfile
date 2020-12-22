FROM jenkins/jenkins:2.263.1-lts-centos7
USER root
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime
USER jenkins