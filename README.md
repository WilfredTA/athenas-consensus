# Athena's Consensus


This (WIP) repository contains formal specs & proofs of distributed systems concepts, including consensus protocols, foundational definitions & conjectures, as well as impossibility results.

All specifications & proofs are written using the [Athena](https://github.com/AthenaFoundation/athena) language.

The first example (and only one currently filled in) is called ["Simple Agreement"](/simple-agreement/types.ath). This is a quite simple consensus protocol based on the one used by Martin Kleppmann in his case study / tutorial titled  ["Verifying distributed systems with Isabelle/HOL"](https://martin.kleppmann.com/2022/10/12/verifying-distributed-systems-isabelle.html). The code files for Kleppmann's Isabelle/HOL formalization can be found in the following gist: [Correctness proofs of distributed systems with Isabelle](https://gist.github.com/ept/b6872fc541a68a321a26198b53b3896b).

More examples are to come (including: a p2p gossip protocol that uses randomness to select subset of neighbors, as well as Paxos, Dolev-Strong, and Tendermint). This repository also specifies some abstract modules that include definitions and theorems meant to be reused across theories such as the abstract specifications of Byzantine Broadcast & State Machine Replication.

- Progress
    - [x] Simple Agreement
    - [ ] Paxos
    - [ ] Dolev-Strong
    - [ ] P2P Gossip
