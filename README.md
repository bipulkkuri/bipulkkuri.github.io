
- Welcome!

Study guide
![AWS DEA-C01](/AWS-DEA-C01/index.html)

Oauth2
![Oauth2 flow](/oauth2/oauth2.drawio.html)


Study Notes

Splitting a database into many databases based on the business domain is called Federation. Like DB for user,account,address,product ,Used to scale easily

Splitting a single dataset across many servers is called Sharding. Used to scale out

Erasure coding splits a data object into chunks called data shards.And creates extra chunks called parity shards.While the original data object can be recreated from a subset of the shards.

Data integrity can be checked via checksum

Bracketing is the process of reversing the entire set of transformations on the data.It ensures that a data object can be recreated from individual shards.


Scaling the computing resources based on load is called Autoscaling. It reduced their costs and operational complexity.

Bloom filter: a memory-efficient probabilistic data structure to check whether an element is present in a set
Trie: a tree data structure used for locating specific keys from within a set

Deployment should be done after durability review: Threat model, risk,mitigation,metrics, audit ,guardrails
