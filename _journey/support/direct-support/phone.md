---
class:
- stop
rel:
- self
properties:
  name: Phone
  sort: 3
  level: 2
  description: Providing a phone number that developers can call when they need support.
entities:
- class:
  - stop
  rel:
  - self
  properties:
    name: Phone
  links:
  - rel:
    - self
    href: support/direct-support/phone.md
  - rel:
    - parent
    href: support/direct-support/
links:
- rel:
  - self
  href: support/direct-support/phone.md
- rel:
  - parent
  href: support/direct-support/
...