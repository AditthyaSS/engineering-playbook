# WebSockets – Engineering Playbook

This folder documents my learning and hands-on simulation of **WebSockets**, focusing on how real-time, bidirectional communication works between a client and a server.

The goal of this entry is to explain WebSockets **conceptually** and **practically**, using a minimal runnable example.

---

## 📌 What are WebSockets?

WebSockets provide a **persistent, full-duplex communication channel** between a client and a server over a single TCP connection.

Unlike traditional HTTP request–response communication, WebSockets allow **both the client and the server to send data at any time**, enabling real-time applications.

---

## 🔄 How WebSockets Work

1. The client initiates a connection using **HTTP or HTTPS**.
2. A **WebSocket handshake** request is sent.
3. If the server accepts, the protocol is **upgraded to WebSocket**.
4. A persistent connection is established.
5. Real-time, bidirectional communication begins.

> HTTP is used only for the handshake.  
> WebSocket handles all real-time communication.

---

## 🖼️ Architecture Diagram

![WebSockets Basics](sockets.png)

---
⚡ What Makes This Real-Time?

The connection remains open

Messages are sent immediately when events occur

The server can push data without waiting for a request

Real-time refers to event-driven, low-latency communication, not whether messages are hard-coded.

🧠 Key Takeaways

WebSockets enable real-time, two-way communication

HTTP is used only for the initial handshake

One persistent connection replaces repeated HTTP requests

Ideal for chat apps, live dashboards, games, and streaming data

📚 Why This Exists

This repository is part of my Engineering Playbook, where I:

Learn concepts daily

Simulate them with runnable code

Document understanding with diagrams and explanations

The focus is on clarity, correctness, and consistency.
