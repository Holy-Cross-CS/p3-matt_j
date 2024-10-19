CSCI 356 Fall 2024 Project 3 Starter Code
-----------------------------------------

Collaboration Note:
I did not work with any classmates on this assignment
I went on geeksforgeeks.org and w3schools.com to find code related
   to type casting and list functions such as append() for proper syntax

This repository contains starter code for project 3, in which you will implement
the whisper web app. 

* `web_files` - The files implmenting the client half of the whisper app.

Tasks:

- [x] implement the client half of the whisper app
- [x] add webserver.py for the server half, borrowing from earlier project
   - [x] print the appropriate URL for whisper app to console
- [x] handle GET for topic list
   - [x] handle version 0 as a temporary stop-gap
   - [x] handle version 1 as a temporary stop-gap
   - [x] handle any version N, the general case, with proper wait/notify\_all
   - [x] return appropriate errors if topic not found or other errors
- [x] handle POST for messages
   - [x] return appropriate errors if request is malformed or other errors
- [x] handle GET for topic message feed
   - [x] handle any version N, with proper wait/notify\_all
   - [x] return appropriate errors if topic is not found or other errors
- [x] handle POST for liking a topic
   - [x] return appropriate errors if topic is not found or other errors
- [ ] reach goal: topics are sorted by some criteria
- [x] reach goal: limit each topic to only the most recent messages
      Only the 10 most recent messages will be printed
- [x] reach goal: implement downvoting/removal of messages
      If a message is "removed" it will print "(This message was removed)" when messages are displayed
- [ ] reach goal: implement other features, e.g. using cookies, etc.
- [x] project still does not use HTTP related python libraries or modules
- [x] does not crash under normal usage
- [x] Update README.md to describe final state of project, collaboration, etc.
