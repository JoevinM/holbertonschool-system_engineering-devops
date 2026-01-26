# Web Infrastructure Design

## Table of Contents
- [Project Overview](#project-overview)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Resources](#resources)
- [Tasks](#tasks)

---

## Project Overview

This project focuses on understanding, designing, and explaining web infrastructures.
The goal is to be able to **design web stacks**, **explain each component**, and **identify weaknesses such as SPOF, security risks, and scalability limits**.

All tasks are based on **whiteboarding** and **conceptual explanations**, not coding.

This project is part of the **Foundations v2.1 – Part 3** curriculum.

---

## Learning Objectives

At the end of this project, you should be able to explain, without external help:

### General
- How a web infrastructure works from user request to response
- The role of each component in a web stack
- What a server is and how it communicates with clients
- The purpose of DNS and common DNS record types
- What a web server and an application server do
- How databases are used in web infrastructures
- What system redundancy is and why it matters
- Common infrastructure issues and limitations

### Concepts & Acronyms

- [Network basics](https://tomnomnom.com/talks/networking.pdf)
- [Server](https://www.techtarget.com/whatis/definition/Web-server)
- [Web Server](https://developer.mozilla.org/en-US/docs/Learn_web_development/Howto/Web_mechanics/What_is_a_web_server)
- [DNS](https://www.cloudflare.com/learning/dns/what-is-dns/)
- [Load balancer](https://www.networkacademy.io/ccna/network-fundamentals/load-balancer)
- [Monitoring](https://www.huntress.com/cybersecurity-101/topic/server-monitoring?utm_source=chatgpt.com)

---

## Requirements

### General
- A `README.md` file at the root of the project is mandatory
- All explanations must be written **in English**
- Each task must be **whiteboarded** (on paper or digital tool)
- A screenshot of each diagram must be uploaded to an image hosting service
- The image link must be included in the corresponding task file
- Tasks will be **manually reviewed**
- You must be able to explain each diagram orally during review
- Focus strictly on what is asked in each task
- Avoid unnecessary details unless explicitly requested

---

## Resources

Read or watch:
- [What is a database](https://www.techtarget.com/searchdatamanagement/definition/database)
- [What’s the difference between a web server and an app server?](https://www.youtube.com/watch?v=S97eKyv2b9M)
- [DNS record types](https://www.ibm.com/think/topics/dns-server)
- [Single point of failure](https://en.wikipedia.org/wiki/Single_point_of_failure)
- [How to avoid downtime when deploying new code](https://softwareengineering.stackexchange.com/questions/35063/how-do-you-update-your-production-codebase-database-schema-without-causing-downt#answers-header)
- [High availability cluster (active-active/active-passive)](https://docs.oracle.com/cd/E17904_01/core.1111/e10106/intro.htm#ASHIA714)
- [What is HTTPS](https://www.sectigo.com/blog/http-vs-https)
- [What is a firewall](https://www.webopedia.com/definitions/firewall/)

---

## Tasks

| # | Task name                           | Description                                                                 | File |
|---|------------------------------------|-----------------------------------------------------------------------------|------|
| 0 | Simple web stack                   | Design a one-server web infrastructure hosting www.foobar.com               | `0-simple_web_stack` |
| 1 | Distributed web infrastructure     | Design a distributed web infrastructure using a load balancer               | `1-distributed_web_infrastructure` |
| 2 | Secured and monitored infrastructure | Design a secured, encrypted, and monitored web infrastructure               | `2-secured_and_monitored_web_infrastructure` |
| 3 | Scale up                           | Design a scalable infrastructure with separated components                  | `3-scale_up` |

---
