
# Socket.IO Chat - edgeless edition

A simple chat demo for socket.io

## How to use

```
$ npm install
$ npm start
```

And point your browser to `http://localhost:3000`. Optionally, specify
a port by supplying the `PORT` env variable.

## Features

- Multiple users can join a chat room by each entering a unique username
on website load.
- Users can type chat messages to the chat room.
- A notification is sent to all users when a user joins or leaves
the chatroom.

## Edgeless features
- After sending "count" message, user count is displayed
- After each 5 seconds, server emits same Math.random() number for all connected users
- After typing "secret" user joins secret channel and his messages are only seen by other secret channel users
