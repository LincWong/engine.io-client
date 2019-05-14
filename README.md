# engine.io-client-weex

Developed based on `engine.io-client` and `weex.adapter.websocket`,The underlying webSocket implementation is replaced by the `weex` socket implementation.

# Docs

same as `engine.io-client` https://github.com/socketio/engine.io-client

# What changed

- Only support socket connection, remove polling transport support
- Replace the websocket implementation with `weex.adapter.websocket`，The details are as follows `·./lib/transports/websocket.js`

# Some products

- [socket.io-client-weex](https://www.npmjs.com/package/socket.io-client-weex)

# Reference materials
- https://github.com/stackOverMind/engine.io-client-weapp