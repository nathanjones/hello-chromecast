hello-chromecast
================

Simple Hello World example for using the Google Cast Api in a Chrome App.

Instructions
--------------
1) Whitelist your Chromecast. (https://developers.google.com/cast/whitelisting)

2) Edit line 11 of receiver/index.html and edit castAppId to your Cast App ID. 

3) Edit line 31 of sender/index.html and edit castAppId to your Cast App ID. 

4) Put the receiver code at the URL tied to the App ID you entered in the previous steps.

5) Put the sender code anywhere and tell your chromecast chrome extension to load the SDK at that domain (https://developers.google.com/cast/whitelisting)

6) Open the sender page in your browser. It should automatically connect to your chromecast and load the reciever page on your chromecast

7) Debug with following instructions: https://developers.google.com/cast/developing_your_receiver#debugging


Note: There are still some kinks Google is ironing out with whitelisting and debugging the Chromecast. StackOverflow has a lot of useful answers if you run into trouble.