# Chatty App

App intended to connect to users to establish a chat using TCP protocol.

Should have an encrypted communication with an asymetric key

## Planned flow of the app

- User opens the client
- User inserts his username
- Server checks if username is currently in use
- Server and client establish a TLS handshake
- Client gets messages
- Client can push messages
- Server receives message and updates the messages for every client