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
It's a single bot with list of static text documents. All good, no state, easy to scale. 

But then the requirement expands and we need to look up records in a database, translate for customers in a different language, query through to an api.

The bot becomes a jack-of-all-trades with no clear structure. It juggles roles and context all at once, and you start to feel the strain in a few clear ways:

- Flows become harder to debug and maintain
- Prompts get longer and harder to manage
- It’s unclear which part of the bot is responsible for what
- Adding a new use case risks breaking what’s already working

That single-agent model starts to fall apart.

We need to extract out the responsibilities into multiple specialized agents. 

Each agent is focused on a single task — planning, research, data fetching, user interaction etc

Each service is easier to develop, debug, test etc. 

The concensus is clear, more chatbots or should I say Agents, or should I say Services...


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

