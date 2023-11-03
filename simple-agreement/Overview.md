# Simple Agreement

In this repository are three Athena files that fully specify the Simple Agreement consensus protocol.

The contents of each file is described below:
- `types.ath`: This file contains data structure definitions as well as function declarations so we can *talk* about a network of communicating processes.
- `network-semantics.ath`: This file contains the formal definition of the state transition functions (as well as auxiliary functions) used to specify the consensus protocol's operational semantics.
- `network-invariants.ath`: This file contains the definition of the correctness properties (invariants) of the Simple Consensus protocol as well as a set of proofs that these invariants hold over the system defined in `network-semantics.ath`.


*Current status*: Semantics and type definitions are complete; some of the core invariants are defined but not yet proven to hold. 

## Walkthrough (tutorial)

Coming soon