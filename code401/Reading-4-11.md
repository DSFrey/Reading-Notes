# Event Driven Applications

## [Event Driven Programming](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)

1. [EventEmitter](https://nodejs.org/api/events.html#events_class_eventemitter) is a native node module used to incorporate event-driven programming.

2. >By registering event listeners we can actually reverse the flow of communication between our objects. Rather than on object needing to reach inside another object to trigger a function, our objects can just emit events and whichever objects are listening to those event will process it in the way they have been told to. The source of an objects behavior is now entirely contained within itself, rather than needing to be accessed by external objects.

3. Event-driven programming keeps our code muc cleaner by making it possible to keep our modules completely separate and focused on one task.
