# awesome-reads
Collection of interesting materials about distributed systems and other CS domains

## Distributed protocols

- [SWIM: Scalable Weakly-consistent Infection-style Process Group Membership Protocol](http://www.cs.cornell.edu/~asdas/research/dsn02-SWIM.pdf) 
- [Lifeguard: SWIM-ing with situational awareness](https://www.hashicorp.com/blog/making-gossip-more-robust-with-lifeguard/)
- [Serf gossip protocol](https://www.serf.io/docs/internals/gossip.html)
- [Plumtree spanning trees for data dissemination](https://www.youtube.com/watch?v=bo367a6ZAwM&list=WL&index=1&t=63s)
- [Uber's Ringpop](https://eng.uber.com/ringpop-open-source-nodejs-library/)
- [Rapid membership](https://www.usenix.org/system/files/conference/atc18/atc18-suresh.pdf)
- [HyParView](https://speakerdeck.com/cmeiklejohn/hyparview-a-membership-protocol-for-reliable-gossip-based-broadcast)
- [FireFlies: byzantine-tolerant membership and gossip](https://wiki.epfl.ch/edicpublic/documents/Candidacy%20exam/PR14Pavlovic.pdf)
- [Raft consensus](http://thesecretlivesofdata.com/raft/)
- [CASPaxos](https://arxiv.org/pdf/1802.07000.pdf)
- [RAMP Made Easy: RAMP-Fast algorithm](http://rustyrazorblade.com/2015/11/ramp-made-easy/)
- [RAMP Made Easy: RAMP-Slow algorithm](http://rustyrazorblade.com/2015/11/ramp-made-easy-part-2/)
- [Cure: Transaction Protocol](https://pages.lip6.fr/Marc.Shapiro/papers/Cure-final-ICDCS16.pdf)
- [Atlas: state-machine geo-replication](https://arxiv.org/pdf/2003.11789.pdf)
- [ActOp: Optimizing Distributed Actor Systems for Dynamic Interactive Services](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/eurosys16loca_camera_ready-1.pdf)
- [Transactions for Distributed Actors in the Cloud](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/10/EldeebBernstein-TransactionalActors-MSR-TR-1.pdf)
- [AMBROSIA: providing performant virtual resiliency](https://dl.acm.org/doi/abs/10.14778/3377369.3377370)
- [IPA: Invariant-Preserving Apps for weakly consistent systems](http://www.vldb.org/pvldb/vol12/p404-balegas.pdf)
- [Snapdoc: authenticated P2P snapshots with history privacy](https://content.sciendo.com/view/journals/popets/2019/3/article-p210.xml?language=en)

## Systems

- [AWS Aurora](https://www.slideshare.net/AmazonWebServices/aws-reinvent-2016-deep-dive-on-amazon-aurora-dat303/8?src=clipshare)
- [Spanner: Becoming a SQL System](https://static.googleusercontent.com/media/research.google.com/pl//pubs/archive/46103.pdf)
- [Eventuate: reliable casual broadcast based on eventsourcing](http://rbmhtechnology.github.io/eventuate/architecture.html)

## Data structures

- [A comprehensive study of Convergent and Commutative Replicated Data Types](https://hal.inria.fr/inria-00555588/PDF/techreport.pdf)
- [Delta-state replicated data types](https://arxiv.org/pdf/1603.01529.pdf)
- [Efficient synchronization of state-based CRDTs](https://arxiv.org/pdf/1803.02750.pdf)
- [Pure operation-based CRDTs](https://arxiv.org/pdf/1710.04469.pdf)
- [Quotient filters](https://blog.acolyer.org/2017/08/08/a-general-purpose-counting-filter-making-every-bit-count/)
- [Bloom clocks](https://arxiv.org/abs/1905.13064)
- [Dotted version vectors](http://basho.com/posts/technical/vector-clocks-revisited-part-2-dotted-version-vectors/)
- [Node-scoped logical clocks](http://haslab.uminho.pt/tome/files/dotteddb_srds.pdf)
- [Adaptive Replacement Cache](https://lrita.github.io/images/posts/datastructure/ARC.pdf)
- [Local-first software](https://martin.kleppmann.com/papers/local-first.pdf)
- [Mergable Replicated Data Types](https://kcsrk.info/papers/oopsla19-mrdt.pdf)
- [Modern B-Tree Techniques](https://w6113.github.io/files/papers/btreesurvey-graefe.pdf)
- [Riak BigSets](https://pages.lip6.fr/syncfree/index.php/2-uncategorised/53-big-sets.html)

## Streaming

- [Apache Gearpump](http://downloads.typesafe.com/website/presentations/GearPump_Final.pdf)
- [MillWheel: Fault-Tolerant Stream Processing at Internet Scale](https://www.cs.cmu.edu/~pavlo/courses/fall2013/static/papers/p734-akidau.pdf)
- [Kafka exactly once delivery and transactional messaging](https://cwiki.apache.org/confluence/display/KAFKA/KIP-98+-+Exactly+Once+Delivery+and+Transactional+Messaging)

## Performance

- [Lock-free algorithms behind Kotlin coroutines](https://www.youtube.com/watch?v=W2dOOBN1OQI&feature=youtu.be)
- [Scylla’s Approach to Improve Performance for CPU-bound workloads](http://www.scylladb.com/2017/07/06/scyllas-approach-improve-performance-cpu-bound-workloads/)
- [Seastar tutorial for scheduling groups](https://github.com/scylladb/seastar/blob/master/doc/tutorial.md#isolation-of-application-components)
- [Understanding Go channels](https://www.youtube.com/watch?v=KBZlN0izeiY)
