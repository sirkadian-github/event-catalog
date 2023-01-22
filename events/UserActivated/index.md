---
name: UserActivated
version: 0.0.1
summary: |
  Event represents when an user activated
producers:
    - Auth Service
consumers:
    - User Food Service
owners:
    - dboyne
    - mSmith
---

<Admonition>When firing this event make sure you set the `correlation-id` in the headers. Our schemas have standard metadata make sure you read and follow it.</Admonition>

### Details

This event is the final event of the registration process. It gets raised when user activated.

<NodeGraph title="Consumer / Producer Diagram" />

<Schema />