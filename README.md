# paxos
CSP Formalization for Paxos Protocol

## Changelog

### v0.2-beta
- Add coverage for when multiple Proposers conflict
- Resolve issue where you can recover before resetting acceptor state

### v0.1-beta 

- Add support for multi-proposers
- Add coverage for when a proposer fails after sending **an** Accept
- Add coverage for when a redundant learner fails
- Add coverage for when an acceptor fails to send a Promise (quorum achieved)
- Bug Fixes
- Better formatting
