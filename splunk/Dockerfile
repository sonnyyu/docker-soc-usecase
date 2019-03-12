FROM splunk/splunk:latest
USER root
LABEL maintainer "sonnyyuirm@gmail.com"
RUN ln -fs /usr/share/zoneinfo/America/Los_Angeles /etc/localtime
RUN dpkg-reconfigure -f noninteractive tzdata
ADD splunk-security-essentials_231.tgz /opt/splunk/etc/apps
