# Test Invalid UTF-8

This repository contains invalid UTF-8 mischief.

It was split from the main test repo <https://github.com/cirosantilli/test> because GitLab gives 500 preventing other tests.

The interesting objects are:

- [%FF](%FF). This byte can never appear in UTF-8.
- [%C0BC](%C0BC). Overlong encoding of `<`.
