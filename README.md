# ChatApp
A chat application built to run on local instances, using javascript and socket.io.

The basic functionality was pulled from socket.io tutorial project here: https://socket.io/get-started/chat/#Introduction

## The basic use cases of this project(goals and examples from socket.io site):
1. Add user tracking
  - [ ] Display when users connect or disconnect
  - [ ] Add support for basic nick names
  - [ ] Find out who is typing a message
  - [ ] Show who is currently using the application
2. Chat Functionality
  - [ ] Currently the app sends the message to the user who sent it original, changes that to no
  - [ ] Add private messaging
3. Add authentication
  - [ ] Add abiltiy to create a user account
  - [ ] Store details in a NoSQL instance
  - [ ] Keep conversation logs for user reference
4. Add UI improvements
  - [ ] Add tabs in window while private messaging


Socket.io is not a chat service base layer, but rather it is used to broadcast information from a provider to all consumers. This relay of information can be through many different means. Here we see it interfacing with a web application designed to eventually run as a standalone application.