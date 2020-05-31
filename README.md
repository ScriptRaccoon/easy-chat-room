# Chat Room

This chat room is mainly a demonstration of how Node.js, express and socket.io work.

You can check it out at one of these places:

-   https://qc51c.sse.codesandbox.io/
-   https://easy-chat-room.herokuapp.com/

In the login screen, you can see how many users are currently in the room. Then you login with a name, which goes through a basic validation.

Each message has a time stamp and is colored by the user's color, which is generated randomly during the login.

The room has a header which displays the current users. When you click on one of them, you can send a private message to that user. You can also send group messages like that.

The header also has a topic can be set by all users.

The ChatBot informs about new and leaving users. He also kicks users when they are spamming and even bans them after three kicks, using [this](https://www.npmjs.com/package/socket-anti-spam) package.
