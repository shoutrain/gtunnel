# gtunnel
`gtunnel` translate data flow from socket to socket, SSL encap/decap can be applied. This is a Golang implementation in replace of `stunnel`. We don't have the pain of using openssl library, and we benefit from go-routine which is lightweight and scalable.

`gtunnel` has to be very scalable, and measurement will be placed.

