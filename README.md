# Multithreaded Chat App (Java)

This is a console-based group chat app I built in Java using **sockets and threads**. It’s kinda like the OG WhatsApp… but only in your terminal 😄

### 💡 What it does:
- Starts a server that accepts multiple clients
- Each client connects and can chat in real-time
- Server broadcasts each message to all connected clients

### 🔍 What’s inside:
- `ServerMain`: Starts the server and listens for connections
- `ClientHandler`: Runs in its own thread for each user
- `MessageBroadcaster`: Sends incoming messages to all clients
- `ClientMainone`, `ClientMaintwo`: Basic client UIs (you can run multiple)

### ⚙️ Tech used:
No libraries. Just **pure Java** using `Socket`, `ServerSocket`, `Thread`, etc.

### 👨‍💻 How to use it:
1. Start the server by running `ServerMain`
2. Then launch `ClientMainone` and/or `ClientMaintwo` (open multiple terminals)
3. Start chatting — all messages are shared in real-time

---

This was my way of understanding how real-time chat and multithreading works in Java. If you’re learning threads, sockets, or networking — you’ll definitely learn something by poking around.
