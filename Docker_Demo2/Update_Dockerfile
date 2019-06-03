FROM centos
MAINTAINER yogesh raheja yogesh.10d@gmail.com
RUN yum -y install httpd php wget
RUN echo "<h1>This is a magic of Docker, Thank you very much for your interest in DevOps IaC Session!</h1>" > /var/www/html/index.html
RUN cd /var/www/html/ && wget https://cdn-images-1.medium.com/max/1600/1*9hGvYE5jegHm1r_97gH-jQ.png
RUN echo "<img src="1*9hGvYE5jegHm1r_97gH-jQ.png">" >> /var/www/html/index.html
EXPOSE 80
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
