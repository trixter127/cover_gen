---
title: Elb
---

# Elastic Load Balancer

### Types 
- Application Load Balancer
- Network Load Balancer
- Classic Load Balancer
- Gateway Load Balance - Load balancing for 3rd Party Virtual Services

| Type            | Protocol | Use Cases                  |
| --------------- | -------- | -------------------------- |
| **Application** | HTTP/S   | Web Server                 |
| **Network**     | TCP      | High Performance Work Load, Low Latency , Costly |
| **Classic**     | HTTP/S & TCP |        Old one                    |
 


Notes: 

- To get **Ipv4 Address** - Look for header named '**`X-Forwarded-For`**', available in HTTP/S protocol load balancers
- **504** Error - **Gateway Timed Out**  
