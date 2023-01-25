# websocket

WebSockets are a convenient way for servers to communicate with remote clients. WS enables real-time communication with connected computers.

The process of WebSocket is simple. A server registers handler functions for specific events. When a user connects, it serves a webpage, which creates a WebSocket connection with the server and registers its own handlers for the same events. When it needs to talk to the server, the client-side script emits a certain event. The server, upon recieving the event, calls its own handler function. In the case of a multiplayer game, the callback function emits the event to all the connected clients, effectively acting as a relay device.

Recommended WebSocket libraries for Node.js:

- [ws](https://www.npmjs.com/package/ws): This is the most popular on NPM and is also used by reputable projects like [Discord.js](https://discord.js.org).
- [WebSocket](https://www.npmjs.com/package/websocket)
- [Socket.io](https://socket.io): This is probably the simplest to get started with.
