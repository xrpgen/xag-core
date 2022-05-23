# The XAG Ledger

The XAG Ledger is a decentralized cryptographic ledger powered by a network of peer-to-peer servers. The XAG Ledger uses a novel Byzantine Fault Tolerant consensus algorithm to settle and record transactions in a secure distributed database without a central operator.

## XAG
Xrpalike Gene aims to help any organization that needs to build trust through a new generation of blockchain protocols at a low cost and rapid construction of a distributed financial book of bank-grade security
XAG project is forked from Ripple, XAG aims to build a new ecosystem upon ripple. Xrpalike Gene uses XAG to help build the Internet of Value, ushering in a world in which money moves as fast and efficiently as information does today.

## XRP
XRP is a public, counterparty-free asset native to the XRP Ledger, and is designed to bridge the many different currencies in use worldwide. XRP is traded on the open-market and is available for anyone to access. The XRP Ledger was created in 2012 with a finite supply of 100 billion units of XRP. Its creators gifted 80 billion XRP to a company, now called Ripple, to develop the XRP Ledger and its ecosystem.


### Build from Source

* [Linux](Builds/linux/README.md)
* [Mac](Builds/macos/README.md)
* [Windows](Builds/VisualStudio2017/README.md)

## Key Features of the XAG Ledger

- **Censorship-Resistant Transaction Processing:** No single party decides which transactions succeed or fail, and no one can "roll back" a transaction after it completes. As long as those who choose to participate in the network keep it healthy, they can settle transactions in seconds.
- **Fast, Efficient Consensus Algorithm:** The XAG Ledger's consensus algorithm settles transactions in 4 to 5 seconds, processing at a throughput of up to 1500 transactions per second. These properties put XAG at least an order of magnitude ahead of other top digital assets.
- **Finite XAG Supply:** When the XAG Ledger began, 100 billion XAG were created, and no more XAG will ever be created. The available supply of XAG decreases slowly over time as small amounts are destroyed to pay transaction costs.
- **Responsible Software Governance:** A team of full-time, world-class developers at Ripple maintain and continually improve the XAG Ledger's underlying software with contributions from the open-source community. Ripple acts as a steward for the technology and an advocate for its interests, and builds constructive relationships with governments and financial institutions worldwide.
- **Secure, Adaptable Cryptography:** The XAG Ledger relies on industry standard digital signature systems like ECDSA (the same scheme used by Bitcoin) but also supports modern, efficient algorithms like Ed25519. The extensible nature of the XAG Ledger's software makes it possible to add and disable algorithms as the state of the art in cryptography advances.
- **Modern Features for Smart Contracts:** Features like Escrow, Checks, and Payment Channels support cutting-edge financial applications including the [Interledger Protocol](https://interledger.org/). This toolbox of advanced features comes with safety features like a process for amending the network and separate checks against invariant constraints.
- **On-Ledger Decentralized Exchange:** In addition to all the features that make XAG useful on its own, the XAG Ledger also has a fully-functional accounting system for tracking and trading obligations denominated in any way users want, and an exchange built into the protocol. The XAG Ledger can settle long, cross-currency payment paths and exchanges of multiple currencies in atomic transactions, bridging gaps of trust with XAG.


## Source Code


### Repository Contents

| Folder     | Contents                                         |
|:-----------|:-------------------------------------------------|
| `./bin`    | Scripts and data files for Ripple integrators.   |
| `./Builds` | Platform-specific guides for building `rippled`. |
| `./docs`   | Source documentation files and doxygen config.   |
| `./cfg`    | Example configuration files.                     |
| `./src`    | Source code.                                     |

Some of the directories under `src` are external repositories included using
git-subtree. See those directories' README files for more details.


## See Also

API reference: https://dev.xagfans.com/

WTAA protocol: https://github.com/xrpgen/wtaa

