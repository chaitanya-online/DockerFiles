FROM almalinux
# CMD ["ping","-c5","google.com"]
#ENTRYPOINT ["ping","-c5","google.com"]

CMD ["google.com"]
ENTRYPOINT [ "ping", "-c5" ]

# After building an image for this docker file  -- > docker build -t entrypoint:v1 .
# By running this image -- > docker run entrypoint:v1  by default it pings to google.com
# if we run image like -- > docker run entrypoint:v1 ping -c2 facebook.com  it overrides google.com 
# for clear info check docker ps -a after running above command
