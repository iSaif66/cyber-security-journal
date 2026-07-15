# Topic Name
TCP/IP Networking Fundamentals
## 🎯 Goal
To understand how the TCP/IP model works and compare it with the OSI model.
## 📚 Theory
The TCP/IP model is the networking model used by the Internet today. It provides the protocols and architecture required for communication between devices across networks.
## 📝 Notes
- This model consists of 4 layers and it has an updated version which has 5 layers (Just splittef the "Link layer" into "Data Link & Physical").
- Each layer has the same function as the OSI Model.
-> Application Layer : Process To Process Communication (The layer a user deals with).
-> Transport(Data Flow using TCP/UDP) : Host To Host Communication, has the responsible of making data into packets to transfer it.
-> Internet : Internet Layer: Responsible for logical addressing and routing packets using IP.
-> Link Layer: Responsible for communication within the local network using MAC addresses and physical media.
- Difference between TCP & UDP:
-> TCP is more reliable and it has handshake feature so it's more accurate but slower, otherwise the UDP Protocol it's faster but less reliable.

## 💻 Commands

ping (IP Address).

## 🧪 Labs

TryHackMe - Introduction to Networking (Completed)

## ❓ Questions

None

## 🔗 Resources

- Professor Messer.
- CloudFlare Documentation.
- THM Lab.

## 📌 Summary
The TCP/IP model is the practical networking model used on the Internet today, while the OSI model serves mainly as a conceptual reference for understanding networking.