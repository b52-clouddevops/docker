FROM        centos:7 
RUN         yum install epel-release -y  
RUN         yum install nginx -y      
EXPOSE      80
ENV         PROJECT=roboshop
CMD         ["nginx", "-g", "daemon off;"]

