## BitcoinFS

* The most safe filesystem ever, totally eliminates all worry about your data!
* Your data is kept on every [Bitcoin nodes](https://bitnodes.io/) over the world, and verification of the data will be done by each node.
* You just need to pay a [small transaction fee](https://en.bitcoin.it/wiki/Transaction) for storing every 80 bytes of your data. Why don't pay such small fee for storing your data forever?

## Implementation

* Your data will be splitted into 80 byte sized chunks, and each chunk is stored in [OP_RETURN](https://en.bitcoin.it/wiki/OP_RETURN) parameter of every Bitcoin transactions.
* TODO