# my-camel-app Documentation

A my-camel-app


## Testing

Use the broker's console to send message to the correct queue. You can use the following payload:

Single line:
----
{"message": "hello", "color": "orange", "pet": "cat"}
----

Multiple Lines:
----
[
{"message": "hello", "color": "orange", "pet": "cat"},
{"message": "aloha", "color": "green", "pet": "dog"}
]
----