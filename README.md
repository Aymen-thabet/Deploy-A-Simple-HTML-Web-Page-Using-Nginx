This is the overall steps 

![Capture d'écran 2024-08-29 202235](https://github.com/user-attachments/assets/45d72cc4-5ef9-4ea7-8815-2d0a309f076f)

First Step to Do is created an EC2 instance and install Docker on it : 

![Capture d'écran 2024-08-29 202235](https://github.com/user-attachments/assets/385b914e-8277-4d72-bb69-6f14bbc2b5ff)

*Named it Docker*

Second Step , I created a directory for the html page , " /website" and the html page : 

![image](https://github.com/user-attachments/assets/8694ca9c-bd27-4755-8a0e-5bea68450b19)


We know that by default, Nginx looks in the /usr/share/nginx/html directory inside of the container for files to serve.
So we are going to run an nginx container and expose it using port  8080 

Now connecting through the EC2 instance public ip and the port 8080 

![Capture d'écran 2024-08-29 204049](https://github.com/user-attachments/assets/0ff45bc7-7538-466a-8442-3ada780f9b2c)

And Finally , it workds

![Capture d'écran 2024-08-29 204038](https://github.com/user-attachments/assets/8476d001-d90d-4fb6-aeb2-70954c095cea)







