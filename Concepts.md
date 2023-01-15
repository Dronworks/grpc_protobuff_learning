## General concepts
### Callback from a server
To notify that server is processed our call there is a need to update a callback item.

We do callback(null, {some item}). The *null* means that we want the system to calculate the response length.
