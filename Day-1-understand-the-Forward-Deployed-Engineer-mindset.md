**Day 1**
Today’s goal: understand the **Forward Deployed Engineer mindset**.

An FDE is not just a backend developer. An FDE takes an unclear customer/business problem and turns it into a working, useful, production-ready solution.

| Backend Engineer | Forward Deployed Engineer |
|---|---|
| Builds assigned APIs/features | Finds the real customer problem |
| Works mainly from requirements | Creates requirements from discovery |
| Focuses on code quality and system design | Focuses on business outcome plus engineering |
| Usually less customer-facing | Highly customer-facing |
| Delivers service/module | Delivers usable solution/adoption |

**Core Concept**
The FDE flow is:

```text
Customer problem
-> discovery questions
-> small useful prototype
-> technical design
-> production hardening
-> measurable business impact
```

Example:

```text
Problem: Support agents spend too much time reading long tickets.

FDE thinking:
User: support agent
Pain: slow triage
Data: ticket text, customer history, SLA
Prototype: summarize ticket, classify priority, suggest next action
Production needs: auth, audit logs, feedback, monitoring
Success metric: reduce triage time by 40%
```

**What To Learn Today**

1. What does an FDE do?
2. How is FDE different from normal Java/Spring Boot developer?
3. How to ask customer discovery questions.
4. How to convert a business problem into technical scope.
5. How to define version 1 without overengineering.

**Your Day 1 Task**
Open the exercise and fill this:

```text
User:
Current workflow:
First problem to solve:
Required data:
Systems to integrate:
First prototype:
Not automated in version one:
Security and privacy risks:
Success metrics:
Production readiness:
```

Interview answer to memorize:

```text
A Forward Deployed Engineer combines engineering, product thinking, and customer problem solving. The role is to understand a customer workflow, identify the real pain, build a practical solution quickly, and make it reliable enough for production. An FDE must handle ambiguity, communicate clearly, design systems, write code, debug issues, and measure business impact.
```

Next after this: **Day 1.1 Customer Discovery Questions**, where we go deeper into exactly what to ask a customer before designing anything.
