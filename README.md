# Awesome CRDT

A collection of awesome CRDT resources

## Know Before You Go

### Set Theory

- [Set Notation and Concepts](https://link.springer.com/content/pdf/bbm%3A978-0-85729-829-4%2F1.pdf)
- [Set theory symbols](https://www.rapidtables.com/math/symbols/Set_Symbols.html)

### Order Theory

- [Partially ordered set (Wikipedia)](https://en.wikipedia.org/wiki/Partially_ordered_set)
- [Total Order (Wikipedia)](https://en.wikipedia.org/wiki/Total_order)
- [Causal Ordering](http://scattered-thoughts.net/blog/2012/08/16/causal-ordering/)
- [Semilattice (Wikipedia)](https://en.wikipedia.org/wiki/Semilattice)
- [Defanging Order Theory](http://jtfmumm.com/blog/2015/11/17/crdt-primer-1-defanging-order-theory/)

### Clocks

- [Logical Clock (Wikipedia)](https://en.wikipedia.org/wiki/Logical_clock)
- [Lamport Timestamps (Wikipedia)](https://en.wikipedia.org/wiki/Lamport_timestamps)
- [Assigning Lamport & Vector Timestamps](https://www.cs.rutgers.edu/~pxk/417/notes/clocks/index.html)
- [Vector Clock (Wikipedia)](https://en.wikipedia.org/wiki/Vector_clock)
- [Version Vector (Wikipedia)](https://en.m.wikipedia.org/wiki/Version_vector)
- [Why Logical Clocks are Easy](https://queue.acm.org/detail.cfm?id=2917756)

## Papers 

### Foundations

- [Achieving Convergence, Causality-Preservation, and Intention-Preservation in Real-Time Cooperative Editing Systems - Sun et. al. (1998)](http://diyhpl.us/%7Ebryan/papers2/distributed/distributed-systems/real-time-cooperative-editing-systems.1998.pdf)
- [Designing a commutative replicated data type - Marc Shapiro et. al. (2007)](https://arxiv.org/pdf/0710.1784)
- [CRDTs: Consistency without concurrency control - Mihai Letia et. al. (2009)](https://arxiv.org/pdf/0907.0929)
- [A commutative replicated data type for cooperative editing - Nuno Preguiça (2009)](https://hal.inria.fr/inria-00445975/document)
- [A comprehensive study of Convergent and Commutative Replicated Data Types - Marc Shapiro et. al. (2011)](https://hal.inria.fr/inria-00555588/document)
- [Convergent and Commutative Replicated Data Types - Marc Shapiro et. al. (2011)](https://hal.inria.fr/hal-00932833/document)
- [Conflict-free Replicated Data Types - Marc Shapiro et. al. (2011)](https://hal.inria.fr/inria-00609399v1/document)
- [Pure Operation-Based Replicated Data Types - Carlos Baquero et. al. (2017)](https://arxiv.org/pdf/1710.04469.pdf)
- [Evaluating CRDTs for Real-time Document Editing - Mehdi Ahmed-Nacer et. al.](https://members.loria.fr/CIgnat/files/pdf/AhmedNacerDocEng11.pdf)
- [Large-Scale Geo-Replicated Conflict-free Replicated Data Types - Carlos Bartolomeu](http://www.gsd.inesc-id.pt/~ler/reports/carlosbartolomeu-midterm.pdf)
- [Pure Operation-Based Replicated Data Types - Carlos Baquero et. al. (2017)](https://arxiv.org/pdf/1710.04469.pdf)
- [Consistency, Availability, and Convergence - Mahajan et. al.](http://www.cs.utexas.edu/users/dahlin/papers/cac-tr.pdf)

#### Clocks

- [Time, Clocks, and the Ordering of Events in a  Distributed System - Leslie Lamport (1978)](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)
- [Virtual Time and Global States of Distributed Systems - Friedemann Mattern (1988)](https://www.vs.inf.ethz.ch/publ/papers/VirtTimeGlobStates.pdf)
- [Timestamps in Message-Passing Systems That Preserve the Partial Ordering - Colin Fidge (1988)](http://fileadmin.cs.lth.se/cs/Personal/Amr_Ergawy/dist-algos-papers/4.pdf)
- [Dotted Version Vectors: Efficient Causality Tracking for Distributed Key-Value Stores - Carlos Baquero et. al.](http://gsd.di.uminho.pt/members/vff/dotted-version-vectors-2012.pdf)

### Applications

- [WOOT: Real time group editors without Operational transformation - Gérald Oster et. al. (2005)](https://hal.inria.fr/inria-00071240/document)
- [RGA, RHT, RFA: Replicated abstract data types: Building blocks for collaborative applications - Hyun-Gul Roh (2011)](http://csl.skku.edu/papers/jpdc11.pdf)
- [Logoot: A Scalable Optimistic Replication Algorithm for Collaborative Editing on P2P Networks - Weiss et. al. (2009)](https://hal.archives-ouvertes.fr/inria-00432368/document)
- [TreeDoc: A commutative replicated data type for cooperative editing (2009)](https://hal.inria.fr/inria-00445975/document)
- [SwiftCloud: Fault-Tolerant Geo-Replication Integrated all the Way to the Client Machine - Marek Zawirski et. al. (2013)](https://arxiv.org/pdf/1310.3107.pdf)
- [LSEQ: an Adaptive Structure for Sequences in Distributed Collaborative Editing - Brice Nédelec et. al. (2013)](https://hal.archives-ouvertes.fr/hal-00921633/document)
- [WOOTR: Abstract unordered and ordered trees CRDT - Stéphane Martin et. al. (2011)](https://arxiv.org/pdf/1201.1784.pdf)
- [Logoot-Undo: Distributed Collaborative Editing System on P2P Networks - Stéphane Weiss et. al.](https://s3.amazonaws.com/academia.edu.documents/39769048/Logoot-Undo_Distributed_Collaborative_Ed20151107-5753-e8mgn.pdf?AWSAccessKeyId=AKIAIWOWYYGZ2Y53UL3A&Expires=1535395093&Signature=0osSBA0TEG5rjZ58sr9z7%2FrC%2Bxc%3D&response-content-disposition=inline%3B%20filename%3DLogoot-Undo_Distributed_Collaborative_Ed.pdf)
- [Yjs: A Framework for Near Real-Time P2P Shared Editing on Arbitrary Data Types (2015)](http://dbis.rwth-aachen.de/~derntl/papers/preprints/icwe2015-preprint.pdf)
- [Causal trees: towards real-time read-write hypertext - Victor Grishchenko](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.627.5286&rep=rep1&type=pdf)
- [RGASplit: High Responsiveness for Group Editing CRDTs](https://pages.lip6.fr/Marc.Shapiro/papers/rgasplit-group2016-11.pdf)
- [COPS: Don’t Settle for Eventual: Scalable Causal Consistency for Wide-Area Storage with COPS](http://www-users.cselabs.umn.edu/classes/Spring-2018/csci8980/Papers/CloudDataStorageManagement/COPS.pdf)

#### Clocks

- [Dotted Version Vectors: Logical Clocks for Eventually Consistent Systems](https://github.com/ricardobcl/Dotted-Version-Vectors)

### Proof and Verification

- [A framework for verifying Conflict-free Replicated Data Types (CRDTs) - Dominic Mulligan (2017)](http://srepls6.cs.ucl.ac.uk/images/mulligan.pdf)
- [Verifying Strong Eventual Consistency in Distributed Systems - VICTOR B. F. GOMES (2017)](https://arxiv.org/pdf/1707.01747.pdf)
- [On Verifying Causal Consistency - Bouajjani et. al. (2017)](https://pages.lip6.fr/Marc.Shapiro/workshop-2017-05-03/attachments/enea-slides.pdf)

## Blogs

- [A Look at Conflict-Free Replicated Data Types](https://medium.com/@istanbul_techie/a-look-at-conflict-free-replicated-data-types-crdt-221a5f629e7e)
- [Distributed data structures with Coq](http://christophermeiklejohn.com/coq/2013/06/11/distributed-data-structures.html)
- [Towards a unified theory of Operational Transformation and CRDT](https://medium.com/@raphlinus/towards-a-unified-theory-of-operational-transformation-and-crdt-70485876f72f)
- [Working code for Operational Transformation/CRDT hybrid](https://medium.com/@raphlinus/working-code-for-operational-transformation-crdt-hybrid-9d04a57309da)
- [Convergent Replicated Data Types](http://simongui.github.io/distributed-systems/crdt.html)
- [Logs and docs](https://medium.com/@gritzko/logs-and-docs-b6cb34efc7de)
- [CRDTs explained - supercharge your serverless with CRDTs at the Edge (Russell Sullivan)](https://serverless.com/blog/crdt-explained-supercharge-serverless-at-edge/)
- [Good Spirits: Syncing Data Statelessly](http://archagon.net/blog/2018/09/03/good-spirits-persisting-data-statelessly/)
- [Delta State Replicated Data Types](https://blog.acolyer.org/2016/04/25/delta-state-replicated-data-types/)
- [Datanet: a New CRDT Database that Let's You Do Bad Bad Things to Distributed Data](http://highscalability.com/blog/2016/10/17/datanet-a-new-crdt-database-that-lets-you-do-bad-bad-things.html)
- [Data Laced with History: Causal Trees & Operational CRDTs](http://archagon.net/blog/2018/03/24/data-laced-with-history)
- [Serverless collaboration - (03/03/2019)](https://thegeez.net/2019/03/03/serverless_collab.html)
- [Code together in real time with Teletype for Atom - (15/11/2017)](https://blog.atom.io/2017/11/15/code-together-in-real-time-with-teletype-for-atom.html)

## Videos

- [Strong Eventual Consistency and Conflict-free Replicated Data Types - Marc Shapiro (ThisByGustav)](https://www.youtube.com/watch?v=ebWVLVhiaiY&index=9&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [CRDTs in Practice - Marc Shapiro & Nuno Preguiça (Erlang Solutions)](https://www.youtube.com/watch?v=xxjHC3yLDqw)
- [Automerge: Making servers optional for real-time collaboration - Martin Kleppmann (J On The Beach 2018)](https://www.youtube.com/watch?v=PHz17gwiOc8&index=3&list=PLBWIvCz5rfq0CFXhIWKhbznImXB1aBqbp)
- ["Transactions: myths, surprises and opportunities" by Martin Kleppmann (Strange Loop)](https://www.youtube.com/watch?v=5ZjhNTM8XU8&index=2&list=PLBWIvCz5rfq0CFXhIWKhbznImXB1aBqbp)
- ["CRDTs Illustrated" by Arnout Engelen (Strange Loop)](https://www.youtube.com/watch?v=9xFfOhasiOE&list=PLBWIvCz5rfq0CFXhIWKhbznImXB1aBqbp)
- [Dmitry Ivanov & Nami Naserazad - Practical Demystification of CRDT (Lambda Days 2016) (Erlang Solutions)](https://www.youtube.com/watch?v=PQzNW8uQ_Y4&index=2&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [ElixirConf 2015 - CRDT: Datatype for the Apocalypse by Alexander Songe (Confreaks)](https://www.youtube.com/watch?v=txD1tfyIIvY&index=6&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [Using Erlang, Riak and the ORSWOT CRDT at bet365 (...) - Michael Owen - Erlang User Conference 2015 (Erlang Solutions)](https://www.youtube.com/watch?v=WXmO1IvzIZY&index=7&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [Kappa Day - Practical demystification of CRDT - Tomtom (Jug Łódź)](https://www.youtube.com/watch?v=v2Wedv37w5Q&index=8&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- ["Distributed, Eventually Consistent Computations" by Christopher Meiklejohn (Strange Loop)](https://www.youtube.com/watch?v=lsKaNDj4TrE&index=11&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [Lightning Talk: Just-Right Consistency: Closing The CAP Gap - Christopher Meiklejohn (Erlang Solutions)](https://www.youtube.com/watch?v=zVcv27m8zgY&index=13&list=PLU3pXbz7Jcgn-tyj_hZ3kLlna_ojG5qD5)
- [Tutorial: How to build an Collaborative Editing Application with IPFS using CRDT (IPFS)](https://www.youtube.com/watch?v=-kdx8rJd8rQ)
- [WOOT: an algorithm for concurrency and collaborative authoring! (Julien Genestoux)](https://www.youtube.com/watch?v=NSTZ4mIv_wk)
- [CRDTs for Non Academics (Russell Sullivan)](https://www.youtube.com/watch?v=vBU70EjwGfw)
- [Datanet Website Slideshow](https://www.youtube.com/watch?v=jANg6Za4T1w)

### Playlists

- [CRDT Talks Playlist (IPFS)](https://www.youtube.com/watch?v=em9zLzM8O7c&list=PLuhRWgmPaHtSvjFsjaVm_Fj9nXuwW35Ai)
- [Coding CRDT's (Jeroen Zuijderhoudt)](https://www.youtube.com/watch?v=em9zLzM8O7c&list=PLzUeAPxtWcqxBXjUelmcm5ORVjEpbUlHH)
- [CRDT (Adib Saikali)](https://www.youtube.com/watch?v=oyUHd894w18&list=PL-qXCjp3nQxUjhbdaC7E02a6bzrmG7U89)
- [crdt (Sonny To)](https://www.youtube.com/watch?v=rVRegyQvHqs&list=PLfV2ToGTS-JpUYyGFVK5AE5bzGtw4inwE)

## Implementations

### Data Structures

- [KSeq: A continuous sequence CRDT based on Logoot/LSEQ](https://github.com/nkohari/kseq)
- [LSEQ: CRDT for sequences](https://github.com/Chat-Wane/LSEQ)
- [LSEQTree: A data structure for distributed arrays using the LSeq allocation strategy](https://github.com/Chat-Wane/LSEQTree)
- [LSEQArray: aims to provide an implementation of a CRDT-based array using the allocation strategy LSEQ](https://github.com/Chat-Wane/LSEQArray)
- [Automerge: A JSON-like data structure (a CRDT) that can be modified concurrently by different users, and merged again automatically](https://github.com/automerge/automerge)
- [Yjs: framework for offline-first p2p shared editing on structured data like text, richtext, json, or XML](https://github.com/y-js/yjs)
- [RON: Replicated Object Notation, a distributed live data format, golang/ragel lib ](https://github.com/gritzko/ron)
- [teletype-crdt: The string-wise sequence CRDT powering peer-to-peer collaborative editing in Teletype for Atom](https://github.com/atom/teletype-crdt)
- [Peer CRDT: An extensible collection of operation-based CRDTs that are meant to work over a p2p network](https://github.com/ipfs-shipyard/peer-crdt)
- [Distributed Data Structures in Coq](https://github.com/cmeiklejohn/distributed-data-structures)
- [Akka CRDT: An Eventually Consistent REST/JSON database using CRDTs, Akka Cluster and LevelDB](https://github.com/jboner/akka-crdt)
- [Akka Distributed Data](https://doc.akka.io/docs/akka/snapshot/distributed-data.html?language=scala)
- [wurmloch-crdt: Experimental implementations of conflict-free replicated data types (CRDTs) for the JVM](https://github.com/netopyr/wurmloch-crdt)

#### Toy Implementations

- [Companion to the article "Data Laced with History: Causal Trees & Operational CRDTs"](https://github.com/archagon/crdt-playground)
- [Meangirls: Convergent Replicated Data Types](https://github.com/aphyr/meangirls)

### Editors

- [SandEdit: a project aiming to provide a distributed collaborative editor based on Conflict-free Replicated Data Type](https://github.com/Chat-Wane/SandEdit)
- [Teletype for Atom: Share your workspace with team members and collaborate on code in real time in Atom](https://github.com/atom/teletype)
- [Xi Editor: an attempt to build a high quality text editor, using modern software engineering techniques](https://github.com/google/xi-editor/blob/master/docs/docs/crdt.md)
- [IPFS CRDT Shared Editing: Decentralized Real-Time Collaborative Documents - Conflict-free editing in the browser using js-IPFS and CRDTs](https://github.com/vigzmv/IPFS-CRDT-shared-editing)
- [Shared editing demo using IPFS and CRDT](https://github.com/ipfs-shipyard/shared-editing-demo)
- [Co: collaborative text editor, uses woot. front end in Elm, back in node](https://github.com/leahsteinberg/co)
- [woot-collaborative-editor: A real time collaboration toy project based on WOOT. Implemented with node.js and ws](https://github.com/ryankaplan/woot-collaborative-editor)
- [cljs-collab: Browser-to-browser collaborative editor](https://thegeez.net/2019/03/03/serverless_collab.html)
- [Xray: An experimental next-generation Electron-based text editor](https://github.com/atom/xray)
- [https://arxiv.org/pdf/1810.02137.pdf](Real Differences between OT and CRDT for Co-Editors)

### Databases and Logs

- [AntidoteDB](https://syncfree.github.io/antidote/)
- [Riak KV](http://docs.basho.com/riak/kv/2.2.3/developing/data-types/)
- [Hypermerge: combines Automerge, a CRDT, with hypercore, a distributed append-only log](https://github.com/automerge/hypermerge)
- [Roshi: a large-scale CRDT set implementation for timestamped events](https://github.com/soundcloud/roshi)
- [Swarm: JavaScript replicated model (M of MVC) library](https://github.com/gritzko/swarm)
- [Datanet: an open source CRDT based data synchronization system](http://datanet.co/)
- [Kuhirō: The Near Cloud](https://www.kuhiro.com)

## Projects and Organizations

### SyncFree

- [SyncFree](https://github.com/SyncFree)
- [Automerge](https://github.com/automerge)

## More Lists

- [Readings in conflict-free replicated data types](http://christophermeiklejohn.com/crdt/2014/07/22/readings-in-crdts.html)
- [Carlos Baquero bibliography](https://dblp.uni-trier.de/pers/hd/b/Baquero:Carlos)
- [BOOM: Berkley Orders of Magnitude](http://boom.cs.berkeley.edu/papers.html)
