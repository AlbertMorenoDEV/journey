---
class:
- stop
rel:
- self
properties:
  name: Database
  sort: 3263
  level: 2
  description: Providing services and tooling for backing up database, allowing for
    easy storage and restore of all database resources.
entities:
- class:
  - stop
  rel:
  - self
  properties:
    name: Database
  links:
  - rel:
    - self
    href: backup/database.md
  - rel:
    - parent
    href: backup/
links:
- rel:
  - self
  href: backup/database.md
- rel:
  - parent
  href: backup/
...
