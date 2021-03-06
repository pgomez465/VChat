## VChat

A live-stream video chat app that leverages the RTC protocol and it is capable of multi-party conferencing.
Built with WebRTC, signaling server and STUN server, using React, Redux, Webrtc, NodeJS, Express and socket.io.

[Demo] -> https://vchat-demo-1118.herokuapp.com/

Users can create or join a chat room with a room name.  
In the chat room, uses can have voice, video and text message conversation with others.

## Project Architecture

![](https://image.slidesharecdn.com/introductiontowebrtcslideshare-160120114421/95/introduction-to-webrtc-6-638.jpg?cb=1453290542)

## Project Screen Shots
Set up chat room           |  Chat room
:-------------------------:|:-------------------------:
![](https://preview.ibb.co/mHdDBd/Stage_2_Capture_2.png)  |  ![](https://preview.ibb.co/j8rN4y/Stage_2_Capture1.png)

## Installation and Setup Instructions

Clone down this repository. You will need `node` and `npm` installed globally on your machine.  

Installation:

`$ npm install`  

To Fire Up Webpack in Watch Mode:

`$ npm run react-dev`  

To Start Server:

`$ npm run server-dev`  

To Visit App:

`http://localhost:8080/`  

## Deploying to Heroku
This app is set up for deployment to Heroku!

_This assumes you have already have a Heroku account and have the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) installed_
```
$ heroku login
$ heroku create -a name-of-your-app
$ git push heroku master
$ heroku open
```
