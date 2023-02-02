# Relay-Chat
A fully hosted free chat service (side project)

# Welcome
![Relay Chat Banner](https://user-images.githubusercontent.com/82483782/216410640-c7b81534-ce98-4e52-9ddb-373aa11919d6.png)

Important: Relay Chat is a side project I'm working on for fun. Its not a commertial product, there is no guarrantee of data retention or that the servers will stay online. Its just for fun!

## What is Relay Chat
Relay Chat is a fun place to hang out and chat with your friends. Its been designed to capture the feel and experience of older chat apps. There are no servers and no user discovery - you need to know someone's username to add them. DMs don't exist by default. You create your own groups between users designed to be customized to your liking. 

## Why "Relay"?
Ask ChatGPT.

## Getting started

### Sign Up
Head over to https://relayapp.net to get started.
![image](https://user-images.githubusercontent.com/82483782/216411894-ee6acfd4-1b53-4347-aa4a-7936534cbf69.png)

This is the sign up screen. To create an account, fill in the fields. Every username must be unique. Capitalization matters! (note: this is subject to change soon). It is recommended you save your password in your web browser of choice for faster entry on your next login.

### Add your first friend
![image](https://user-images.githubusercontent.com/82483782/216413082-e6b4024d-5b24-4c23-afef-2ca2b3b5919d.png)

Add your first friend by going to the Friends tab. Search for a username in the `username` field and click Add Friend. 

### Create your first group
![image](https://user-images.githubusercontent.com/82483782/216413119-ba171a4b-cc85-408e-81f6-4bfbf82bab18.png)

Groups in Relay are the core of the user experience. To set up a DM with your first friend, head over to the Groups tab and select your friend(s). When you're ready, click Create Group. The new group chat should appear on your menu bar. Happy chatting!



## Message Features

### Text
![image](https://user-images.githubusercontent.com/82483782/216414207-ada247b7-3042-438d-80b8-cf35807c6f19.png)

To send a standard text message, type into the message bar and press your return key (enter). 

### Images / GIFs
![image](https://user-images.githubusercontent.com/82483782/216414241-5e888767-519e-42d3-9d64-4fc501745712.png)

#### Uploading
Relay currently has entry level support for Images and GIFs. To send an image or GIF (which will be referred to only as Images from this point onward) click the Image Upload button as shown in the image above. To upload an image, select the file using the file selector that appears. When you're ready, press Upload. 
This will begin the file upload. Please allow a few moments for the upload to complete. The dialog will automatically disappear when the upload is complete and your message should appear in the group you're in. 

## Storage
### Where are my uploads stored?
Uploads are stored in a non-publically accessible AWS S3 bucket. This sits behind a Cloudfront instance that is public. Don't upload anything you don't want people to see. Files are hashed and the resulting hash is used for file names. This is to make sure that duplicate files are impossible to save on storage space. 
### Where are my text messages stored?
They are stored in a private MySQL database. Since this is a side project, DO NOT TRUST IT! Don't say anything you don't want to people to see currently. Again, this is NOT a commercial product but rather a tech demo of some full stack programming I have self-taught. 


## Help, Feature Requests or Support
Support for this application is not guarranteed at all. If you wish to help, need help with the app, have a feature request or would like to notify me of a bug you've spotted, message me through Relay! My username is `Ethan` (with the capital E). I have this app on my phone so I'll likely respond quickly to any messages you send me. Make sure to check back for a response!
