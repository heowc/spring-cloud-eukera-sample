### Architecture

```
 ::Serveice Discovery::
                            Client
                            ┌───────────────────────┐
                        ┌─> │ client-product (8081) │
   Server               │   └───────────────────────┘
 ┌────────────────────┐ │   ┌───────────────────────┐
 │ server      (8761) │ ──> │ client-user    (8082) │
 └────────────────────┘ │   └───────────────────────┘
                        │   ┌───────────────────────┐
                        └─> │ client-user    (8083) │
                            └───────────────────────┘
```
