# From True-Concurrent Games to a Categorical Logic of Agency

This repository contains research on the categorical foundations of cybernetics. It asks how to describe a system of interacting agents so that, when components are connected, we can still tell who controls each decision, what information reaches it, and which actions remain possible.

A running example shows why these distinctions matter. Two pairs of policies produce the same observed actions, but only one pair satisfies an authorization rule. A checker that sees only the current actions cannot tell the cases apart. The paper constructs the extra signals the checker needs and traces the authorization token to the action it enables.

## Where to start

- **Control and incentives (§§4–5 and 8).** Who can change a joint decision? A cost monad records the outcome and accumulated cost of a run, so an owner can compare alternatives using both.
- **Communication and oversight (§11).** What do the agents learn when a message arrives? Sections 11.11–11.13 work through disclosure, the price of authorization, and the checker.
- **Controller memory and abstraction (§§12, 14).** When can two histories share a controller state? The answer depends on which future responses or interventions the model must preserve.
