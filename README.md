# Timestamp Files with Oracles

Project for https://chain.link/hackathon

We know that data can be published on the immutable ledger using blockchain, but how can we publish a file
1) with a verifiable timestamp
2) without high transaction fees

on the immutable ledger?

## Current Methods

One way is to put the timestamp on the document: 
Word files, pdf files, (in-app) keybase files, etc. have a timestamp of when the document was created/uploaded and when it was modified. However this is not verifiable.

Another way is to put the document on the timestamp: 
Encode the data on the blockchain as part of a transaction. However this incurs high transaction fees.

## Proposed Method

Create a private network to avoid high transaction fees. Call an oracle to compare blocktimes with Bitcoin or Ethereum blocktimes for verification. Publish the encoded article on the private network!
