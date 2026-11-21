<p align="center">
  <img src="./banner.svg" alt="Udap Kharka: backend engineer building event-driven systems in Bhutan. Messages cross a chain bridge between two dzongs at dusk." width="100%">
</p>

<p align="center">
  <b>Kuzuzangpo la!</b> 🙏🇧🇹<br>
  <i>I build backend systems that talk in events, from the Land of the Thunder Dragon:<br>
  services that publish facts, consume them reliably, and keep working when a message crosses the bridge twice.<br>
  These days the services include AI agents: they read the knowledge base, call real tools, and ask a person before they act.</i>
</p>

<br>

### 📿 The mani wall so far

Every turn of a prayer wheel sends its prayer out one more time. That's at-least-once delivery, so my stack lives on a mani wall:

<p align="center">
  <img src="./wheels.svg" alt="A row of prayer wheels, one per technology: TypeScript, Node.js, NestJS, PostgreSQL, Redis, Docker, NATS JetStream and DDD turning; CQRS, Event Sourcing and Outbox still being learned" width="100%">
</p>

<br>

### 🤖 Agents that ask before they act

I work on a multi-tenant agentic AI platform, where agents get a knowledge base, real tools and a person in the loop:

```
request → agent runtime ──┬─ RAG    pgvector + full-text, fused with RRF
         tenant · role    ├─ LLM    Claude · Gemini · OpenAI-compatible
                          └─ tools  side effect? → human approval → audit log
```

<br>

### 🏹 Arrows that missed

Archery is Bhutan's national sport. My misses:

> `×1` **At-least-once means at-least-twice.** Make every consumer idempotent.<br>
> `×2` **Write to the database and the broker separately, and one will fail.** Use an outbox.<br>
> `×3` **An LLM is a dependency, not an oracle.** Put it behind an interface.<br>
> `×4` **Never let an agent hold the keys.** It proposes, a person approves.

<br>

### 🌶️ Still simmering

```
$ nats sub "druk.udap.learning.>"
[#1] event-sourcing   rebuilding state from the log, not the table
[#2] agents           tools, RAG and human approval
[#3] evals            did the agent get better, or just different?
```

<details open>
<summary><b>🏯 Dzong config: what I run on</b></summary>
<br>

**Build:** NestJS · TypeScript · Node.js · GraphQL<br>
**Store:** PostgreSQL · Redis · Prisma · TypeORM<br>
**Move:** NATS JetStream · Redis Streams · Kafka · BullMQ<br>
**Think:** Vercel AI SDK · Anthropic Claude · Google Gemini · OpenAI-compatible APIs · pgvector · RAG · tool calling<br>
**Stream:** Socket.IO · WebSockets · Next.js<br>
**Ship:** Docker · AWS · Nginx · Linux<br>
**Document:** Swagger · Postman

**Patterns:** event-driven architecture · CQRS · event sourcing · outbox · microservices · domain-driven design · clean architecture · agentic workflows · retrieval-augmented generation · human-in-the-loop

</details>

<details open>
<summary><b>🐍 Contribution log</b></summary>
<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Udap-10/Udap-10/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Udap-10/Udap-10/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/Udap-10/Udap-10/output/github-contribution-grid-snake-dark.svg" />
</picture>

</details>

<br>

<p align="center">
  <a href="https://linkedin.com/in/udap-kharka-456167376">💼 LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:udapkharka64@gmail.com">✉️ udapkharka64@gmail.com</a>
</p>

<p align="center"><sub><i>Tashi Delek 🙏 Build systems that scale, write code that lasts, and optimise for Gross National Happiness: fewer 2 a.m. pages for everyone.</i></sub></p>
