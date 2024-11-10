# paxos
CSP Formalization for Basic Paxos Protocol. 

Notable highlights: 
- Less than 300 lines (w/o comments) for 7 scenarios.
- Has support for leader election (multiple proposers).
- Has support for retries (when a NACK is received)
- Automatic assertions and verifications written to ensure working, good code 💪🏻 

## Changelog

### v1 official
- Optimize various code traces (<300 lines for 7 scenarios)
- Optimize internal state for Proposers and Acceptors
- Optimize reset and retry capabilities
- Add traces for the 7 scenarios

### v0.3-beta
- Resolve more bugs

### v0.2-beta
- Add coverage for when multiple Proposers conflict
- Add coverage for when new Proposers cannot change an existing consensus
- Add coverage for when a multi-identifier majority is insufficient
- Add coverage for when an Acceptor accepts Two Different Values
- Resolve issue where you can recover before resetting acceptor state

### v0.1-beta 

- Add support for multi-proposers
- Add coverage for when a proposer fails after sending **an** Accept
- Add coverage for when a redundant learner fails
- Add coverage for when an acceptor fails to send a Promise (quorum achieved)
- Bug Fixes
- Better formatting
