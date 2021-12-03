## Source of sources

hqserver and client from <https://zeromq.org/get-started/?language=nodejs&library=zeromqjs#>


## Installation 

Froms <https://zeromq.org/download/>

```
npm install zeromq@6.0.0-beta.6 --zmq-shared
``` 

## Server

```
➜  0mq-the-guide git:(master) ✗ node hwserver.js 
Received : [Hello]
Received : [Hello]
Received : [Hello]
Received : [Hello]
Received : [Hello]
Received : [Hello]
Received : [Hello]
Received : [Hello]
Received : [Hello]
Received : [Hello]
```

## Client

```➜  0mq-the-guide git:(master) ✗ node hwclient.js 
Connecting to hello world server…
Sending Hello  0
Received  World 0
Sending Hello  1
Received  World 1
Sending Hello  2
Received  World 2
Sending Hello  3
Received  World 3
Sending Hello  4
Received  World 4
Sending Hello  5
Received  World 5
Sending Hello  6
Received  World 6
Sending Hello  7
Received  World 7
Sending Hello  8
Received  World 8
Sending Hello  9
Received  World 9
```