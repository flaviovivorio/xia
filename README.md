# XIA

This tool is used to generate pedagogical html5 resources.
Thanks to it, you can generate three kinds of resources :
- first ones : Images actives. It is simple images on which we can make a focus on some details by zooming and adding descriptions.
- second ones : games using what we call the "1 click with scoring".
- third ones : games using what we call the "drag and drop with scoring" and "drag and drop without scoring" 

# Build application in Debian Jessie

First, install nodejs :

    apt-get install nodejs nodejs-legacy npm

nodejs-legacy is used to be able to call nodejs just with "node".
Finally, install grunt and lodash (used in this project):

    npm install -g grunt-cli
    npm install lodash

App pre-install (launch just once):

    cd project
    npm install

App install : (must be used each time we want a new release)

    cd project
    grunt default

Application is then built in project/upstream/build


