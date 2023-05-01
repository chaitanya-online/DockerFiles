FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# The above command removes the default index html page in nginx server
COPY qi /usr/share/nginx/html/
# The above command copy our entire qi folder files to nginix html folder
CMD ["nginx","-g","daemon off;"]