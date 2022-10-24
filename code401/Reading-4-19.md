# AWS: Events

## [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

1. SNS is a publish-subscribe system, so it sends messages to everyone on its list of subscribers. SQS is a queuing system, so receivers have to directly ask for messages instead of getting them sent automatically.

2. SNS works well when you have lots of recipients that might need a message processed in different ways. SQS works well for decoupling applications for asynchronus processing.

## [AWS SQS vs SNS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

1. SNS is used to send notifications of an event to multiple SQS queues, where they are safely stored and ready to be polled whatever service is connected to them. This keeps each of these services insulated from eachother.

2. The SNS sends a message out to each subscriber. If the subscriber is active, they receive the message; if they're not lostening, too bad.

## [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

1. By creating message groups, a queue can be split up so that each group can be processed in order, but items from different groups can be processed in parallel.
