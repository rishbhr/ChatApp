# ChatApp
A chat application built to run on local instances, using javascript and socket.io.

The basic functionality was pulled from socket.io tutorial project here: https://socket.io/get-started/chat/#Introduction

The basic use cases of this project(goals and examples from socket.io site):
1. Add user tracking
  a. Display when users connect or disconnect
  b. Add support for basic nick names
  c. Find out who is typing a message
  d. Show who is currently using the application
2. Chat Functionality
  a. Currently the app sends the message to the user who sent it original, changes that to no
  b. Add private messaging
3. Add authentication
  a. Add abiltiy to create a user account
  b. Store details in a NoSQL instance
  c. Keep conversation logs for user reference
   -Keep conversation scrambled while server side
4. Add UI improvements
  a. Add tabs in window while private messaging


Socket.io is not a chat service base layer, but rather it is used to broadcast information from a provider to all consumers. This relay of information can be through many different means. Here we see it interfacing with a web application designed to eventually run as a standalone application.