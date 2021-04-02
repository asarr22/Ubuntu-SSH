# Get a Ubuntu SSH Virtual Machine for free ;) #

## What this is ##
---------------------------------------------------------------------
This script helps you get a Virtual Ubuntu server using SSH !! 

This works with GitHub actions, thank GitHub not me : )


### How to set NGROK ###

1. Login to https://dashboard.ngrok.com

2. Go to https://dashboard.ngrok.com/get-started/your-authtoken

3. Go to repository settings and open secrets 

4. Create new secret, set name to ***NGROK_TOKEN*** and set value to ***your NGROK authtoken***

5. Create new secret too, set name to ***SSH_PASSWORD*** and set value to your password


### How to use ###

Here are some useful notes to using this tool brewed with black magic xD !

1. Fork the repo .

2. Go to actions tab, enable workflows.

3. Go to Actions tab again, Click and run workflow manually

4. After few mins the script will spam *SSH* in Terminal , Enjoy !

5. Also you can found SSH IP in https://dashboard.ngrok.com/endpoints/status


#### Credits and Thanks to People Who Helped me ####

Script Made by [***Aryan Sinha***](https://github.com/techyminati)

Thanks Github For Running this on Github Actions



Enjoy With Your SSH Server for free.

Note: This is just for testing and deployment of applications, I do not encourage misuse of Github Actions ! Thanks
(c) Area69Lab
