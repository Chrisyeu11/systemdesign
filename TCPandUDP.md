
📦 TCP (Transmission Control Protocol)
Connection-oriented: Establishes a connection before sending data (like a phone call).

Reliable: Guarantees all data arrives in the correct order.

Error checking: Yes — includes retransmission if data is lost.

Ordered: Data is reassembled in the correct order.

Slower: Extra overhead due to reliability features.

Examples: Web browsing (HTTP/HTTPS), email (SMTP), file transfer (FTP).

📦 UDP (User Datagram Protocol)
Connectionless: Sends data without a setup (like texting without a reply).

Unreliable: No guarantee data is received or arrives in order.

No error correction: Dropped packets are not resent.

Faster: Less overhead, useful for speed-critical apps.

Examples: Streaming (Netflix, YouTube), online gaming, VoIP (Zoom, Skype).

✅ Side-by-Side Comparison
Feature	TCP	UDP
Type	Connection-oriented	Connectionless
Reliability	Reliable (guarantees delivery)	Unreliable (no guarantee)
Speed	Slower	Faster
Ordering	Ensures correct order	No order guarantee
Use Cases	HTTP, FTP, Email	Streaming, Games, VoIP
