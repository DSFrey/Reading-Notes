# Message Queues

## [Socket.io Chat Example](https://socket.io/get-started/chat/)

1. It creates a connection between a client and a server that allows text to be passed back and forth between them.

2. Console logs record when a user connects or disconnects as well as when a message is sent.

3. Broadcast sends an event to everyone except the sender.

## [Rooms](https://socket.io/docs/v4/rooms)

1. A room is a channel that sockets can join and leave.

2. `socket.join('room name')` joins a room

3. `socket.leave('room name')` leaves a room

## [Namespaces](https://socket.io/docs/v4/namespaces/)

1. >A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection

2. Each namespace as its own event handlers, rooms, and middlewares.

3. If some functionality is only supposed to be available to authorized users, a namespace can separate that logic from the rest of the app.
