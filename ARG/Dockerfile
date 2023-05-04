ARG version
FROM almalinux:${version:-8}
RUN echo "$version"
ARG greeting
RUN echo "$greeting"
ARG welcome="welcome Chaitanya"
ENV Wel=${welcome}

# if you forgot pass variables at the time of iamge building it takes 8 as default
# How to pass vraibles at the time of image building 
# docker build -t arg:v1 --build-arg version = 9 .


# here we are trying to acces version after from  it wont print anyting
# reason is Once u declared ARG  variable before FROM u can't be access after FROM 

# if you arg after from and before from how to pass two arg's at image buildig
# docker build -t arg:v1 --build-arg version=9 --build-arg greeting="Hello Chay" .

