🔤 What is DNS?
DNS = Domain Name System

Purpose: Converts domain names (like google.com) into IP addresses (like 142.250.72.206)
→ Like a phonebook for the internet.

🧭 How DNS Works (Step-by-Step)
You type a website (e.g., example.com)

Browser checks local DNS cache

If not found, it asks the Recursive Resolver

Resolver asks:

Root Server → points to TLD server (.com, .org, etc.)

TLD Server → points to authoritative name server for the domain

Authoritative Name Server → gives the correct IP address

IP is returned to browser

Browser uses the IP to access the website

📂 Types of DNS Servers
Server Type	Role
Recursive Resolver	Finds the IP for the browser
Root Server	Directs to TLD
TLD Server	Directs to domain’s name server
Authoritative Name Server	Final answer (IP address)
🧠 Extra Notes
Caching: Saves past lookups to speed up future ones.

DNS Propagation: Takes time when domain records are updated.

DNS Spoofing: A security attack tricking DNS into sending wrong IPs.

✅ TL;DR:
DNS = name → IP

Works in layers: Resolver → Root → TLD → Authoritative → IP

It’s fast because of caching

It’s important for every internet request

