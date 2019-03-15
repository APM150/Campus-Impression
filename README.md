# CodePath Group Project - Part I App Design

This is an iOS application that can help students locate campus resources expetidiously.

## App Name: Campus-Impression

## Description

We would like to build an iOS app, Campus Impression, that serves as an information booth and Q&A platform, and provides service tools to help incoming students integrate into the college community.  
A. Q&A Forum (main function)  
B. Housing  
C. Transportation  
D. Academic Resources (Main Function)

## App evaluation attributes

College life can be hard to begin with if students do not have sufficient knowledge about things happening around campus. International students stress the most by being in a different country to discover everything on their own. Although there are many existing helpful online resources, there is not a unified place for students to find out all resources at a time. Therefore, we want to make a app that help incoming students adapt to a new environment. Our app would provide some special features to have students interact with each other, such as allowing older students could sell their cars to first-year students and allowing students to initiate study groups via our app.

## User Stories

The sketching of our app design:
<img src='https://i.imgur.com/R8ZDplS.jpg?1' title='App Flow Walkthrough' width='' alt='App Flow Walkthrough' />

## Database Schema

Post: {author(user): PFobject, 
      image: url, 
      comments: Array of pointers,
      postedTime: Date,
      postTitel: String,
      tag: String,
      postContents: String,
      likes: Array of pointers}
     
User: {username: String,
      password: String,
      email: String}

Profiles: {user: PFObject,
          UCIEmail: String,
          gender: String,
          hometown: String,
          major: String,
          birthday: String}
      
Comments:{post: PFObject,
          text: String,
          author: PFObject,
          postedTime: Date}

Likes:{author: PFObject,
       post: PFObject}
       


      

## Video Walkthrough

Here's a walkthrough of user login/signup system (draft):

<img src='https://i.imgur.com/90b0Nde.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Here's a walkthrough of grade system (draft):

<img src='http://g.recordit.co/dvMlfZGrZW.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Here's a walkthrough of Tutor (draft):

<img src='https://github.com/JaksonLu/Campus-Impression/blob/master/Tutor.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Here's a walkthrough of Evaluation (draft):

<img src='http://g.recordit.co/qL2ez2sp7W.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Here's a walkthrough of user like and unlike post (draft):

<img src= 'https://github.com/JaksonLu/Campus-Impression/blob/master/Like%20Post.gif' />

Here is our primitive UI design:
https://drive.google.com/a/uci.edu/file/d/1vh5rzz-WRgS_ylPrS0PsUjWwCp8JORZQ/view?usp=sharing


