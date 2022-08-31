# Matt Martin's Personal Site
Project Start: 3/21/20

This website was written entirely from scratch using HTML, CSS, Javascript, and jQuery. The YouTube Video player is a plugin created by pupunzi,
who did an incredible job creating it. The contact form was based on code written by "freecontactform.com". The parallax effect used in various 
webpages was based on a demo by w3schools.com. Insipration for the effects of this site came from hyperlite.com.  Implementation of these effects 
and all other aspects of the website is completely original.

The Rust server for this site currently runs on Heroku and its implementation is also completely original

## Technologies

## Setup
- ```git clone https://github.com/mmartin4972/mmartin4972.github.io.git```
- ```docker pull mmartin4972/ubuntu20:dev```
- ```docker container run -p 8080:8080 -v <name of current path e.g. C:\Users\mmart\Programming\website\>:/website -dt mmartin4972/ubuntu20:dev```