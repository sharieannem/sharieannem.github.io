---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

## Developing an app with Meteor 

The first thing I thought about when I used Meteor was: "Wow this is complex!". I experienced a lot of frustration and confusion starting out (I can say that I still do) so allow me to share two little encounters that added to this pot of frustration, one of which has been overcomed (Thank goodness!) and the other I have yet to solve.

## First "Gotcha" - Unlocked

The application structure of a meteor app is very complex. There are client, server, and import subdirectories to name a few. It can be very hard to wrap your head around each directory's purpose when you are completely starting out with Meteor. Within those directories are files specific to their directory.
You know when you are developing an app and you are just creating and adding to files to create specific pages for your web applciations, it can be very hard to keep track of them. Then you start up Meteor and access your local host (localhost:3000) to look at where you are at in the development process and to fix any bugs that lie within your program. Then you come to a surprise when your changes do not appear and you frantically try to figure out why by searching the multiple files that you recently updated/created to solve the problem. 
I have had this problem once or twice in the beginning but the solution to it is VERY simple. It was just a matter of adding an import statement to an 'index.js' file! So if you are in a similar situation outlined above, examine your 'index.js' files and see if there is any missing import statements.

## Second "Gotcha" - Missing key

Afer fiddling with Meteor for a couple days and going through the standard process of creating a meteor app, calling 'meteor npm install' and 'meteor run' in the 'app' directory, I thought I had that figured out and stashed under my belt. But to my surprise, as I was working on an app for an assignment for my software engineering class, I invoked 'meteor npm install' then consequently 'meteor --settings ../config/settings.development.json' (which is similar to asking meteor to run on the local host but with a little added feature) and waited for a few minutes like any other run with meteor, it did not work! I ended up staring at the loading screen for a good hour while the command line was in the process of extacting a file. I tried looking up the extraction tool since forums have suggested that the tool used was for x36-bit systems rather than x64-bit systems (I had a 64-bit system) but I could not find it. To this day, I am still troubled by this problem.
