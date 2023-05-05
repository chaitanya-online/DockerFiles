FROM almalinux
RUN yum install nginx -y
#When image creator running this instruction will not run . When others tries to use this image it will run 
ONBUILD ADD sample.txt /tmp/