---
class:
- stop
rel:
- self
properties:
  name: Close (RFC 7230)
  sort: 421
  level: 3
  description: 'The header field-name "Close" has been registered as "reserved", since
    using that name as an HTTP header field might conflict with the "close" connection
    option of the Connection header field. '
entities:
- class:
  - stop
  rel:
  - self
  properties:
    name: Close (RFC 7230)
  links:
  - rel:
    - self
    href: design/headers/close-rfc-7230.md
  - rel:
    - parent
    href: design/headers/
links:
- rel:
  - self
  href: design/headers/close-rfc-7230.md
- rel:
  - parent
  href: design/headers/
...
