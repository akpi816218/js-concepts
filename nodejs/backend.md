# backend

*Backend* and *frontend* are two different terms that developers hear often, especially when building a web app. Simply put, the backend is the server-side program, and the frontend is the client-side program.

A project's backend (also called a server) can be written in many languages. This repository favors [Node.js](../). However, it may be written in Python, C#, Java, PHP, or Ruby, among countless others. The frontend is frequently written in HTML and JavaScript, though others can be used.

A server or backend is frequently used in multiplayer games. Players' browsers send data to the server, which in turn sends the data to all the players. This form of communication frequently uses [WebSocket](./ws)s. Users interact with the frontend, which manages their connection to the server, and in this case, displays a game. **Note:** For the web app to work, the server must be constantly running as to provide 100% uptime for its users.

HTTP/REST APIs also depend on backend servers. While API users seldom need to worry about the server, it is good to know what goes on behind the scenes. When a client (or another server) queries an API, the server goes through multiple steps before responding. First, it processes the request and decides how to respond based on the path and query parameters. Next, it calls the appropriate callback or handler to deal with the request. The handler function does something (i.e. reads or writes to a database) and responds accordingly (i.e. with read data or status of write).
