# Hi, I'm Pawan 👋

I'm a backend engineer in Mangalore, India. For the past 2.5 years I've been building and running serverless systems on AWS with Node.js, TypeScript and Python, for products in healthcare, fintech and HR SaaS.

Most of my work is the part of a product users don't see: jobs that run on a schedule, events that trigger other services, login and session rules, and keeping one customer's data away from another's. I also work on the React web apps when a feature needs both sides.

Lately I've been exploring how AI coding agents can take on real feature work without making things up, which led to the workflow below.

I'm currently **open to backend and full-stack roles**.

## What I've worked on

My product work is in private company repos, so here's what it involved:

- **Patient alert pipeline (healthcare):** a scheduled AWS Batch job that scans patient readings and sends alerts by push, SMS and email, with retries and safeguards against messaging test accounts.
- **Google sign-in for existing users (fintech):** a Cognito trigger that links a Google login to an account that already exists, so the same person doesn't end up with two accounts.
- **Tenant data isolation (HR SaaS):** PostgreSQL Row-Level Security so each company's queries only ever return its own rows, even if application code forgets a filter.
- **One active session per user (healthcare):** forced logout across every open tab using a WebSocket connection registry in DynamoDB.

## Open source

- **[claude-code-agent-workflow](https://github.com/Pawan-j-acharya/claude-code-agent-workflow):** planner, critic and builder agents for Claude Code that take a ticket from plan to reviewed code, one slice at a time. On a real feature it used about 65% fewer tokens than Claude Code's built-in subagents. The first version failed, and the repo explains what I changed.

## Writing

- [How I built a centralized agentic workflow using Claude Code subagents](https://community.7edge.com/t/claude-code-subagents-how-i-built-a-centralized-agentic-workflow-using-subagents/400): what worked, what failed, and the token numbers.
- [Multi-tenant isolation with PostgreSQL Row-Level Security](https://community.7edge.com/t/211): enforcing tenant boundaries in the database instead of in every query.
- [Linking Google sign-in to existing Cognito users](https://community.7edge.com/t/224): avoiding duplicate accounts when users switch login methods.

## Tools I use

Node.js · TypeScript · Python · React · AWS (Lambda, API Gateway, Cognito, EventBridge, Batch, DynamoDB, S3) · MongoDB · PostgreSQL · Serverless Framework

AWS Certified Developer – Associate · AWS Certified Cloud Practitioner

## Get in touch

[LinkedIn](https://www.linkedin.com/in/pawan-acharya-638584290/) · pawanachar20@gmail.com
