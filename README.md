# engineering-reference

Curated documentation for backend, infrastructure, systems, and security engineers. - Rubén Martínez Agramunt (Rub3cK0r3)

No tutorials.  
No blogs.  
Official docs, specs, RFCs, and postmortems.

---

## Philosophy

* Official documentation > blog posts  
* RFCs > Medium articles  
* Man pages > YouTube  
* Postmortems > hype  

If I’m not using it in production or while debugging, it doesn’t belong here.  
Focus on **authoritative, reproducible, and maintainable sources**.

---

## Languages

### Go

* https://go.dev/doc/  
* https://pkg.go.dev/std  
* https://go.dev/ref/spec  
* https://go.dev/doc/effective_go  
* https://go.dev/ref/mod  
* https://pkg.go.dev/testing  

### Rust

* https://doc.rust-lang.org/book/  
* https://doc.rust-lang.org/std/  
* https://doc.rust-lang.org/reference/  
* https://doc.rust-lang.org/nomicon/  
* https://docs.rs/  

### C++

* https://en.cppreference.com/w/  
* https://isocpp.org/std/the-standard  
* https://godbolt.org/  

### C

* https://man7.org/linux/man-pages/  
* https://en.cppreference.com/w/c  
* https://pubs.opengroup.org/onlinepubs/9699919799/  

### Python

* https://docs.python.org/3/  
* https://docs.python.org/3/library/index.html  
* https://docs.python.org/3/reference/  
* https://peps.python.org/  

### Java

* https://docs.oracle.com/en/java/javase/21/docs/api/  
* https://docs.oracle.com/javase/specs/  
* https://openjdk.org/projects/  

### Bash / Shell

* https://www.gnu.org/software/bash/manual/bash.html  
* https://mywiki.wooledge.org/BashGuide  
* https://www.tldp.org/LDP/abs/html/  

### JavaScript / Node.js

* https://developer.mozilla.org/en-US/docs/Web/JavaScript  
* https://nodejs.org/api/  

---

## Databases

### PostgreSQL

* https://www.postgresql.org/docs/current/  
* https://www.postgresql.org/docs/current/mvcc.html  
* https://www.postgresql.org/docs/current/transaction-iso.html  
* https://www.postgresql.org/docs/current/indexes.html  
* https://www.postgresql.org/docs/current/using-explain.html  
* https://www.postgresql.org/docs/current/explicit-locking.html  
* https://wiki.postgresql.org/wiki/Performance_Optimization  

### Redis

* https://redis.io/docs/latest/  
* https://redis.io/docs/latest/develop/use/patterns/  

### Additional DBs

* MySQL: https://dev.mysql.com/doc/  
* MongoDB: https://www.mongodb.com/docs/  
* Cassandra: https://cassandra.apache.org/doc/latest/  

---

## HTTP / Protocols / RFCs

* RFC 9110 — HTTP Semantics: https://www.rfc-editor.org/rfc/rfc9110  
* RFC 9111 — HTTP Caching: https://www.rfc-editor.org/rfc/rfc9111  
* RFC 8446 — TLS 1.3: https://www.rfc-editor.org/rfc/rfc8446  
* RFC 7519 — JSON Web Token: https://www.rfc-editor.org/rfc/rfc7519  
* https://www.rfc-editor.org/  

---

## Security

### OWASP

* OWASP Top 10: https://owasp.org/www-project-top-ten/  
* OWASP Cheat Sheet Series: https://cheatsheetseries.owasp.org/  

### Offensive / Defensive

* PortSwigger Web Security Academy: https://portswigger.net/web-security  
* MITRE ATT&CK: https://attack.mitre.org/  
* CWE — Common Weakness Enumeration: https://cwe.mitre.org/  

### Standards

* NIST CSF & Publications: https://csrc.nist.gov/publications  
* ISO/IEC 27001: https://www.iso.org/isoiec-27001-information-security.html  

---

## Linux / Systems

* Linux man pages: https://man7.org/linux/man-pages/  
* systemd: https://www.freedesktop.org/software/systemd/man/  
* nftables: https://wiki.nftables.org/wiki-nftables/index.php/Main_Page  
* iptables: https://ipset.netfilter.org/iptables.man.html  
* OpenSSL Docs: https://www.openssl.org/docs/  
* Linux Kernel Documentation: https://www.kernel.org/doc/html/latest/  

---

## Containers / Orchestration

* Docker Documentation: https://docs.docker.com/  
* Docker CLI Reference: https://docs.docker.com/engine/reference/commandline/docker/  
* Kubernetes Official Docs: https://kubernetes.io/docs/home/  
* CRI-O / containerd references: https://cri-o.io/  

---

## Observability / Monitoring

* Prometheus: https://prometheus.io/docs/  
* OpenTelemetry: https://opentelemetry.io/docs/  
* Grafana: https://grafana.com/docs/  
* ELK Stack Docs: https://www.elastic.co/guide/index.html  

---

## Testing / Performance

* k6 — Load Testing: https://k6.io/docs/  
* Criterion.rs — Benchmarking in Rust: https://criterion.rs/book/  
* pytest Documentation: https://docs.pytest.org/en/stable/  
* JMeter: https://jmeter.apache.org/usermanual/index.html  

---

## Networking

* TCP/IP Guide: http://www.tcpipguide.com/free/index.htm  
* IANA Port Assignments: https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml  
* Wireshark Docs: https://www.wireshark.org/docs/  
* BPF / eBPF Reference: https://www.kernel.org/doc/html/latest/bpf/index.html  

---

## Incident Postmortems

* Cloudflare Engineering Postmortems: https://blog.cloudflare.com/tag/postmortem/  
* Google SRE Book Postmortems: https://sre.google/sre-book/table-of-contents/  
* GitHub Engineering: https://github.blog/category/engineering/  
* Netflix Postmortems: https://netflixtechblog.com/tagged/postmortem  

---

> Python is the base for backend, automation, DevOps, and security. Use **only standard library and official docs**. Avoid tutorials or blogs. Focus on **full control of code**, separating business logic, data access, and server. Key modules: `http.server`, `socket`, `ssl`, `asyncio`, `json`, `urllib`, `sqlite3`, `threading`, `multiprocessing`, `os`, `pathlib`, `subprocess`, `logging`, `hashlib`, `secrets`. Enough for APIs, pipelines, security tools, and automation. Extend with C/Rust only for extreme performance; core remains Python.  

> **Use frameworks as libraries, not architecture.** Keep business logic independent. Frameworks are delivery tools, not the core of the system.
