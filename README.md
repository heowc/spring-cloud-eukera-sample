### Architecture

```
 ::Serveice Discovery::
                            Client
                            ┌────────────────────┐
                        ┌─> │  spring boot(8080) │
   Server               │   └────────────────────┘
 ┌────────────────────┐ │   ┌────────────────────┐
 │  spring boot(8761) │ ──> │  spring boot(8080) │
 └────────────────────┘ │   └────────────────────┘
                        │   ┌────────────────────┐
                        └─> │  spring boot(8080) │
                            └────────────────────┘
```
