## General concepts
### Callback from a server
To notify that server is processed our call there is a need to update a callback item.

We do callback(null, {some item}). The *null* means that we want the system to calculate the response length.

### What endpoints are GRPC available?
To see what endpoints are available type in console `grpcurl --plaintext localhost:9090 list`

### What method available on endpoint?
To see what methods are available type in console `grpcurl --plaintext localhost:9090 list <endpoint name>`

### To send message to gRpc server
Type in console `grpcurl --plaintext - '{"message": "how are you"}' localhost:9090 <endpoint name>/<method name>`
