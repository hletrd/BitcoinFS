## BitcoinFS

* The most safe filesystem ever, totally eliminates all worry about your data!
* Your data is kept on every [Bitcoin nodes](https://bitnodes.io/) over the world, and verification of the data will be done by each node.
* You just need to pay a [small transaction fee](https://en.bitcoin.it/wiki/Transaction) for storing every 80 bytes of your data. Why don't pay such a small fee for storing your data forever?
* Worrying about overhead for storing arbitrary data along with your file? It's just a small trade-off for storing your data safe. 

### How can I delete my data?
* Just remove a metadata pointing to the transaction storing a chunk of your data!

### It is too expensive!
* The first commercial HDD, [IBM 305 RAMAC](https://en.wikipedia.org/wiki/IBM_305_RAMAC) was about $30,000 for storing 5MB of data. BitcoinFS is cheaper!

### I don't want my data being publicly exposed.
* Well, it is not being *exposed*, it is just being distributed to nodes worldwide.

## Implementation

* Your data will be splitted into 80 byte sized chunks, and each chunk is stored in [OP_RETURN](https://en.bitcoin.it/wiki/OP_RETURN) parameter of every Bitcoin transactions.
* TODO
