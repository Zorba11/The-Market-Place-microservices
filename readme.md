Language used - TypeScript
Frontend - React and Next JS
Backend services - Node, Express, MongoDB, Redis
Infra - Docker, Kubernetes on GCP

**Services**

auth - everything user related, sigup/signn,signout
tickets - listing creation, editing, editability
orders - order creation/editing
expiration - monitors order creation
payments - handles payment success/failures

**Events**

1. UserCreated, UserUpdated
2. OrderCreated, OrderCancelled, OrderExpired
3. TicketCreated, TicketUpdated
4. ChargeCreated

auth
