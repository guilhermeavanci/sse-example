# SERVER SENT EVENTS (SSE) EXAMPLE

Using `node` and `express`.

## Install dependencies

```
npm i
```

## Run

```
node server.js
```

The server must be running on port `3000`.

## Testing

### Browser

You can see it working on the browser accessing http://localhost:3000/.

### CLI

You can also check the events on your terminal running:

```
curl localhost:3000/stream
```

# Source

Based on [Josh](https://github.com/Josh-Weston)'s and [Ggorlen](https://ggorlen.github.io/)'s answers to this [Stackoverflow question](https://stackoverflow.com/questions/34657222/how-to-use-server-sent-events-in-express-js).
