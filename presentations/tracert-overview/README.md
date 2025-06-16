# Understanding and Using the `tracert` Command

📅 **Date:** Spring 2025  
🎓 **Course:** CSIA 330 – Wireless Security  
🎥 **Presentation Link:** [Watch on YouTube (Unlisted)](https://www.youtube.com/watch?v=6eMa3iE3vSc&list=PLRX0EcV0YK7poUuMPa5CTAkxD_I7qLKIv&index=6)

## 🧠 Overview

This presentation provides a comprehensive look at the `tracert` command (short for "Trace Route") — a command-line utility used to trace the path data takes across a network. With both explanation and a live demonstration, this presentation shows how `tracert` helps diagnose slow or failing internet connections.

## 🔑 Key Topics Covered

- **What is `tracert`?**  
  A command-line tool that maps the route data packets take from your device to a remote destination.

- **How It Works**  
  - Utilizes Time-To-Live (TTL) values to trace each hop in the path  
  - Each "hop" is a router or network node the packet passes through  
  - Results include hop number, response times (ms), and IP/hostname  

- **Interpreting Output**  
  - *Hop Number*: Step in the path  
  - *Response Time*: Indicates latency at each hop  
  - *Timeouts* (`* * *`): Blocked or failed responses  

- **Common Use Cases**  
  - Troubleshooting slow connections  
  - Identifying ISP bottlenecks  
  - Diagnosing unreachable websites  
  - Comparing routing across different networks  

- **Live Demonstration Highlights**  
  - Running `tracert google.com`  
  - Analyzing router responses and identifying delays  
  - Explaining real-time output for education and diagnostics

## ✅ Takeaways

The `tracert` command is a powerful tool for diagnosing internet issues and understanding how data flows through networks. It's useful for both casual users and professionals, offering insights into where slowdowns or failures occur.

---

**Created by:** Sam Mendez  
**Format:** Video presentation with live command-line demo and supporting slides  
