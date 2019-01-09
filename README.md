1. run `ultrahook hook localhost:8800` - this sets to listen on `http://hook.parohy.ultrahook.com/`. This is added in test repo as webhook destination.
2. run `node server.js` - this is a simple express app listening to `localhost:8800` GET nad POST requests.

Ultrahook redirects requests from set github destiantion to localhost address.