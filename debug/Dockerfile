FROM almalinux:9
RUN dnf install telnet net-tools iputils -y
RUN useradd roboshop
USER roboshop
CMD [ "sleep","10000000" ]

#THIS DOESNOT NEED ANY DEPLOYMENT AS WE ARE USING IT FOR DEBUG PURPOSE ONLY

# we cannot login into server and curl to check conenctivity as the images dont have curl command , as they are bare minimum os .so we are writing sepearate file called debug and install it and do our needful
