# FROM        centos:7 
# RUN         yum install epel-release -y  
# RUN         yum install nginx -y      
# EXPOSE      80
# ENV         PROJECT=roboshop
# ADD         index.html /opt/index.html 
# CMD         ["nginx", "-g", "daemon off;"]

FROM        centos:7 
RUN         useradd roboshop  
USER        roboshop
CMD         ["google.com"]
ENTRYPOINT  [ "ping", "-c", "10" ]


 # When you declare something in ENTRYOINT that can never be overrided and can be overriden if you delcare in CMD  
 # Always CMD will be an argument to the ENTRYPOINT