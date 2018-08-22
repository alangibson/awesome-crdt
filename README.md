# awesome-crdt
A list of awesome CRDT resources

## Papers

### Foundations

- [Achieving Convergence, Causality-Preservation, and Intention-Preservation in Real-Time Cooperative Editing Systems - Sun et. al. (1998)](http://diyhpl.us/%7Ebryan/papers2/distributed/distributed-systems/real-time-cooperative-editing-systems.1998.pdf)
- [Conflict-free Replicated Data Types - Marc Shapiro et. al. (2011)](https://hal.inria.fr/inria-00609399v1/document)
- [A comprehensive study of Convergent and Commutative Replicated Data Types - Marc Shapiro et. al. (2011)](https://hal.inria.fr/inria-00555588/document)
- [CRDTs: Consistency without concurrency control - Mihai Letia et. al. (2009)](https://arxiv.org/pdf/0907.0929)
- [A commutative replicated data type for cooperative editing - Nuno Preguiça (2009)](https://hal.inria.fr/inria-00445975/document)
- [Designing a commutative replicated data type - Marc Shapiro et. al. (2007)](https://arxiv.org/pdf/0710.1784)

### Applications

- [SwiftCloud: Fault-Tolerant Geo-Replication Integrated all the Way to the Client Machine - Marek Zawirski et. al. (2013)](https://arxiv.org/pdf/1310.3107.pdf)
- [LSEQ: an Adaptive Structure for Sequences in Distributed Collaborative Editing - Brice Nédelec et. al. (2013)](https://hal.archives-ouvertes.fr/hal-00921633/document)
- [Logoot: A Scalable Optimistic Replication Algorithm for Collaborative Editing on P2P Networks - Weiss et. al. (2009)](https://hal.archives-ouvertes.fr/inria-00432368/document)
- TODO WOOT, RGA

## Blogs

- [A Look at Conflict-Free Replicated Data Types](https://medium.com/@istanbul_techie/a-look-at-conflict-free-replicated-data-types-crdt-221a5f629e7e)

## Videos

- [Automerge: Making servers optional for real-time collaboration - Martin Kleppmann (J On The Beach 2018)](https://www.youtube.com/watch?v=PHz17gwiOc8&index=3&list=PLBWIvCz5rfq0CFXhIWKhbznImXB1aBqbp)
- ["Transactions: myths, surprises and opportunities" by Martin Kleppmann (Strange Loop)](https://www.youtube.com/watch?v=5ZjhNTM8XU8&index=2&list=PLBWIvCz5rfq0CFXhIWKhbznImXB1aBqbp)
- ["CRDTs Illustrated" by Arnout Engelen (Strange Loop)](https://www.youtube.com/watch?v=9xFfOhasiOE&list=PLBWIvCz5rfq0CFXhIWKhbznImXB1aBqbp)
- [Dmitry Ivanov & Nami Naserazad - Practical Demystification of CRDT (Lambda Days 2016) (Erlang Solutions)](https://www.youtube.com/watch?v=PQzNW8uQ_Y4&index=2&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [ElixirConf 2015 - CRDT: Datatype for the Apocalypse by Alexander Songe (Confreaks)](https://www.youtube.com/watch?v=txD1tfyIIvY&index=6&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [Using Erlang, Riak and the ORSWOT CRDT at bet365 (...) - Michael Owen - Erlang User Conference 2015 (Erlang Solutions)](https://www.youtube.com/watch?v=WXmO1IvzIZY&index=7&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [Kappa Day - Practical demystification of CRDT - Tomtom (Jug Łódź)](https://www.youtube.com/watch?v=v2Wedv37w5Q&index=8&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [Strong Eventual Consistency and Conflict-free Replicated Data Types (ThisByGustav)](https://www.youtube.com/watch?v=ebWVLVhiaiY&index=9&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- ["Distributed, Eventually Consistent Computations" by Christopher Meiklejohn (Strange Loop)](https://www.youtube.com/watch?v=lsKaNDj4TrE&index=11&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [Lightning Talk: Just-Right Consistency: Closing The CAP Gap - Christopher Meiklejohn (Erlang Solutions)](https://www.youtube.com/watch?v=zVcv27m8zgY&index=13&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [CRDTs in Practice - Marc Shapiro & Nuno Preguiça (Erlang Solutions)](https://www.youtube.com/watch?v=xxjHC3yLDqw&list=PLzUeAPxtWcqxBXjUelmcm5ORVjEpbUlHH&index=4)
- [Tutorial: How to build an Collaborative Editing Application with IPFS using CRDT (IPFS)](https://www.youtube.com/watch?v=-kdx8rJd8rQ)

### Playlists

- [CRDT Talks Playlist (IPFS)](https://www.youtube.com/watch?v=em9zLzM8O7c&list=PLuhRWgmPaHtSvjFsjaVm_Fj9nXuwW35Ai)
- [Coding CRDT's (Jeroen Zuijderhoudt)](https://www.youtube.com/watch?v=em9zLzM8O7c&list=PLzUeAPxtWcqxBXjUelmcm5ORVjEpbUlHH)
- [CRDT (Adib Saikali)](https://www.youtube.com/watch?v=oyUHd894w18&list=PL-qXCjp3nQxUjhbdaC7E02a6bzrmG7U89)
- [crdt (Sonny To)](https://www.youtube.com/watch?v=rVRegyQvHqs&list=PLfV2ToGTS-JpUYyGFVK5AE5bzGtw4inwE)

## Implementations


TODO https://github.com/y-js/yjs


### Data Structures

- [KSeq: A continuous sequence CRDT based on Logoot/LSEQ](https://github.com/nkohari/kseq)
- [LSEQ: CRDT for sequences](https://github.com/Chat-Wane/LSEQ)
- [LSEQTree: A data structure for distributed arrays using the LSeq allocation strategy](https://github.com/Chat-Wane/LSEQTree)
- [LSEQArray: aims to provide an implementation of a CRDT-based array using the allocation strategy LSEQ](https://github.com/Chat-Wane/LSEQArray)
- [Automerge: A JSON-like data structure (a CRDT) that can be modified concurrently by different users, and merged again automatically](https://github.com/automerge/automerge)
- [Yjs: framework for offline-first p2p shared editing on structured data like text, richtext, json, or XML](https://github.com/y-js/yjs)
- [teletype-crdt: The string-wise sequence CRDT powering peer-to-peer collaborative editing in Teletype for Atom](https://github.com/atom/teletype-crdt)
- [Peer CRDT: An extensible collection of operation-based CRDTs that are meant to work over a p2p network](https://github.com/ipfs-shipyard/peer-crdt)

### Editors

- [SandEdit: a project aiming to provide a distributed collaborative editor based on Conflict-free Replicated Data Type](https://github.com/Chat-Wane/SandEdit)
- [Teletype for Atom: Share your workspace with team members and collaborate on code in real time in Atom](https://github.com/atom/teletype)
- [IPFS CRDT Shared Editing: Decentralized Real-Time Collaborative Documents - Conflict-free editing in the browser using js-IPFS and CRDTs](https://github.com/vigzmv/IPFS-CRDT-shared-editing)
- [Shared editing demo using IPFS and CRDT](https://github.com/ipfs-shipyard/shared-editing-demo)

### Databases and Logs

- [AntidoteDB](https://syncfree.github.io/antidote/)
- [Riak KV](http://docs.basho.com/riak/kv/2.2.3/developing/data-types/)
- [Hypermerge: combines Automerge, a CRDT, with hypercore, a distributed append-only log](https://github.com/automerge/hypermerge)

## Projects

### SyncFree

- [SyncFree](https://github.com/SyncFree)

## More Lists

- [Readings in conflict-free replicated data types](http://christophermeiklejohn.com/crdt/2014/07/22/readings-in-crdts.html)
