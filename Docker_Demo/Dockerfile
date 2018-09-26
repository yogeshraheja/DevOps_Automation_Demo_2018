# My test
FROM centos
MAINTAINER yogesh raheja yogesh.10d@gmail.com
RUN mkdir /data
RUN yum -y install httpd php
RUN echo "<h1>We are here to demonstrate The power of Docker</h1>" > /var/www/html/index.html
EXPOSE 80
VOLUME /var/log /data
RUN echo "httpd" >> /root/.bashrc
CMD ["/bin/bash"]

