---
name: UserRegister
version: 0.0.1
summary: |
  Event represents when an user register
producers:
    - Auth Service
consumers:
    - Email Service
owners:
    - dboyne
    - mSmith
---

<Admonition>When firing this event make sure you set the `correlation-id` in the headers. Our schemas have standard metadata make sure you read and follow it.</Admonition>

### Details

This event is the first event of the registration process. It gets raised when user register.

<NodeGraph title="Consumer / Producer Diagram" />

<Schema />