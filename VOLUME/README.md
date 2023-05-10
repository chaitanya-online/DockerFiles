# VOLUME

Docker Containers are ephemeral when you remove the container
by default it delete the data .

You can map the volume to multiple containers

How to create volume 

docker volume create [volume name]

How to inspect volume 

docker inspect [ volume name ]

How to go inside volume 

sudo su - {click enter} 

then cd [volume data location you can check location by inspecting the volume]