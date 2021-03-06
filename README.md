NOTE: If code doesn't load, view at https://nbviewer.jupyter.org/github/vkli/Chainlink-Hackathon-2021/blob/main/Untitled.ipynb

# Timestamp Files with Oracles

Project for https://chain.link/hackathon

We know that files can be published on the blockchain, but how can we publish a file
1) with a verifiable timestamp
2) without high transaction fees
3) while preserving privacy

on the immutable ledger?

## Current Methods

One way is to put the timestamp on the document: 
Word files, pdf files, (in-app) keybase files, etc. have a timestamp of when the document was created/uploaded and when it was modified. However this is not verifiable.

Another way is to put the document on the timestamp: 
Encode the data on the blockchain as part of a transaction. However this incurs high transaction fees and is not private.

## Proposed Method

Create a private blockchain. Call an oracle to compare blocktimes with Bitcoin/Ethereum blocktimes or Google clocktime for verification. Publish the encoded file on the private blockchain!

## Demo

https://youtu.be/Jf6_MF4rkpw

## Further Reading
[ChainLink Youtube Channel](https://www.youtube.com/channel/UCnjkrlqaWEBSnKZQ71gdyFA)

[Chainlink Fireside Chat with DocuSign Founder Tom Gonser](https://youtu.be/SZ3iy_jYFS4)

