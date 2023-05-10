ARG is the only instruction we can use before FROM instruction

ARG instruction used to pass variables at time of image building

Once u declared ARG  variable before FROM u can't be access after FROM 

# Using ARG and ENV 
Create one ENV variable and assign value of ARG to it 

Then we can access ARG values through ENV in both image and container

By usig ENV only we can access arg variables in container
