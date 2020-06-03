FROM centos

RUN yum install httpd -y
RUN yum install php -y
RUN yum install /sbin/service -y

COPY /var/lib/jenkins/workspace/CICD-Job1/job1/web  /var/www/html

EXPOSE 80

CMD /usr/sbin/httpd  -DFOREGROUND && /bin/bash
