# PrivateBlockchainSmartContracts
a book about smart contracts on private blockchains

## This book is FREE and will stay free. You can download pdf or the epub version.

### <a href="https://github.com/AndreiD/PrivateBlockchainSmartContracts/raw/master/My%20Ethereum%20Book.pdf">Download PDF version here</a>
### <a href="https://github.com/AndreiD/PrivateBlockchainSmartContracts/raw/master/My%20Ethereum%20Book.epub">Download EPUB version here</a>

Proof-of-Authority is a newer concept in the blockchain world where you have a number of pre-approved authority nodes (called sealers, think of these as mining nodes). 
Any new node that you want to add has to be voted on by the currently approved set of authority nodes, this gives you full control over which nodes can seal blocks (mine) on your network. 
To make sure a malicious signer cannot do too much harm to the network any signer can sign at most one of a number of consecutive blocks 
(SIGNER_COUNT / 2) + 1. The same consensus is applied when an authority node is removed from the network.

The Ethereum Proof-of-Authority protocol is called Clique and is well described in the Clique Github issue. Ethereum currently uses this algorithm for the Rinkeby test network.

In this book we will discuss writing Smart Contracts, that will work both on mainnet and on private blockchains, and setting up a private blockchain system using Ethereum's Proof of Authority Clique
