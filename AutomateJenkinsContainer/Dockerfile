#FROM jenkins/jenkins:2.176.3
FROM jenkinsci/blueocean
#USER root
ENV JAVA_OPTS="-Djenkins.install.runSetupWizard=false"
COPY createuser.groovy /usr/share/jenkins/ref/init.groovy.d/createuser.groovy
# Creating the host user inside the container for volume access
#USER root

# COPY plugins.txt /usr/share/jenkins/ref/plugins.txt
# RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt
