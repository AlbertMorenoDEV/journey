---
class:
- stop
rel:
- self
properties:
  name: Zone
  sort: 940
  level: 3
  description: Manage the zones for any particular domain.
entities:
- class:
  - stop
  rel:
  - self
  properties:
    name: Zone
  links:
  - rel:
    - self
    href: dns/addressing/zone.md
  - rel:
    - parent
    href: dns/addressing/
links:
- rel:
  - self
  href: dns/addressing/zone.md
- rel:
  - parent
  href: dns/addressing/
...
