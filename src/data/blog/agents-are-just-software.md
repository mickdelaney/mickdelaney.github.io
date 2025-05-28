---
author: Sat Naing
pubDatetime: 2025-05-28T15:22:00Z
modDatetime: 2025-05-28T15:22:00Z
title: Agents Are Just Software
slug: agents-are-just-software
featured: true
draft: true
tags:
  - agents
description:
  Agents Are Just Software Why the Next Wave of AI Is Really a Distributed-Systems Story.
---

We’re drowning in hype, but if you peel back the curtain every “AI agent” is just a process that reads messages, does work, and sends messages back. 

Distributed systems 101.

Your boss says to ship a chatbot to handle those simple customer service queries. 
Its a single bot with list of static text documents, all good. No state, easy to scale. 

But then it needs to look up records in a database, then it needs translate for customers in a different language, then it needs to a query through to an api. 

So the concensus is clear, more chatbots or should I say Agents...


## Agents

[Accoring to IBM](https://www.ibm.com/think/topics/ai-agents) refers to a system or program that is capable of autonomously performing tasks on behalf of a user or **another system**.

Ultimatey with our engineering hat on we can view AI Agents as just systems, services or gasp microservices !!

Therefore given the need to get them to talk to each other, or **colaborate**, we'll end up with the same problems as getting fleets of microservices, or systems to talk to each other.



<figure>
  <img
    src="https://images.pexels.com/photos/159618/still-life-school-retro-ink-159618.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
    alt="Free Classic wooden desk with writing materials, vintage clock, and a leather bag. Stock Photo"
  />
    <figcaption class="text-center">
    Photo by <a href="https://www.pexels.com/photo/brown-wooden-desk-159618/">Pixabay</a>
  </figcaption>
</figure>


## Agentic Pattern & Distributed Systems

| Agentic Pattern    | Implementation | Distributed Systems | Runtime Concerns |
| ------------------ | -------------- | ------------------- | ---------------- |
| Prompt Chaining    | Synchronous API calls in a single process | required |
| **_title_**        | Title of the post. (h1) | required |

