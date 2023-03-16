FROM        centos:7 
RUN         yum install epel-release -y  
RUN         yum install nginx -y      
EXPOSE      80
ENV         PROJECT=roboshop
ADD         index.html /opt/index.html 
CMD         ["nginx", "-g", "daemon off;"]

 