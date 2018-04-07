---
class:
- stop
rel:
- self
properties:
  name: Service Credit
  sort: 8
  level: 1
  description: When an SLA is not met, how are accounts being credit due to service
    outages, and downtime, hold the platform accountable for reliability.
entities:
- class:
  - stop
  rel:
  - self
  properties:
    name: Service Credit
  links:
  - rel:
    - self
    href: service-level-agreements/service-credit.md
  - rel:
    - parent
    href: service-level-agreements/
links:
- rel:
  - self
  href: service-level-agreements/service-credit.md
- rel:
  - parent
  href: service-level-agreements/
...