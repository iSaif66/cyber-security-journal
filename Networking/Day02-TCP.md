# Topic Name
TCP/IP Model

## 🎯 Goal
- To understand the difference between TCP/IP model and OSI model

## 📚 Theory
TCP/IP Model is the model which internet is using nowadays because it's more user-friendly.
## 📝 Notes
- This model consists of 4 layers and it has an updated version which has 5 layers (Just splittef the "Link layer" into "Data Link & Physical").
- Each layer has the same function as the OSI Model.
-> Application Layer : Process To Process Communication (The layer a user deals with).
-> Transport(Data Flow using TCP/UDP) : Host To Host Communication, has the responsible of making data into packets to transfer it.
-> Internet : Adds IP Header to the data transfered using IP addresses.
-> Link : MAC Adresses & Physical Components.
- Difference between TCP & UDP:
-> TCP is more reliable and it has handshake feature so it's more accurate but slower, otherwise the UDP Protocol it's faster but less reliable.

## 💻 Commands

ping (IP Address).

## 🧪 Labs

THM (introduction to Networking).

## ❓ Questions

None

## 🔗 Resources

- Professor Messer.
- CloudFlare Documentation.
- THM Lab.

## 📌 Summary
-TCP/IP Model is similar to OSI model but with wider range of connections.
-OSI is still used by engineers when it comes to understanding how networks works.