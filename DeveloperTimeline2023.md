# Counterparty Developer Timeline

---

![XCP-logo](https://github.com/davestaxcp/CounterpartyTimeline2023/assets/136373423/ec7d7f16-1059-45dc-b887-7b4101361cc8)


---

Date: **2014-01-02**

Timeline Topic: **Counterparty Launched on Bitcointalk**

Significance: Counterparty Co-Founder user 'PhantomPhreak' posts the first [Official Thread](https://bitcointalk.org/index.php?topic=395761) on the [Bitcointalk](https://bitcointalk.org/) Forums for creating Counterparty. In doing so, the post officially started the publishing of the project and offered [Counterwallet](https://wallet.counterwallet.io/) as a space to experiment with the technology used on top of Bitcoin. 

Related Links: https://bitcointalk.org/index.php?topic=395761

Author: Adam Krellenstein

---

Date: **2014-02-02**

Timeline Topic: **2,648,755 XCP Created in Proof of Burn**

Significance: In order to give the Counterparty project maximum legitimacy right from the start, it was considered fundamentally important that all new XCP cryptocurrency coins are distributed fairly and proportionally. Read more about this process and why XCP creators used [Proof of Burn](https://counterparty.io/news/why-proof-of-burn/).

Related Links: https://counterparty.io/news/why-proof-of-burn/

Author: Counterparty Community

---

Date: **2014-04-15**

Timeline Topic: **Counterparty Codebase Audited by Sergio Lerner**

Significance: Focusing on the security of counterpartyd and the Counterparty protocol, this audit was completed by professional cryptographer [Sergio Demian Lerner](https://en.bitcoin.it/wiki/User:Sergio_Demian_Lerner) between February 24 and April 5 of 2014. Sergio has discovered numerous serious bugs in Bitcoin, and is extremely experienced both developing and evaluating cryptocurrencies. Read more about this audit [here](https://counterparty.io/news/sergio-lerner-completes-independent-security-audit/).

Related Links: https://counterparty.io/news/sergio-lerner-completes-independent-security-audit/
https://en.bitcoin.it/wiki/User:Sergio_Demian_Lerner

Author: Counterparty Community and Sergio Demian Lerner

---

Date: **2014-04-15**

Timeline Topic: **Dividend Payments Added**

Significance: With [this Counterparty upgrade](https://counterparty.io/news/pay-dividends-with-bitcoin/), users could not only issue stocks (Assets) but also now pay dividends in BTC, XCP and any Counterparty Asset to shareholders, automatically and trustlessly. The shareholders do not even need to run a Counterparty client to receive such dividends.

Related Links: https://counterparty.io/news/pay-dividends-with-bitcoin/

Author: Adam Krellenstein

---

Date: **2014-07-13**

Timeline Topic: **Fully Trustless Games**

Significance: Though early and experimental, a "rock-paper-scissors" type game [was introduced](https://counterparty.io/news/introducing-fully-trustless-games-on-blockchain/) using the Counterparty protocol to do so. It was the first step towards trustless multiplayer games (such as poker and chess) that are fully decentralized.

Related Links: https://counterparty.io/news/introducing-fully-trustless-games-on-blockchain/

Author: Dan Anderson

---

Date: **2014-11-28**

Timeline Topic: **Free Numeric Assets and Multi-signature Support**

Significance: [Counterwallet](https://wallet.counterwallet.io/) now supports the creation of free asset names (now called Numeric Assets) and also now supports the creation of multi-signature addresses. 

Related Links: https://counterparty.io/news/counterparty-development-update-4/

Author: Adam Krellenstein

---

Date: **2015-10-29**

Timeline Topic: **Counterparty Improvement Proposals Started**

Significance: A [Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0001.md) is a design document providing information to the Counterparty community, or describing a new feature for Counterparty or its processes or environment. CIPs became the primary mechanisms for proposing new features, for collecting community input on an issue, and for documenting the design decisions that will go into Counterparty.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0001.md

Author: Devon Weller

---

Date: **2015-11-04**

Timeline Topic: **BIP 21 URI on Counterparty**

Significance: [Counterparty Improvement Proposal #2](https://github.com/CounterpartyXCP/cips/blob/master/cip-0002.md) is based off of [Bitcoin BIP 21](https://github.com/bitcoin/bips/blob/master/bip-0021.mediawiki) by Nils Schneider and Matt Corallo. The purpose of this URI scheme on Counterparty is to enable users to easily make payments by simply clicking links on webpages or scanning QR Codes.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0002.md
https://github.com/bitcoin/bips/blob/master/bip-0021.mediawiki

Author: Devon Weller

---

Date: **2016-01-24**

Timeline Topic: **Support for 80-byte OP_RETURN**

Significance: Doubled the amount of data that could fit in an OP_RETURN from 40-bytes to 80-bytes

Related Links: https://counterparty.io/news/counterparty-community-update-jan-02-increasing-op_return-to-80-bytes-devparty-developments/

Author: Ruben de Vries

---

Date: **2016-07-11**

Timeline Topic: **P2SH support**

Significance: Data encoding method that allows counterparty to encode larger amounts of data via chaining 2 transaction, rather than using multisig, which is costly, and pollutes the UTXO set too much.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0006.md

Author: Ruben de Vries

---

Date: **2017-03-15**

Timeline Topic: **Implementation Bounties Established**

Significance: Prior to this process, implementation of Counterparty Improvement Proposals via bounties was performed somewhat ad-hoc. This raised some confusion and exposed several ambiguities, such as potential mismatches in expectations between the individuals donating to the effort and the parties implementing the effort. [This CIP](https://github.com/CounterpartyXCP/cips/blob/master/cip-0008.md) removed these and other potential points of conflict to institute a process that maximizes the chance of success while remaining as lightweight as possible.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0008.md

Author: Robby Dermody

---

Date: **2017-05-01**

Timeline Topic: **Added Subassets**

Significance: [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0004.md) established a protocol for issuing subassets to enable named asset owners the ability and flexibility to issue new easily identified and related named assets (ex: Asset = BACON, Subasset = BACON.crispy).

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0004.md

Author: Jeremy Johnson

---

Date: **2017-09-28**

Timeline Topic: **Enhanced sends with memo field support**

Significance: An asset send transaction during this time required a P2PKH output to the receiver of an asset. This is in addition to the message data output (encoded in OP_RETURN). The additional output was an unnecessary burden that, on average, was five times more expensive to spend than it's worth. The primary use case for a memo field is to identify transactions to merchants and exchanges. [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0009.md) reduced the cost associated with accepting or listing XCP and Counterparty assets.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0009.md

Author: Joe Looney & needmoney90

---

Date: **2017-09-28**

Timeline Topic: **Shortened Transaction Type ID Namespace**

Significance: At this time, each Counterparty message allocated 4 bytes to the message type ID. But it was noted that Counterparty only uses 14 of the 4 billion possible message types. [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0011.md) shortened the message type ID to 1 byte. This saved 3 bytes in every transaction.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0011.md

Author: Devon Weller

---

Date: **2017-09-28**

Timeline Topic: **Memo Requirement through Broadcasts**

Significance: [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0012.md) allowed any user to be able to mark an address under their control as memo-required. This allowed an exchange to mark their address as memo-required, and to reject sends without a memo. Which reduced their support costs. Enforcing a memo requirement at the protocol level also has the added benefit that it can discourage predatory behavior by exchanges, such as allowing sends without a memo, and ignoring any support requests by customers who made a deposit without a memo.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0012.md

Author: Jeremy Johnson

---

Date: **2018-12-28**

Timeline Topic: **Segwit Support**

Significance: [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0015.md) supported spending and creating segwit outputs for Counterparty transactions. By utilizing P2WPKH and P2WSH scripts to send assets, users can spend less on transaction fees sent from counterparty-lib and counterwallet. This adding of segwit compatibility to counterparty-lib also enabled potential future enhancements.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0015.md

Author: Devon Weller

---

Date: **2018-12-28**

Timeline Topic: **Upgrade of Counterparty to use latest Bitcoin and Indexd**

Significance: [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0019.md) presented the necessary steps to get XCP codebase up to date with the latest Bitcoin technology to take advantage of the latest developments in the space including: Faster blockchain sync and parsing, Segwit support for lower fees, Hash Timelocked Contracts (to enable atomic swaps and lightning) and better fee estimation overall.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0019.md

Author: John Villar

---

Date: **2019-10-24**

Timeline Topic: **P2SH data encoding**

Significance: By chaining 2 transactions together it is possible to embed data in the scriptSigs of P2SH outputs. With this method, explained in [the Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0006.md), Counterparty Users could easily put in a lot more data than the other methods used at the time by Counterparty.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0006.md

Author: Ruben de Vries

---

Date: **2019-10-24**

Timeline Topic: **Multi-Peer Multi-Asset Sends (MPMA)**

Significance: Multiple transactions using Counterparty were seeming to be wasteful when the sender already knows who are the recipients and how much of each asset each one needs to receive. [This Counterparty Improvement Proposal](https://github.com/chiguireitor/cips/blob/master/cip-0010.md) established a new send message type geared towards batch processing to send multiple assets to multiple addresses.

Related Links: https://github.com/chiguireitor/cips/blob/master/cip-0010.md

Author: John Villar & Javier Varona

---


Date: **2019-10-24**

Timeline Topic: **Sweep Support**

Significance: Moving assets and ownerships between addresses in large batches had been cumbersome and costly in the past due to how Counterparty addresses are encoded. The "address sweep" message, implemented by [this Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/cip21/cip-0020.md), solved this by sending all the assets owned and ownerships to a target address in one single operation.

Related Links: https://github.com/CounterpartyXCP/cips/blob/cip21/cip-0020.md

Author: John Villar

---

Date: **2020-03-03**

Timeline Topic: **Asset Dispenser Support**

Significance: The Dispenser mechanism, introduced in [this Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/cip21/cip-0021.md), created a new mechanism called 'Dispensers' to swap tokens for on-chain BTC without the need for a third signed message, unlike BTCPay which had already been implemented on Counterparty. A dispenser gives out a fixed amount of tokens for a given amount of on-chain BTC.

Related Links: https://github.com/CounterpartyXCP/cips/blob/cip21/cip-0021.md

Author: John Villar

---

Date: **2021-01-11**

Timeline Topic: **Updated fednode stack to use addrindexrs**

Significance: [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/cip22/cip-0022.md) changed the underlying address index implementation from the currently unmaintained `indexd` service to `addrindexrs` to simplify deployment and make software more responsive.

Related Links: https://github.com/CounterpartyXCP/cips/blob/cip22/cip-0022.md

Author: John Villar

---

Date: **2021-27-01**

Timeline Topic: **Bug fixes on non-divisible dividends and 0 quantity credits**

Significance: [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0023.md) fixed the issue when creating dividends where the payment is done with non-divisible assets over a divisible asset. Also, it changed the protocol to not write 0 quantity dividend credits.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0023.md

Author: John Villar

---

Date: **2022-08-31**

Timeline Topic: **Oracled Dispensers**

Significance: The price assigned to a dispenser is fixed to the given bitcoin amount when opening it, making price swings problematic for dispenser offerings. [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0024.md) created "Oracled Dispensers" by allowing pegging the value of a dispenser to a variable feed multiplier (USD value for example), letting users specify the price of a given dispenser to a multiplier of a feed.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0024.md

Author: John Villar, Jeremy Johnson, Javier Varona

---

Date: **2022-08-31**

Timeline Topic: **Reset Token & Divisibility Statuses for Unused Asset**

Significance: If a Counterparty Asset Owner holds the entire supply and the asset is not locked, [this Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0003.md), allowed the owner to reset the supply (e.g. set the supply at zero) and change the divisibility status.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0003.md

Author: JP Janssen

---
---

# **Drafted Developments**

---
---

Date: **Not Active Yet**

Timeline Topic: **MPMA Send from Multiple Addresses**

Significance: [This Counterparty Improvement Proposal](https://github.com/deweller/cips/blob/cip-13-mcat/cip-0013.md) allows for multiple transactions from multiple addresses to be grouped together in one transaction.

Related Links: https://github.com/deweller/cips/blob/cip-13-mcat/cip-0013.md

Author: Devon Weller

---

Date: **Not Active Yet**

Timeline Topic: **Instant Lottery**

Significance: [This Counterparty Improvement Proposal](https://github.com/Jpja/cips/blob/master/cip-0014.md) Suggests stimulating usage of the Counterparty betting system by having lotteries always available and to not require a human counterparty, nor a trusted human oracle to do so. This would increase demand for XCP from players, and have an automated player that accumulates XCP over time (to a burn address), effectively reducing the supply.

Related Links: https://github.com/Jpja/cips/blob/master/cip-0014.md

Author: JP Janssen

---

Date: **Not Active Yet**

Timeline Topic: **Virtual Machines (non-turing complete)**

Significance: [This Counterparty Improvement Proposal](https://forums.counterparty.io/t/proof-of-concept-vm-development/3031
) looks to develop a minimal pure python Virtual Machine tailored specifically for counterparty.

Related Links: https://forums.counterparty.io/t/proof-of-concept-vm-development/3031

Author: John Villar

---

Date: **Not Active Yet**

Timeline Topic: **Serialized Tokens**

Significance: The idea for [this Counterparty Improvement Proposal](https://forums.counterparty.io/t/serialized-tokens/3486) is to be able to assign each token a unique ID which is tracked through the tokens lifecycle. So if a token is a 1/300, you could track which specific 1/300 out of the rest of the 299 with a unique serial.

Related Links: https://forums.counterparty.io/t/serialized-tokens/3486

Author: Jeremy Johnson 

---

Date: **Not Active Yet**

Timeline Topic: **Atomic Swaps**

Significance: [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/discussions/100) suggests adding Atomic Swaps. Which enable direct peer-to-peer asset exchange by utilizing Hash Time Locked Contracts to ensure secure and trustless transactions. The proposal suggests using Atomic Swaps to eliminate vulnerabilities of dispensers and XCP DEx limitations.

Related Links: https://github.com/CounterpartyXCP/cips/discussions/100

Author: Keyuno

---

Date: **Not Active Yet**

Timeline Topic: **Taproot Support**

Significance: [This Counterparty Improvement Proposal](https://github.com/CounterpartyXCP/cips/blob/master/cip-0030.md) looks to include taproot addresses in the creation and parsing of counterparty transactions. Taproot addresses have become increasingly popular with the creation of [Ordinals](https://github.com/ordinals/ord) and many users look to also manage Counterparty assets on these types of addresses.
Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0030.md

https://github.com/ordinals/ord

Author: Javier Varona and Jeremy Johnson

---

Date: **Not Active Yet**

Timeline Topic: **Picopayments**

Significance: It was proposed to implement this [open source idea](https://github.com/CounterpartyXCP/picopayments-hub) to create a decentral micropayment hub for counterparty assets.

Related Links: https://github.com/CounterpartyXCP/picopayments-hub

Author: Fabian Barkhau

---

Date: **Not Active Yet**

Timeline Topic: **Voting Meta Protocol through Broadcasts**

Significance: With [this idea](https://github.com/CounterpartyXCP/cips/blob/master/cip-0005.md), any user should be able to initiate a vote for all holders of a Counterparty asset. Holders of the asset could broadcast their vote and all Counterparty nodes would be able to tally the votes. With the lack of PoW 'voting' by miners there's no good way to reach / poll for consensus on changes to the protocol that aren't completely uncontroversial. Using this proposed protocol, Counterparty developers can initiate a vote to all XCP holders to learn the will of the community in a decentralized way.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0005.md

Author: Ruben de Vries

---

Date: **Not Active Yet**

Timeline Topic: **Blockchain Validated Asset Metadata (BVAM)**

Significance: [In this idea](https://github.com/CounterpartyXCP/cips/blob/master/cip-0007.md), Blockchain Validated Asset Metadata would provide a mechanism to define detailed information about a Counterparty asset. A hash of the information is stored in the bitcoin blockchain as proof that the metadata is validated by the issuer of the asset. The enhanced asset info standard requires a static URL and a trusted data source. It cannot be used for serverless peer-to-peer sharing of asset metadata. The BVAM standard is more detailed, extensible and does not rely on a single central web server to host the asset metadata file. BVAM provides optional identity validation to prove ownership of a token. The BVAM format is a superset of the enhanced asset info standard and maintains backwards compatibility.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0007.md

Author: Devon Weller

---

Date: **Not Active Yet**

Timeline Topic: **Scheduled Distributions**

Significance: [This idea](https://github.com/CounterpartyXCP/cips/blob/master/cip-0016.md) allows dividends to be scheduled to activate on locked assets, by defining future block height and escrowing funds.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0016.md

Author: Dan Anderson 

---

Date: **Not Active Yet**

Timeline Topic: **Automated Feed with Bitcoin and Counterparty Data**

Significance: [This idea](https://github.com/CounterpartyXCP/cips/blob/master/cip-0017.md) would set up a betting feed with relevant Bitcoin and Counterparty data. This opens up for managing risks, as well as for speculation. This utilizes the existing betting system. Minor protocol changes are required. This proposal will integrate an oracle in the protocol, eliminating the need for a trusted middleman (for data derived from the blockchain). The automated oracle will periodically broadcast values that have real economic impact on users of Counterparty and Bitcoin. This includes the fee level and the XCP/BTC price. In addition it's trivial to add a random number feed which will enable betting on any probability, and potentially be used for future smart contracts.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0017.md

Author: JP Janssen

---

Date: **Not Active Yet**

Timeline Topic: **Enhanced Asset Information Specification**

Significance: Counterparty provides a simple standard for enhanced asset info. This standard is useful, but is limited. By standardizing an [additional set of fields](https://github.com/CounterpartyXCP/cips/blob/master/cip-0025.md) which can be defined in the asset enhancement info JSON file, we can allow for much more information to be associated with an asset in a standardized way.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0025.md

Author: Jeremy Johnson 

---

Date: **Not Active Yet**

Timeline Topic: **Broadcast Token Naming System (BTNS)**

Significance: [This idea](https://github.com/CounterpartyXCP/cips/blob/master/cip-0028.md) establishes a new token naming system via Broadcasts. By establishing 3 pre-defined broadcast formats, users can `DEPLOY`, `MINT`, and `TRANSFER` tokens. With these 3 functions we can create tokens, allow users to mint them in a decentralized "fair" way, and allow for the moving of these new tokens between addresses. This spec can be extended in the future to allow for additional options and formats. This spec was inspired in part by BRC-20 and SRC-20 and seeing the desire to experiment with new token naming systems.

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0028.md

Author: Jeremy Johnson

---

Date: **Not Active Yet**

Timeline Topic: **Crypto Address Messaging System (CryptoMessages)**

Significance: [This idea](https://github.com/jdogresorg/CryptoMessages/tree/master/docs), establishes an address messaging system via Broadcasts. This would allow users to pass messages between addresses. This spec can be extended in the future to allow for additional options and formats.

Related Links: https://github.com/jdogresorg/CryptoMessages/tree/master/docs

Author: Jeremy Johnson & Javier Varona

---

Date: **Not Active Yet**

Timeline Topic: **Asset Issuance Fees**

Significance: [This idea](https://github.com/CounterpartyXCP/cips/blob/master/cip-0029.md) aims to balance the cost of issuing assets with that of running nodes/infrastructure, and to encourage use of broadcasts when issuances are not strictly needed. The CIP suggests a fee of 0.10 XCP for a registering a numeric assets (which are free to mint at this time and only require a btc fee for the transaction).

Related Links: https://github.com/CounterpartyXCP/cips/blob/master/cip-0029.md

Author: JP Janssen

---

Date: **Not Active Yet**

Timeline Topic: **Ordinal Envelopes**

Significance: Ordinal numbers are serial numbers for satoshis, assigned in the order in which they are mined, and preserved across transactions. They are described in Bitcoin BIP [pr1408 ](https://github.com/bitcoin/bips/pull/1408) and implemented with [ord](https://github.com/casey/ord). By integrating Ordinal numbers into the Counterparty federated node stack, they can be viewed through the lens of Counterparty’s account model as one-time use addresses. Ordinal theory is similar to Counterparty in terms of platform consensus. They are both smart contracts deployed as node software rather than as on-chain logic (EVM). [Connecting the Ordinal and Counterparty ecosystems](https://forums.counterparty.io/t/ordinal-envelopes/6504) is prudent for increasing interoperability within the broader bitcoin ecosystem.

Related Links: https://forums.counterparty.io/t/ordinal-envelopes/6504
https://github.com/bitcoin/bips/pull/1408
https://github.com/casey/ord

Author: Joe Looney

---

Date: **Not Active Yet**

Timeline Topic: **Lock Description**

Significance: [This idea](https://github.com/CounterpartyXCP/cips/commit/58268b60fb49a019955847ca8cedd034145d0948) looks to add the function 'LOCK ASSET DESCRIPTION'. While it is good to be able to change an asset description to update broken links and other technical issues... In many cases a permanent as possible option for the asset description is wanted by token creators and holders. Most people that own counterparty assets assume that the description is permanently unchangeable. This update would allow the -option- for asset owners to LOCK the description for all blockchain eternity. 

Related Links: https://github.com/CounterpartyXCP/cips/commit/58268b60fb49a019955847ca8cedd034145d0948

Author: Theo Goodman
