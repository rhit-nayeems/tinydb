# tinydb fork roadmap

Test roadmap for Mandavero end-to-end testing on this fork.

## Queries
- [x] Add Table.first(cond) returning the first matching document
  - Table.first(cond) returns the first document matching cond, in insertion order.
  - Table.first(cond) returns None when nothing matches.
  - Existing tests pass.
- [ ] Add Table.exists(cond) as a readable alias for contains
  - Table.exists(cond) returns True exactly when Table.contains(cond) does.
  - Existing tests pass.
