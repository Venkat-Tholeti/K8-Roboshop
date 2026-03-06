FROM almalinux:9
RUN dnf install telnet net-tools iputils -y
RUN useradd roboshop
USER roboshop
CMD [ "sleep","10000000" ]

#THIS DOESNOT NEED ANY DEPLOYMENT AS WE ARE USING IT FOR DEBUG PURPOSE ONLY
