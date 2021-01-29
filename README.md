# websocket-Server-Client-Chat
Chat application build for Multiple clients and single server. Uses Websocket to have real time 2way connection to the server

Room messaging server implementation that is using a bidirectional RPC
protocol to implement chat-like communication. Designed to handle
common public network messaging problems like reliable delivery,
multiple connections from a single user, real-time permissions and
presence. RPC requests processing and a room messages format are
customisable via hooks, allowing to implement anything from a
chat-rooms server to a collaborative application with a complex
conflict resolution. Room messages also can be used to create public
APIs or to tunnel M2M communications for IoT devices.
