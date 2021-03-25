---
description: >-
  Each digital asset is a finite, secure, transferable and adaptive 'digital
  byte' of data in which all types of "DigiAssets" can be issued, sent &
  received.
---

# DigiAssets

_This article was copied from the preview of the book_ [_Blockchain 2035_](https://blockchain2035.com/)_._

{% hint style="info" %}
_This article may contain outdated information._
{% endhint %}

## Part 1

### Summary

DigiAssets is a secure, scalable secondary layer on top of the global DigiByte blockchain that allows for the decentralized issuance of assets, tokens, smart contracts, digital identity and much more. DigiAssets can be used to securely and cryptographically represent anything we find in the real world. From real-world assets such as real estate, airplanes, boats and cars to scarce digital pieces of art and music. Signed documents such as wills, deeds, and purchase orders to medical bills and advertisement data and info can be protected as DigiAssets.

DigiAssets as an ecosystem and platform already has interested parties planning and or working to build platforms in real estate, finance, remittance, identity, point of sale, racing, trade, healthcare, supply chain, government and more.

DigiAssets leverages unique aspects of a truly decentralized blockchain only found within a blockchain like DigiByte that have never been publicly discussed in most blockchain circles. This allows DigiAssets to be more secure, scalable and decentralized than any other platform yet seen in the market.





### Background

_“You have to know the past to understand the present.”_  - **Carl Sagan**

The idea of building assets on top of a decentralized blockchain similar to how HTTP works on top of TCP/IP started in 2012 with the publishing of the Mastercoin \(later Omni\) [white paper](https://github.com/OmniLayer/spec) in 2012 by J.R Willett.

Mastercoin was launched in 2013 and was officially rebranded to Omni in 2015. Omni to this day serves as the layer Tether is issued on and projects like Factom use to anchor into the Bitcoin blockchain.

Next came the [Open Assets ](https://github.com/OpenAssets/open-assets-protocol/blob/master/specification.mediawiki)protocol after the addition of OP\_RETURN to the Bitcoin blockchain. OP\_RETURN was created to allow for additional data outside of normal transaction data and is used by DGB and BTC to this day. Open Assets was then modified and innovatively expanded upon to become Colored Coins. Colored Coins launched in 2014 and made several enhancements to the structure of secondary layer digital assets and the creation of opcodes of more detailed smart contracts.





### [Technical explanation of OP\_RETURN](https://bitcoin.stackexchange.com/questions/29554/explanation-of-what-an-op-return-transaction-looks-like) <a id="technical-explanation-op_return"></a>

I don't want to go into many details here, but the main reason most of these secondary layers never took off is the bitcoin blockchain filled up and the cost of transactions increased tremendously from 2015- 2019. Because of bitcoins, limited scalability compared to DigiByte superior load capacity \(40x\) at the writing of this article DigiByte is much better positioned to be a base protocol for advanced secondary layer asset issuance. Also, due to DigiBytes 5 mining algorithms, and real-time DigiShield/MultiShield difficulty adjustment DGB is a much more secure protocol to build upon. I will go into this in a future article in greater detail to clean up the confusion on the tech.

The next step in the evolutions of creating and issuing digital assets was Ethereum. Many of the lessons, ideas, and tech learned from Mastercoin, Open Assets and Colored Coins provided the foundation for the creation of Ethereum. Also, originally Satoshi had included many more opcodes when Bitcoin started in 2009 but was later ripped out due to security concerns; a fact often overlooked given the security vulnerabilities and hacks later exposed in Ethereum smart contracts continuing to this day.

For those wanting to learn more about opcodes in computer science look [here](https://en.wikipedia.org/wiki/Opcode).

Ethereum was definitely innovative in adding numerous new opcodes and pushing the limits, but our strategy with DigiAssets is to keep the security, scalability, and rigidity of the DigiByte blockchain with the flexibility and smart contract capability of a secondary asset layer. We are also exploring the possibility of allowing previously written Ethereum solidity smart contracts to become and execute as a DigiAsset.

It is important to note here the opcodes found in Ethereum today have a beginning in structure and format as the Colored Coins opcodes structure.





### [Ethereum Opcodes](https://github.com/crytic/evm-opcodes)

We continue to build upon the creative work of the giants that have come before us. We built the foundation of DigiByte in 2014 upon the work of brilliant Bitcoin core developers, they in turn, along with Satoshi, built upon the pioneering work of cryptographers from the 60s - 2000s to originally build Bitcoin. Just as the brilliant cryptographers of years gone by built upon the work of information theory by Claude Shannon starting in 1948.   
  
We are building upon the open source lessons and insights learned from Mastercoin, Omni, Colored Coins, and Ethereum and combining them into one secure, scalable and innovative secondary DigiAssets layer. We are also incorporating many of the innovations and lessons we have learned over the past 5 years for innovative applications of blockchain tech such as Digi-ID.

Is also important to note in all the above cases, the founders issued their own coins on their protocol in order to fund themselves. In the case of DigiAssets, we are not doing this in order to keep the open source technology as decentralized as possible and we warmly welcome all developers, companies, and parties to contribute to DigiAssets in any way you can.







## Part 2

While some might decide to skip this blog post because it is a “technical overview” I encourage everyone to read through it to learn more about this amazing new open-source addition to the DigiByte ecosystem. It is written in a way to try and convey highly technical concepts in easy to understand descriptive terms. This article consists of three sections:

1. High-Level DigiAssets Overview
   1. The DigiByte "Oreo"
   2. TCP/IP vs HTTP
2. Technical Components of DigiAssets
   1. The OP\_RETURN Output
   2. The DigiAssets Protocol Schema
   3. The "DigiByte" or DigiAssets OP\_CODE Byte
   4. DigiAssets Metadata
3. Running & Using DigiAssets
   1. Walking Through A DigiAssets Transaction
   2. Running Your Own DigiAssets Server
   3. Using Public DigiAssets API
   4. DigiAssets Wallets
   5. Cost of Issuing A DigiAsset
   6. DigiAsset Spam & Bloat





### High-Level DigiAssets Overview

To better understand the relationship between DigiAssets and how it fits in with the DigiByte blockchain, we can compare and contrast it to two easy to understand concepts. The first one of which is the concept of a DigiByte "oreo" or simply a three-layered cake.

#### **The DigiByte “Oreo”**

![](https://cdn.shopify.com/s/files/1/0081/8652/7841/files/Screen_Shot_2019-05-22_at_9.58.36_AM_large.png?v=1558537133)



When looking at the DigiByte ‘oreo’ the bottom layer we see is the protocol and communications layer of the blockchain itself. This is where nodes, i.e. desktops, laptops, and servers running the full DigiByte core client communicate with each other. This is the communications layer where transactions are sent and received and nodes relay blocks from miners etc.    
  
The second or middle layer of the DigiByte oreo/cake is the individual digital asset or cryptocurrency layer. This is where a “DigiByte” comes in as a cryptocurrency or digital asset. Without this asset, people would not be incentivized to run DigiByte full nodes. So think of the cryptocurrency “DigiByte” as the fuel or energy used to run the network. Or think of it as a digital payload through which other assets can be sent and received.   
  
The final top layer is where a whole new world of possibilities occur. This is the applications layer where DigiAssets as a secondary protocol layer resides.  This is also where other innovative platforms and protocol layers such as Digi-ID and others can be created.

#### **TCP/IP vs HTTP**

A more technical example of the relationship between the DigiByte blockchain and the DigiAssets protocol can be found in the relationship between TCP/IP and HTTP.

TCP/IP, short for ‘transmission control protocol and internet protocol,’ was funded and developed as a networking method by the US DoD through DARPA in 1969. It was built to provide end-to-end data communication with specifics on how data should be packetized, addressed, transmitted, routed, and received. As the internet continued to develop, the limitations of this protocol, built strictly for simple computer to computer communications, often in ways humans could not understand, needed to be expanded.

Enter HTTP, the Hypertext Transfer Protocol. HTTP is the underlying protocol used by the World Wide Web and makes it human readable as we know it today. This protocol defines how messages are formatted and transmitted, and what actions Web servers and browsers should take in response to various commands. HTTP data is embedded in TCP/IP packets just like DigiAssets data is embedded in DigiByte transactions. And just like HTTP allows for the internet we know today to exist, so will DigiAssets allow for a major explosion of new user experiences on top of DGB. We are helping transform the internet from simply an internet of information to an internet of value, and value transfers.







### Technical Components of DigiAssets

_In this section, we will outline the four major technical components of what makes DigiAssets possible as a protocol asset layer on top of the DigiByte blockchain._

\_\_

\_\_

#### The OP\_RETURN Output

The OP\_RETURN output is the primary way that DigiAssets are sent and are layered into the underlying DigiByte blockchain.  We will go into more detail in this section on how OP\_RETURN is used in a transaction. For a detailed explanation on how DigiByte & Bitcoin transactions work in technical detail please see here: [https://bitcoin.org/en/transactions-guide](https://bitcoin.org/en/transactions-guide)  
  
OP\_RETURN is a transaction type that allows us to add arbitrary data to a provably unspendable pubkey script that full nodes don’t have to store in their UTXO database. Effectively it's a way of adding null data to a blockchain transaction without bloating a public chain like DigiByte or Bitcoin. An  OP\_RETURN output gets added to any DigiByte transaction that's being utilized by the DigiAssets protocol to issue, send, receive or burn an asset. OP\_RETURN is limited to holding 80 bytes of data. Trying to attach any more than 80 bytes to the OP\_RETURN output will cause a transaction to be rejected by the rest of the DigiByte network.







#### The DigiAssets Protocol Schema

Given there is a very tiny amount of data that we can fit into at OP\_RETURN output of a DigiAssets DigiByte transaction we need a very efficient way of utilizing that space. Since OP\_RETURN is limited to 80 bytes of capacity we need a way to encode the entire protocol schema. Because of the beautiful use of cryptography we are able fit the entire DigiAssets protocol scheme in those 80 bytes. The schema also changes depending on whether the DigiAssets transactions is an issuance, a transfer or a burn. Here is how these 80 bytes in an issuance are broken down. [**Read more**](https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/DigiAsset%20Scheme)\*\*\*\*

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Bytes</b>
      </th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Comments</th>
      <th style="text-align:left">Stored in</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">2</td>
      <td style="text-align:left">Protocol Identifier</td>
      <td style="text-align:left"><code>0x4441</code> ASCII representation of the string DA (&quot;DigiAssets&quot;)</td>
      <td
      style="text-align:left">OP_RETURN</td>
    </tr>
    <tr>
      <td style="text-align:left">1</td>
      <td style="text-align:left">Version Number</td>
      <td style="text-align:left">Currently <code>0x02</code>
      </td>
      <td style="text-align:left">OP_RETURN</td>
    </tr>
    <tr>
      <td style="text-align:left">1</td>
      <td style="text-align:left"><b>Issuance</b>  <a href="https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/OP_CODEs">OP_CODEs</a>
      </td>
      <td style="text-align:left">The &quot;DigiByte&quot; - aka where the magic happens</td>
      <td style="text-align:left">OP_RETURN</td>
    </tr>
    <tr>
      <td style="text-align:left">20</td>
      <td style="text-align:left">SHA1 Torrent Hash</td>
      <td style="text-align:left">(optional), only when metadata is included</td>
      <td style="text-align:left">OP_RETURN or (1|3) Multisig</td>
    </tr>
    <tr>
      <td style="text-align:left">32</td>
      <td style="text-align:left">SHA256 of <a href="https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/Metadata">metadata</a>
      </td>
      <td style="text-align:left">
        <p>(optional), only when metadata is included.</p>
        <p>Allows for torrent metadata verification</p>
      </td>
      <td style="text-align:left">OP_RETURN or (1|2) or (1|3) Multisig</td>
    </tr>
    <tr>
      <td style="text-align:left">1-7</td>
      <td style="text-align:left"><a href="https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/DigiAsset%20Scheme#amount">Amount</a> of <b>issued units</b>
      </td>
      <td style="text-align:left">Encoded with the [Encoding Schema](Number Encoding)</td>
      <td style="text-align:left">OP_RETURN</td>
    </tr>
    <tr>
      <td style="text-align:left">2-9 (per instruction)</td>
      <td style="text-align:left">[Transfer Instruction](Transfer Instructions)</td>
      <td style="text-align:left">Encoding the flow of assets from inputs to outputs</td>
      <td style="text-align:left">OP_RETURN</td>
    </tr>
    <tr>
      <td style="text-align:left">1</td>
      <td style="text-align:left"><a href="https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/DigiAsset%20Scheme#issuance-flag">Issuance Flags</a>
      </td>
      <td style="text-align:left">At the moment only 6 bits are used</td>
      <td style="text-align:left">OP_RETURN</td>
    </tr>
  </tbody>
</table>

As you can see the first byte lets us know it's a DigiAsset by flagging it with "DA" or `0x4441` in hex to let the DigiAssets software know it should kick in and parse the OP\_RETURN data for info on the DigiAsset.





#### The "DigiByte" or DigiAssets OP\_CODE Byte

A single key byte of data in the schema above is where the instructions for what to do with all DigiAssets and how they are encoded is kept. We like to call this key byte of data, the “DigiByte” as this digital byte of data unleashes a whole new world of possibilities for securing and processing an internet of value. This is where the heart of DigiAssets lives.

This single byte of data gives us up to 128 possible OP\_CODEs or the basis for expanding DigiAsset smart contract code and the development of a DigiAssets programming language. So far 25 out of the possible 128 OP\_CODEs have been defined. Here are the codes currently in version 1 of DigiAssets for issuance and transfer.  See more [here](https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/OP_CODEs).

![](https://cdn.shopify.com/s/files/1/0081/8652/7841/files/Screen_Shot_2019-05-22_at_9.59.49_AM_large.png?v=1558537245)

It is important to note these codes were the same starting point for Ethereum in 2014, and we can potentially port some of the OP\_CODEs developed by Ethereum over the past 4 years. By separating DigiAssets OP\_CODEs from the main level DigiByte protocol OP\_CODEs we can mitigate the risk and minimize the attack surface that having numerous OP\_CODEs creates.







### DigiAssets Metadata

_The final main component of DigiAssets is the metadata. The metadata can include whatever you want it to include. You can attach as much or as little metadata as would want to, as in the end you are just taking a cryptographic hash of the data and storing that hash. You can also define whatever fields or custom smart contract code you want to include as metadata._

_Metadata is structured in a JSON format and can be distributed as a torrent. It can also be stored in IPFS, in an AWS bucket or as a blob on Azure or on your local laptop or phone. It's really up to you how you want to handle your DigiAsset metadata.  
  
In theory, you could hash an entire high definition major motion picture which would take up terabytes of data and include it as metadata. The key is you just have to store it somewhere you can access it. Metadata is also not required to issue, transfer or create a DigiAsset._

_One final note on metadata. There is a big opportunity for new business models and service providers to step up and provide innovative ways for securely storing metadata for DigiAsset smart contracts and assets. Ideally, companies and users should secure and store their own metadata, but it is also important to make metadata easy to handle and easy to access in a secure way._ [_**Read more about Metadata**_](https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/Metadata)_\*\*\*\*_

_\*\*\*\*_

_\*\*\*\*_

#### _Running & Using DigiAssets_

Let's take a deeper dive into how you can get up and running with digiassets as a user or a developer.





#### _Walking Through A DigiAssets Transaction_

The first step in creating a DigiAsset transaction is you need to create a regular DGB transaction with a tiny amount of DGB. Once that is done we add an OP\_RETURN output with all the schema & OP\_CODE data outlined above that is needed for your particular DigiAsset. Once that data is added you broadcast that transaction to the network either through your own client or by using a publicly available API. Normal nodes and clients ignore the OP\_RETURN data and it doesn’t bloat the DigiByte blockchain with unnecessary data. Wallets and services running DigiAssets enabled software can then pars OP\_RETURN for instructions on how to handle the DigiAssets in your wallet or the platform they are received on. For a code example on how this works [**see here**](https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/Getting%20Started)**.**

\*\*\*\*

\*\*\*\*

**Running Your Own DigiAssets Server**

DigiAssets itself consists of several individual open source GitHub repositories. We as core developers do provide a demo server software stack for main net and testnet for people to learn and help development on top of in order to encourage adoption of DigiAssets. We do however limit how much traffic and volume these public facing servers provide. We also disable issuance on our public API on mainnet and don’t store metadata which will be touched on later. Testnet has no restrictions, but the metadata and other data are often deleted as its a tiny server.  
  
We want to make sure each company, or group or power user of DigiAssets is running their own DigiAssets full stack server & API to support any platform or app they build. In order to issue your own DigiAssets you will need to run your own DigiAsset server. Our open source wallets will, however, allow you to send, receive and burn assets.

To run your own DigiAssets server stack and API you will need the following four software repositories. You will need digibyted, digiassetsd, DigiAssets Block Explorer and the DigiAssets Metadata Handler. Once you have these 4 services running and configured you will have a fully independent server stack running for your DigiAssets application or use case. You can view the full guide and links to these [**repos here**](https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/API%20Docs)**.**

\*\*\*\*

\*\*\*\*

#### Using Public DigiAssets API

As mentioned above we do provide a public api for mainnet and testnet for developers to use during testing and development of their apps. We do however for legal, ethical and anti-spam reasons have the ability to issue an asset disabled on the public mainnet api. Also storing massive amounts of metadata is prohibited.

We are also closely monitoring to make sure as the DigiAssets public API’s are not abused. If you are building a front-facing consumer application you need to run your own DigiAssets server stack and API. You can find more about the public API endpoints [**here**](https://github.com/DigiByte-Core/DigiAssets-Protocol-Specifications/wiki/API%20Docs)**.**

\*\*\*\*

\*\*\*\*

#### DigiAssets Wallets

Right now there are three main wallets that we are building support into for DigiAssets. These include the DigiByte Go wallet, DigiVault, and the DigiByte mobile Android and iOS wallets.   
  
The DigiVault wallet currently works and anyone can find it on the DigiByte-Core GitHub and install it themselves from core source code. The problem is it requires Redis-server, a full DigiByte client and is very slow and cumbersome. It's not exactly user-friendly at the moment, but it is a fully working wallet for DigiAssets. You can find [**DigiVault code here**](https://github.com/DigiByte-Core/DigiVault)**.**  
  
DigiByte Go + DigiAssets is nearing release and will be a fully functioning wallet that will get people started right off the bat with no delay for sync times. You can find the code and or help us with development on it [**here**](https://github.com/DigiByte-Core/digibytego)**.**

{% hint style="warning" %}
**DigiByte Go is currently not functional and should be avoided.**
{% endhint %}

The DigiByte mobile wallets are being worked on in order to allow people to send, receive and burn DigiAssets. The great thing about the mobile wallet it is a fully independent SPV wallet that connects directly to the DigiByte blockchain and does not require access to a backend API to sync itself to the blockchain. You can find the code and help us out here for [**Android**](https://github.com/DigiByte-Core/digibytewallet-android)**.**

And here for DigiByte [**iOS**](https://github.com/DigiByte-Core/digibytewallet-ios).  
  
In the future, once all kinks are worked out we will be working to get DigiAssets into other wallets and onto exchanges.





#### Cost of Issuing A DigiAsset

To issue your asset on the main DigiByte blockchain, you will need to pay a small network transaction fee that will be distributed through the network as a mining reward to whoever mines the block the DigiAssets transaction is contained in. This fee will never go to any specific individual DigiByte entity or group of people. If we as DigiByte core developers or any other centralized group ever took that fee directly, it would undermine the entire concept of decentralization in a trustless environment that we have achieved with DigiByte thus far. The exact cost of that fee for as a DigiAssets transaction is yet to be determined, and we open that discussion up to the community. The reality is there needs to be a small fee in order to prevent bloat and spam attacks on the network. For right now during development and testing the current fee is a normal DGB transaction fee.





#### DigiAsset Spam & Bloat

As mentioned above, if there were no DGB transaction fee people could easily spam thousands of DGB or DigiAsset transactions with an automated script that could grind the entire blockchain to a halt. With DigiAssets we still have that problem but we also have other potential ways people can abuse the protocol.   
  
An example of asset issuance gone awry can be seen recently with Ravencoin. One look at their asset explorer can demonstrate how DigiAssets can be abused with wallet annoying, crude and embarrassing asset advertisements. It's easy to query the blockchain and see the top 10,000 addresses that recently received a transaction and then sent a tiny amount to that address of an Advertisement Asset. If costs are trivial this can become a massive problem which is why we as developers are discussing ways to make this type of wallet ad spam very costly to bad actors.

There are public discussion threads where users quickly got tired of their Raven wallets receiving “HERPES” “PAYDAYLOANS” and “ICO advertisements.” This is one of the main reasons we have no plans on bringing native DigiAssets support to the DigiByte core QT wallet anytime soon or implementing DigiAssets natively into the core DigiByte blockchain code. We want to make sure we do not involuntarily introduce new security vulnerabilities or bad user experience to DGB.





#### Conclusion

I originally wanted to talk about types of DigiAssets and specific use cases along with what future developments of DigiAssets will entail in part 2 but this blog post quickly lengthened. I will be writing a part 3 where we will take a deeper dive into different types of DigiAssets and specific examples. Until then if you are a developer we could use your help getting DigiAssets streamlined and bug-free in our wallets. Join us in the DigiByte developers chat on Telegram to learn more about how. Or just submit a PR on GitHub. :\)

