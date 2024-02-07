# Gurukul-Material

## Threads
- [ ] Lazy Threads
- [ ] How do you know communications between threads are acknowledged by each other
- [ ] CSP - Communicating Sequential Processes (*Golang channels*)
- [ ] Busy wait and weight lock 
- [ ] Run level (0,2,3,4,5)
	- [ ] Switch between run levels and init config
- [ ] How does a crashed app get restarted by *init process*
- [ ] How do *daemons* stay up? How are they revived if killed?
- [ ] Login threads and processes - what happens from startup to login screen?
	- [ ] *Login Manager* (runs at root) -> privileges because it has access to credentials
	- [ ] Privilege change (occurs at root)
	- [ ] Login (*fork call* for spawning processes and exec call)
- [ ] Kernel space vs User space during login and boot up
- [ ] Exec replaces a running process with image of process to change it
- [ ] How are child processes and child daemons linked to each other
- [ ] Dynamically linked libraries and statically linked libraries
## Networking
- [ ] ICMP
- [ ] Public vs Private IPs
- [ ] Routing table - path length calculation 
	- [ ] Multiple links in routing
	- [ ] How 'lookup' works - the bits required for *lookup* [*routing algorithms*]
- [ ] TCP priority -> how time sensitive/important data has priority defined to drop a TCP packet that is not high priority
	- [ ] Cannot fool a router
	- [ ] How do routers know priority
- [ ] ICMP block
- [ ] OSI in theory has clear separation, but in reality has overlap. Why?
- [ ] TCP algorithms - TAHOE, RENO, FastStart etc.
- [ ] HTTP/3 - UDP algorithm - *Quic*
- [ ] Keep-alive - overhead of creating new connection avoided (HTTP/1.1)
- [ ] *2616 HTTP/1.1 RFCs -> IETF publishes*
- [ ] Bandwidth and latency not related (slow-start algorithm example)
- [ ] sll, dll, AOT and JIT, .NET in JIT
- [ ] C being commonality between most HLL
## Garbage Collector
- [ ] Working
- [ ] Types
	- [ ] *Pause the world*
	- [ ] *Pauseless (AZUL)*
- [ ] Stack vs Heap memory
	- [ ] *Stacktrace*
- [ ] *Class bytecode* modification (Java)
- [ ] Maximum arguments passed to a method in Java
- [ ] No compaction in C/C++ and can be manually changed
- [ ] graalvm - no garbage collection
- [ ] *Reference object* - pointer in Java -> moves locations without programmers knowing (because C/CPP has pointers but java doesn't)
# Sent by Mentors
[Idea Keymaps](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
[UUID vs ULID](https://medium.com/@sammaingi5/uuid-vs-ulid-how-ulid-improves-write-speeds-d16b23505458#:~:text=For%20example%2C%20ULIDs%20are%20more,work%20with%20in%20certain%20situations.)
[How we built Pingora, the proxy that connects Cloudflare to the Internet](https://blog.cloudflare.com/how-we-built-pingora-the-proxy-that-connects-cloudflare-to-the-internet/)
[ScyllaDB Internals](https://www.youtube.com/watch?v=AqY13RjWwJg&t=1375s)
[SeaStar](https://seastar.io)
[Thread per Core Architecture](https://drive.google.com/file/d/1EJHkuxRJMxK_yFQpUftKW8LaFr2SQDSC/view)
[In memory columnar data structures](https://entzik.medium.com/a-case-for-in-memory-columnar-data-structures-44ddb20c2c69)
[Why single-threaded Redis is fast](https://levelup.gitconnected.com/4-reasons-why-single-threaded-redis-is-so-fast-414e0106f921)
[TraceRoute](https://www.fortinet.com/resources/cyberglossary/traceroutes)
[Reading TraceRoute results](https://www.varonis.com/blog/what-is-traceroute)
[Evolution of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Evolution_of_HTTP#invention_of_the_world_wide_web)
[SO_REUSE in TCP](https://blog.flipkart.tech/linux-tcp-so-reuseport-usage-and-implementation-6bfbf642885a)
[Journey of a request to the backend](https://medium.com/@hnasr/the-journey-of-a-request-to-the-backend-c3de704de223)
# Extras
[Why Stack so fast](https://www.youtube.com/watch?v=N3o5yHYLviQ)
[Exploring CoRoutines](https://www.youtube.com/watch?v=jT2gHPQ4Z1Q)
[Database Internals](https://github.com/Akshat-Jain/database-internals-notes)


