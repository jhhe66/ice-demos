This demo illustrates the use of [Asynchronous Method Invocation (AMI)][1]
with a server that performs simple calculations and a client that can
call for the calculations without blocking.

To run the demo, first start the server:

```
java -jar build/libs/server.jar
```

In a second window, start the client:

```
java -jar build/libs/client.jar
```

[1]: https://doc.zeroc.com/display/Ice37/Asynchronous+Method+Invocation+%28AMI%29+in+Java
