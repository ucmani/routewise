# RouteWise

**Find out how much of your LLM traffic actually needs your most expensive model.**

> Status: early development.

## Why

Most LLM-powered products send every request to one strong, expensive model. A large share of those requests are simple enough for a smaller, cheaper model to handle just as well, but teams rarely have the evidence to act on that safely.

Generic routing tools exist, but they are typically tuned on someone else's data. Your traffic, your users, and your definition of "good enough" are different.

## What RouteWise does

RouteWise looks at real conversation traffic and answers three questions:

1. **How much are you overspending?** An estimate of the cost that could move to a smaller model, broken down by task type.
2. **What would it cost in quality?** Where a smaller model holds up, and where it doesn't.
3. **Can routing be automated safely?** A learned router that sends each request to the right-sized model, and keeps checking its own decisions over time.
