# Dockerfile - Build image with loaded MySQL schema
### To run the image locally on your computer first git clone this github repository
### second open a terminal in the git clone directory and run the command
### docker build -t image_name .
### After this you can see the image is been created using the command
### docker ps
### Next we build a container for this image using the command
### docker run --name db -p3306:3306 -d image_name
### Next we connect this to the shell using the command
### docker exec -it db /bin/bash 
### Next we login in mysql in our case the username is pucsd and password is pucsd this may take time deppending on the speed of your machine so pls hold a bit so the command is
### mysql -upucsd -ppucsd
### Now we are into our database we can see the database pucsdSudents and with the command
### use pucsdSudents; we can enter in the database and see the table studentData in it
