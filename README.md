# Bither: The New Eco-Friendly and Layered Decentralized Economy

![COVER](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/cover.jpg)

## Abstract
Bither presents an entirely new platform based on a synthesis of several methods. By introducing Merged-Mining capability and also optimizing computing power consumption, Bither sets its goal to draw more computing power toward its network through an efficient mining algorithm.
 
Bither works with “Proof of Work” (PoW), as its consensus algorithm, though with a different architecture and distinct functions compared to Bitcoin, Ethereum, and many other similar networks. Bither’s innovation is in its calculation of network hash rate and automatic separation of computing power by using trusted masternodes. Through a hybrid method, these masternodes are defined and implemented in high numbers. Moreover, each masternode’s information is compared to other masternodes and there is an automatic and precise supervision over the accuracy of the computations and their orders.
 
In this method, masternodes are equipped with a new processor core (software). Through this processor core, the entire hash rate of the network is calculated before being divided into four major parts:

1. M percent of the network's total hash rate is allocated for mining new coins, recording transactions, securing the main network, and checking and executing smart contract algorithms on Bither's main network.
2. N percent of the network's total hash rate is distributed among networks of the second layer. This computing power is used for recording and confirming transactions in networks of the second and third layers. It is also used for computation and summarization of the network's internal transactions.
3. This part is shown by the percentage marker of K. Through the miners’ decision and selection, this part is assigned to operational projects; these are projects that run on the Bither network and need computing power for their processing.
4. The last part is introduced by the percentage marker of L (L=100-M-N-K). This part is assigned to a third-layer network in which miners can lease their excess computing power, The token that is used in this network is called Rental Processor.

By implementing a modern architecture for mining and defining trusted masternodes, the Bither platform presents a new solution to the current problem of mining centralization. The role that masternodes play in the distribution of hashing power is an innovative approach to solve the problem of ASICs. This way, ordinary have a chance to mine as well.
 
Bither has presented a completely new platform that has many advantages in executing smart contracts, setting up scientific projects that need computing power, creating second and third layers toward the categorization of activities for tokens etc. Some of these advantages go as follows:

* Optimized use of energy with the multi-mining ability to incentivize miners
* The possibility to create thousands of sidechains in the network
* Recording transaction details on the sidechains rather than the main network
* Not needing Bither balance for the sidechain transactions
* A standard platform where scientific projects can purchase their required computing power.
* Providing the required hashing power for mineable projects at the start of their activity
* Profitable mining during market downturns
* Defining a safe and secure standard to prevent fraud in the initial coin offerings (ICO)
* The possibility to define and create holding companies
* Setting up decentralized and user-friendly exchanges

To conclude, the Bither platform -while providing all features of current PoW based blockchains such as security, “tokenization” and smart contracts, aims to push blockchain technology one step further in order to have a place in a green and eco-friendly future and to be a great help for scientific projects in order to afford the process of big data. Besides these, Bither has also brought many innovations to make its platform more efficient and user-friendly.

# Topics

1. [Introduction](#introduction)

    1. [Blockchain technology and general information about its function](#blockchain-technology-and-general-information-about-its-function)
    
    2. [Major applications of Blockchain technology](#major-applications-of-blockchain-technology)
    3. [Token](#token)
    4. [Smart contracts](#smart-contracts)
    5. [Some capabilities of smart contracts](#some-capabilities-of-smart-contracts)
    6. [A study of the most important challenges of Blockchain based networks](#a-study-of-the-most-important-challenges-of-blockchain-based-networks)
2. [The architecture of the Bither platform](#the-architecture-of-the-bither-platform)
3. [The Bither Stock network](#the-bither-stock-network)
4. [Innovations and attractions of Bither](#innovations-and-attractions-of-bither)
5. [Practical examples applicable to the Bither network](#practical-examples-applicable-to-the-bither-network)
6. [How distribution and mining work on the Bither platform and the Bither Stock](#how-distribution-and-mining-work-on-the-bither-platform-and-the-bither-stock)
7. [Distribution method of the Bither platform’s token (BTR)](#distribution-method-of-the-bither-platforms-token-btr)
8. [Distribution method of the Bither Stock’s token (BSK)](#distribution-method-of-the-bither-stocks-token-bsk)
9. [The distribution method of the Bither Rental Processor token (BRP)](#the-distribution-method-of-the-bither-rental-processor-token-brp)
10. [Details of the initial coin offering (ICO)](#details-of-the-initial-coin-offering-ico)

## Introduction

### Blockchain technology and general information about its function

A blockchain is a distributed ledger that can record transactions or any other information in continuously growing blocks. Through using a cryptographic hash, these blocks, when created, would be immutable, It means that once any information is recorded in the system, they can never be deleted or changed. It makes blockchain a great solution in any situation where recording data needs to be traceable, transparent and performed by untrusted members of a network.
 
The blockchain technology has made it possible for a digital and decentralized currency to become operational. Far more than being just an underlying technology of a cryptocurrency, blockchain technology is going to be as revolutionary as the historical inventions such as steam or combustion engine. This technology can revolutionize the digital world; using the ‘distributed consensus' feature for each old or new online transaction, it can process transactions that allow digital assets to be identified in the future. And this is all possible without any risk against one's privacy, in a secure environment for the digital assets in all sides of the transaction.
 
Due to the requirement of a trusted third party, online financial transactions have become the monopoly of a few corporations, leading to an unnecessary increase in transactions fees.
 
Using cryptography, digital signatures, and subsequent verification by other participants (known as miners) in the network, blockchain does not rely on any central node or third party in a transaction process. Every transaction is secured by a digital signature. Each transaction is digitally signed by the sender's private key before being sent to the receiver's public key. In order to be able to spend any amount of money, the owner of the money needs to prove that they own the private key. By using the public key of the sender, a miner identifies the digital signature (ownership of the private key) and if correct, confirms it (the miner runs some other checks and marks the transaction as valid).
 
Each transaction is broadcasted across the network by a node and after identification, it is recorded in the ‘distributed ledger'. Before being recorded in the ‘distributed ledger', every single transaction must be identified and validated. In advance of any transaction, the identifying nodes must make sure of two things:

* The sender has a validated digital signature for processing the transaction.
* The sender owns enough currency in their account. All transactions of the sender’s account (public key) must be controlled in the distributed ledger so that sufficiency of the account’s holding gets validated.

**Figure 1**
![Figure 1](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/1.png)

Here an issue is raised: Keeping the order of transactions that are broadcasted to other nodes in a blockchain’s peer-to-peer network (like bitcoin). The transactions are not necessarily processed in the order in which they are created, thus the system has to contrive a way to prevent double spending, to achieve this, transactions must be transferred node by node along the network. Note that there is no guarantee that the order of receiving the transactions by nodes corresponds with the order of their creation.

**Figure 2**
![Figure 2](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/2.png)

This means that a mechanism is needed through which the whole blockchain network can agree on the order of transactions. The system puts transactions in a group of blocks and then arranges them by connecting each block to the previous one through a cryptographic hash. These blocks are connected to each other like chains in one line in a time sequence. Each block saves a hash output of its previous block.

**Figure 3**
![Figure 3](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/3.png)

The next problem to solve is that every node can arbitrarily create a block of transactions and broadcast it on the network as a suggestion for the next block. If, at any given time, different blocks are created by different nodes, which one should be considered to be valid? As long as blocks can be received in different orders in different parts of the network, no order can be trusted. Blockchain has solved this problem by introducing a match puzzle. Any block that wants to be added to the blockchain, has to contain an answer in its content for a unique ‘math puzzle’. That answer is called ‘Proof of Work’. A node that creates a block must be able to prove that it has enough computational resources to solve the ‘math puzzle’. For example, a node needs to be able to find a random number (nonce) with which it can generate the hash output of the next block which starts with a certain number of zeros. The number of zeros at the beginning of a block’s hash vary due to the difficulty of the network(the more hash power a network has, the more zeros a block’s hash needs to have), but the verification  process is very simple and can be done by verifying the hash regarding the input data.

**Figure 4**
![Figure 4](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/4.png)

Solving this math puzzle is time-consuming and its complication is adjustable, for example, the complexity of the puzzle can be adjusted so that the average time of its solution by a node in the bitcoin network (for creating a block) is 10 minutes. The possibility of the creation of more than one block in the system during the allocated time is very low. The first node to solve the puzzle broadcasts its own block to the rest of the nodes in the blockchain. If in a special circumstance more than one block is created simultaneously, it leads to the creation of different branches. However, the math puzzle is complex enough for the blockchain to be stabilized quickly and all nodes would agree on the chain order of recent blocks.

On the other hand, the network recognizes only the longest blockchain as the valid one. As a result, it is almost impossible for an invader to define a fake transaction because not only do they have to generate a block that has solved the mathematical problem, but they should also simultaneously recreate previous blocks in a way that other nodes in the network consider valid. This process gets even more difficult due to the fact that blockchains are connected to each other by hash.

### Major Applications of Blockchain Technology

The term “blockchain” is applicable to any network in which information is recorded by numerous untrusted members, and the blocks are chained together by a proof. As a result, this technology has fundamentally challenged and changed the world of business. Moreover, by reducing the need for any central institutions such as banks, this technology grants the full control of financial affairs to ordinary people. A new form of trade that is known as ‘pull transactions’ has been formed which has created a lot of enthusiasm; an enthusiasm that is certainly due to high hopes that specialists have for applications of blockchains. Some of the most brilliant thinkers of the computer science world go so far to call blockchain technology The Magic Beanstalk. Some of these applications are as follows:

* International Payments

In blockchain technology information is shared in the format of blocks; it is very fast and transparent; it can be supervised and confirmed by everyone; due to its immutable nature, blockchain technology provides a great alternative for current slow, risky and expensive cross-border transactions and global payments.

* Peer to Peer Transactions

Naturally, when you attempt to move money internationally, you have to use a mediator which is probably going to be a bank or a FinTech company, but with blockchain technology, this transfer is peer to peer, and the mediators can be easily excluded.

* Auditing

The secure and immutable nature of the blockchain technology has facilitated macro auditing for users (even the case owner cannot edit anything within this technology). Banks and other big Payment Service Providers -through which people perform their online digital transactions- protect their clients' account information against hackers by using client-server infrastructures. To achieve that, they spend billions of dollars to protect their clients' information. Likewise, any online transaction system is responsible for the protection of their clients' information. After all, the same information that we share with banks, we share with businesses too. However, since all online businesses are vulnerable to attacks or hacks, the safety of sensitive financial information is always in jeopardy. By contrast, Blockchain improves security, mitigates fraud and automates the process of auditing. Therefore, a permitted blockchain with some restrictions in accessing sensitive data will bring cost efficiencies for auditing.

* Financial Agreements, Payments, and Taxes

Sometimes in the stock market, we hear the phrase T+3. This phrase means that a Transaction (T) will be finalized in three days. There are ways to speed up this process but they come with security risks. With blockchain technology, a transaction is immediately finalized, so we would have a T+0 settlement date. Moreover, the transparent nature of blockchain reduces the chances of error in the tax payment process to its lowest level, if not zero

* Insurance

Sometimes individuals and companies buy several insurance policies from different companies, and then fraudulently create a self-made damage claim, attempting for earning illegitimate profits. The nature of blockchain is set up in such a way that any recording information is done uniquely. By simple coding, it can become unrepeatable too. So, no ‘natural' or ‘legal person' would be able to commit fraud.

* Preventing Money Laundry

If receivers and senders have unique addresses in the blockchain, all identity verification standards (KYC) and anti-money laundering regulations (AML) can be applied in which case there will be a very secure and fast anti-money laundering system. By combining and integrating accurate and valid identity verification blockchains with blockchain payment systems, the best supervision and transparency will be applied to such transactions. On the other hand, blockchain is able to encrypt legal settings. In other words, the verification process and function of blocks in blockchain can be a translation of legal governmental processes into digital codes. For example, regarding the banks, this leads to an increase in the efficiency of anti-money laundering situations. Blockchain can be set to take different responsibilities, for example, allowing a transaction to take place or according to regulations that are applied to it, we send the report of the transactions that have taken place to the responsible people. This enables the banks to automatically process their transactions or their transaction reports.

* the Supply Chain Management

A blockchain makes the history of transactions traceable. The supply chain management can take advantage of this feature in tracking the goods from manufacture to sale in a decentralized way and with any number of participants. Since there are many people in different time zones and places involved in the supply chain, the blockchain, due to its decentralization nature, makes a global supply chain operating system possible, It also reduces human errors, makes the recording data more accurate and scalability easier.

* Medical Care

Sex, age, height, and other personal characteristics, along with the latest examinations, medical diagnosis, etc., can be stored in a blockchain. When necessary, with permission from the concerned individual or anyone responsible for them, the doctor -without needing any mediator organization and thus without wasting time- can have access to necessary information. This happens without any time or places restrictions. Using this method, the doctor can have access to medical records and thus make a better diagnosis which eventually leads to better treatment.

* Real Estate

Using local real estate agents to buy and sell properties makes the land recording fragmented. Also, a centralized listing service (as an alternative) is hard to achieve. In contrast, while we can keep current fragmented listing data, blockchain significantly improves the search process. It also gives more accuracy in the due diligence process.

* Media and entertainment industry

Through a blockchain-based platform, content creators (writers, photographers, artists, video makers etc. ) can reach their audience and sell their contents without needing third parties which in this case are big media companies. Content distribution becomes faster, simpler, more secure and less expensive both for content creators and customers, and the current monopoly of media distribution can be broken.

* Management of Inter-organisational Documents and Information

Blockchain technology has revolutionized the way information is gathered and recorded. In fact, more than being a database, a blockchain is a system of record keeping management. We have seen the compromisation of systems that led to changes of data many times before using the blockchain technology, this information will be immutable that even the strongest hacking systems in the world won't be able to make changes in the database. Easy management of documents and the decrease in various kinds of fraud are instances of these technological advantages.

* Management and Personal Identification

There are many people who fake or change their identity and commit unlawful activities. If by using different methods, people's identities are determined and stored in a blockchain, we will never witness such a misuse. The cryptography used in the technology, have created new ownership rights that are forming interesting digital relations. In fact, blockchain has created a new opportunity for creating a strong system of ‘digital identification’. This is due to the fact that blockchain has not been created on the basis of user accounts and licenses that are made available via user accounts; this is a ‘pull transaction' and ownership of private keys which means the ownership of the digital assets. These conditions provide a safe and new way of management for people's personal identity in the digital world: no one shares their personal information more than it is needed.

* Election

In a centralized world, security is never guaranteed. It means that hackers can penetrate into election systems and change the results. By using the combination of the PoW mechanism and the cryptographic technology in the blockchains, we are able to overcome such problems.

* Using Blockchain in Stock Markets

Another way to look at cryptocurrencies is to consider them as securities or bonds. This means by creating a unique digital identity for cryptography keys, a special form of ownership rights is formed (for example these codes can own or be owned). The ownership of these codes can be introduced as a shared, physical commodity or any other modes of an asset. Using blockchain protocols, these rules can be turned into codes.

* Humanitarian aids

Recent researches show a common distrust among the public toward charity organizations. Blockchains’ transparency will bring back the public's trust and will lead to donations for projects and programmes that will benefit everyone.

* Independent Organisation

Bitcoin itself is an example of an independent government or in other words a ‘DAO' (Decentralized Autonomous Organisation). Blockchain technology has made it possible for management models to be digitized. Whenever there is a disagreement between a network's users and shareholders, by voting among the members, an appropriate route for a collective decision can be taken. Ethereum has introduced new features in this area. Considering past records, it seems like the implementation process of such organizations should still be reviewed and corrected even more closely.

* Internet of Things

Current networks cannot guarantee complete security. With blockchains, however, it can be almost certain that physical objects that are controlled by blockchain, will function correctly even in the face of subversive manipulations. All mentioned blockchain use-cases allow people to secure their digital interactions in a way that was not possible before. People's financial and personal data is gathered, secured and stored in a different way from the past. By automatization and smartization through smart contracts, digital interactions can be fundamentally changed.

### Token

The word token is referred to whatever is used as a symbol for money in a machine. Tokens are not necessarily limited to one platform; they indicate that you have a tradable asset. By running a project on a blockchain, developers (or startuppers) are able to define their own customized token for facilitating transaction processes, asset management, and distribution.

For example, consider a project that is supposed to set up a computer game, In order to purchase the advanced equipment for the game, this project needs its own unique currency. Without getting engaged in coding and setting up a professional blockchain, developers can effectively and in the shortest possible time (in platforms that have this possibility -NEX, Omni, Ethereum etc.), create a customized token. Companies can use different methods to define a token accurately to specify how many tokens are or will be released and how the users and investors can obtain these tokens.

Of course, the first and biggest advantage of using a blockchain for practical tokens is that the number of any token is specified at the very outset. This means that companies and organizations cannot manipulate or issue countless tokens that can reduce the value of the token or cause inflation. In fact, there is a public supervision over the distribution of the tokens to prevent any manipulation.

At the outset, the purpose of Tokens was to represent real-world assets that are physically difficult to transfer or safeguard in a payment ecosystem. For some Blockchains, tokens are as necessary as fuel for engine; they have become an integral part of the platforms running on these blockchains. In fact, tokens are now the currencies of new economic systems with a real market value of their own.

**Figure 5**
![Figure 5](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/5.png)

It is said that one of the biggest steps in the world of blockchain was the possibility of creating tokens without a blockchain of their own. This made it possible for projects to possess their own customized tokens (to be distributed and managed independently from the main coin) while benefiting from the advantages of a blockchain. This way, one single blockchain can function for numerous projects with various use-cases. It helps to save energy and attract funds in a more convenient way.

### Smart Contracts

The next progressive leap in functional and targeted development of blockchain across the industries and in different areas of life is the incorporation of smart contracts in the blockchain technology.

Smart contracts are special protocols that become active in order to make it possible to take part in, confirm, or execute the contents of any contract. Smart contracts perform transactions and interactions in a secure way and without a third party. Activities and records of smart contracts can be traced and are irreversible. The conditions of a legal contract, insofar as possible, is translated into computer codes and are executed automatically at the given time.

This idea was first proposed in 1994 by a computer and encryption scientist named Nick Szabo. He set the main principles of the idea but at that time there wasn't a suitable environment for the realization of that idea to manifest. With the emergence of blockchain technology, the idea of smart contracts was soon realized. In order to create a smart contract on blockchain the following items are needed:

* The subject of the Contract: This programme needs to have access to the products or services that the contract is about, so it can automatically control them while they are being bought or supplied.
* Digital Signature: All parties start the agreement by signing the contract with their private keys.
* Conditions of the Contract: Conditions of the smart contract are accurate in continuation of a series of predefined operations and their actions. All parties must sign these conditions. Not only rules and conditions are defined by smart contracts in the same way that a traditional contract does, but also automatically enforce those obligations.
* Unique and Exclusive Platform: Smart contract gives blockchain technology a unique platform that is distributed among the concerned platform nodes.

Simply explained, a smart contract is a special computer code in a blockchain that gets executed by one node. When that happens, the distributed ledger gets updated and the result will be accessible for everyone. Smart contracts are like IFTTT (If This Then That).

In smart contracts, no individual or institution is able to control a contract. If the content of a contract is correct, that contract gets executed automatically.

### Some Capabilities of Smart Contracts

* The ability to process ‘multi-signature’ contracts. In these contracts, financial resources are spent only when a specific percentage of the shareholders agree to it 
* Management of contracts between individuals, such as buying insurance from someone else.
* Providing functional capability for other contracts (such as software libraries).
* Storage of information about an application such as registration of a domain or profile information.

As an example, imagine a person who goes to the doctor. After the visit, the doctor prescribes a prescription drug in the examination. The doctor also advises the patient to contact the secretary after getting the examination results, to receive a new prescription (adjusted to the results) via email. But the patient takes the drugs irregularly and completely forgets about the examination. Obviously, this is not good. Now let's see how blockchain technology can change the scenario.

The patient receives an appointment with the doctor. This gets recorded on blockchain and the contract gets executed. By recording the patient's information on the blockchain distributed ledger, the next contract gets activated and executed which would include sending the patient's medical record to the doctor, sending a message to the patient and setting alarm on the patient's watch for the appointment day. On the day of the appointment, an SMS is sent to the patient, as a trigger to activate the next contract. In the contract's code, there is a doctor prescription which is recorded in the blockchain's distributed ledger by the doctor after the examination. The patient goes to the pharmacy and by only giving their blockchain address and their digital signature on a special device sees the prescription and receives the prescribed drugs. At the same time, the patient is referred to a lab close to where they live, and a day and time is set. At the same time, a trigger is sent for the next contract so that once again the patient receives the day and time via an SMS and vibration on their smartwatch. The examination day arrives, and the patient is notified of the time of the examination. They go to the lab and by giving their blockchain address and digital signature they are identified. The system sends a trigger for the next contract so that the results are saved on the medical record. The examination is done, and the result is saved on the patient's medical record. Simultaneously another trigger is sent for the next contract so that the new prescription is sent to the patient's email. The patient goes to the pharmacy and like before, receives their drugs.

### A Study of The Most Important Challenges of Blockchain Based Networks

1. **Security and recording of transactions:** The most important issues in a blockchain are security, verification, and recording the transactions. When a block of ‘transaction information' is processed successfully, all transactions in that block are confirmed and recorded. This happens during the mining process.

One common method of recording and verifying transactions is a mechanism known as ‘Proof of Work’ (PoW). While PoW is commonplace in blockchains, technically it is of no use except for keeping the network secure. This method engages thousands of powerful computational resources just for finding random numbers. Since these computations require a huge amount of energy, cryptocurrencies can no longer rely on such methods in order to survive in the future, especially considering the fact that the current societal model is still facing many unsolved problems regarding the considerable cost of energy for its machinery.

**Diagram 1**
![Diagram 1](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/6.jpg)

Currently, the annual consumption of electricity just for the mining Bitcoin and Ethereum has exceeded the annual consumption of countries such as the Czech Republic, Chile, and Colombia. Such consumption that increases every year is equal to the release of 20 megatons of carbon dioxide gas into the atmosphere. Therefore, on top of the high financial cost, this method seriously harms the environment.

**Diagram 2**
![Diagram 2](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/7.jpg)

On the other hand, scientific and academic projects are in pressing need of computing power. That is why many people have started to share their personal computer's computing power. The total payment for cloud computing (or renting people's computing power) in 2017, has been estimated at $130 billion. The amount was only $5.82 billion for 2008 while it is expected to reach $159 billion by 2020.

Considering these two factors (energy consumption for ‘Proof of Work’ and the increasing need for rented computing power), it would be a great idea to develop a platform in which miners are able to rent out part of their computing power to the scientific and academic projects.

Facing the problem of high energy consumption, the ‘Proof of Stake’ (PoS), has been introduced as an alternative to PoW. This solution, however, suffers from the following problems:

* A. Nothing at stake: The first problem that appears for these systems is the fact that resources are not in danger. In such a situation, during every fork, an attacker can go with both new forks.
* B. Distribution: Since a significant portion of coins is initially distributed before launching the platform, there may be some questions about the fairness of such initial distribution.
* C. 51% Attack: The PoS based networks are more prone to 51% attacks or to be manipulated by big fishes who hold most of the coins in their hands. People with the most money in the system can basically control the system. Providing their own enough of a share, they can apply censorship in the system and prevent some transactions from taking place.
* D. Monopoly: People with a considerable amount of coins, in the future, will receive the majority of the coins as well.

**Figure 6**
![Figure 6](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/8.png)

* E. Coins that are used as hashing power ( computing power) for valuable computations are thought to contain a kind of ‘proof of science’. These projects control the computing power in favor of analysis and data processing for important projects. This can considerably lower the cost of complex scientific research. It can also help with the speed of programming and administration of scientific projects in areas of artificial intelligence, genetics, medicine, astronomy, and nanotechnology.

The main problem with these systems, however, is that there is no systematic framework for their easy, correct and modular execution. They also lack network transparency. It is apparent that if executed correctly, this will be an important step forward for fundamental and applied sciences. This will be a great help for the welfare and development of human society.

Several methods of execution and implementation of scientific proof have been used. For example, FoldingCoin has been using the platform of Counterparty and has assigned the computing power of the supporters to medical research. There are also other projects such as GridCoin, EmerCoin, and CureCoin that are in need of computing power for their publicly beneficial computations.

Furthermore, in addition to the above projects, by providing an adequate framework, most universities and research institutes can speed up the execution process of their projects.

Some of the most critical problems faced by such projects are as follows:

* I. Lack of efficient and standardized platforms: At the moment, a standard platform for presenting computation services to a wide range of scientific and research projects has yet come to exist. In order to sustain their existence, most of these projects turn to miscellaneous systems or use combination methods.
* II. Centralized management: Calculation and announcement of the total hashing power of the network, distribution of rewards (in the format of predefined coins) to the contributors, and other network activities, usually take place in a centralized manner. Such a system does not fit the nature of blockchain technology.
* III. Scheduled distributions: Considering the lack of definition of a standardized structure, coin distribution usually takes place in a periodic manner, Taking that into account (in the case of long intervals between the issuance and distribution of rewards), the market for such coins would always be prone to go down during coin distribution.

2. **Separability:** The next challenge in blockchain based networks is how to create a connection between correlated and separated activities, with a decentralized infrastructure. For example, in order to set up the Internet of Things (IoT) for the purpose of controlling a large organization, various tokens need to be created.

**Figure 7**
![Figure 7](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/9.png)

The Internet of Things, in a simple word, is the communication of sensors and devices, with a network through which they can interact with each other and their users. In fact, it is a system of computers, digital and mechanical devices, humans and animals, each of which has a specific code and is independently present in the network. A considerable share of the information exchange and actions takes place without a direct interference and supervision of humans.

Due to various capabilities of the IoT technology in regard to ‘machine to machine’ interactions, this technology has been widely used in different sections of the industry including energy and gas. Of course, a modern and modular structure that can satisfy all the needs of this technology will be welcomed by practitioners of the field.

For example, imagine that in order to implement the ‘Internet of things’ for the purpose of controlling a big organization, different tokens need to be defined. In this example, in order to control and calculate water consumption, we need a token for water volume. Also, for a smart control and calculation of the electricity used for the brightness of the building, we need a Candela token (Candela is the base unit of luminous intensity in the international system of units with the symbol of a cd). On the other hand, for the adjustment of the building temperature, we need to define a token with the name Celsius. For cleaning, repairing, and other services, a cost token, and for the implementation of smart control on consumed energy, a Joule token should be defined as well. 

In the above example, if we decide to use the current blockchain technology, we first need to have a network consisting of independent tokens. These tokens eventually need to be arranged in a centralized network or with special programming in a decentralized network. That is due to a lack of appropriate modular infrastructure for the implementation of the ‘Internet of things’ technology, in the current blockchain technology. The best solution for this problem is to define a decentralized control unit in the second layer (a management unit that is supposed to be used in a modular manner by the ‘Internet of things’) and to define control tokens in the third layer. In this definition, control tokens of the third layer are automatically decentralized and independent, while all of them are controlled by the second layer from which they have branched off.

**Figure 8**
![Figure 8](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/10.png)

The Bither platform has a completely innovative and revolutionary design. It has a functional solution to the current challenges and problems faced by blockchain technology. By designing and implementing the new infrastructure and by optimizing the existing hashing power in the network, the Bither platform presents an appropriate solution to the problem of energy waste. On the other hand (through a new definition of the third layer in blockchain), needs that have not been met so far can be responded to.

This innovation implements classification and separation in the main network. Moreover, by recording an early execution of transactions in the network of the second layer and by merely sending a summary to the main network, it prevents a heavy load on the main blockchain. This problem came up a while ago in the Ethereum network when running a game, imposed a heavy load on the Ethereum network.

The next issue that has recently raised the sensitivity of governments, is the mushroom-like growth of scam ICOs (Initial Coin Offering) and their fast and easy execution on platforms such as Ethereum. In this method of implementation of ICOs, there is no supervision on their execution process. This means that after raising funds, projects can act in any way they want. In order to standardize and organize ICOs, the Bither platform presents a practical approach while keeping the old capabilities. In the following pages, we shall explain the advantages of this approach in detail.

## The Architecture of The Bither Platform

Bither presents an entirely new platform based on a synthesis of several methods. By introducing multi-mining capability and also optimizing hashing power consumption, Bither sets its goal to draw more computing power toward its network. Furthermore, Bither’s main network employs a new method to provide secure and impeccable records of transactions and computations.

Networks that are based on ‘Proof of Work’ (PoW) justify their constantly growing difficulty to attract more miners by making the claim that the increase of hashing power boosts network security and prevents possible attacks. This justification is correct in regard to the security challenges; but it does not convince the critics when it comes to the practical use of the computing power and also prevention of energy wastage. The Bither platform presents an innovative architecture in which a major part of the energy consumed by creating computing power is used for practical and beneficial purposes.

So far, one might conclude that Bither is a network based on ‘Proof of Science’ or even ‘Proof of Stake’ but surprisingly, like Bitcoin and Ethereum, Bither is also a network completely based on ‘Proof of Work’ mechanism. Like these networks, Bither seeks to attract as many miners as possible to increase its hashing power. Bither works with PoW as its consensus algorithm though with a different architecture compared to Bitcoin, Ethereum, and many others similar networks.

Bither’s innovation is in its calculation of network hash rate and automatic separation of hashing power by using trusted masternodes that will be defined and implemented in high numbers through a hybrid method. The necessary conditions for creating a trusted masternode are to have a specific number of Bither coins and to be approved by both the community and the development team. What is more, each masternode’s information is compared to other masternodes and there is an automatic and precise supervision over the accuracy of the computations as well as of their orders. This is, however, an initial design and Bither founding team is planning to fund research and development teams to partake in the implementation of a more decentralized network governance.

This way, masternodes are equipped with a new processor core (software). Through this processor core, the entire network hash rate is calculated before being divided into four major parts:

**Figure 9**
![Figure 9](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/11.png)

Part One: M percent of the network's total hash rate is allocated for mining new coins, recording transactions, securing the main network, and checking and executing smart contract algorithms on Bither's main network.

Part Two: N percent of the network's total hash rate is distributed among networks of the second layer. This hashing power is used for recording and confirming transactions in networks of second and third layers. It is also be used for computation and summarization of the network's internal transactions.

Part Three: This part is shown by the percentage marker of K. Through the miners’ decision and selection, this part is assigned to operational projects; these are projects that run on the Bither network and need computing power for their processing.

Part Four: The last part is introduced by the percentage marker of L (L=100-M-N-K). This part is assigned to a third-layer network in which miners can lease their excess hashing power. The token that is used in this network is called “Rental Processor”. This will be explained later.

### Comments

1- According to the number of projects running on Bither, the exact percentages of M and N can slightly change. This is completely dependent on the number and quality of the second and third-layer networks. Percentages M and N are determined completely automatically via a smart system by trusted masternodes. They are then sent to miners as an order, note that miners themselves have no role in this division; for instance, they cannot assign all of their computing power to just the main network. The process of computing and then issuing the order of distribution of computing power is done by Bither's processor core (DPU), which is under the authority of trusted masternodes. The processor core of masternodes (DPU) will be an open source software.

2- Adjusting and assigning the percentages of K and L is under the complete authority of miners who are attached to the main network. From now on, the total K and L will be called “excess computing/hashing power” in this paper. Miners may choose to do one of the below options:

* They can assign all of this excess hashing power to one or several projects that need hashing power. In this case, we will have: K=100-M-N, L=0
* They can transfer all of their hashing power to the Rental Processor network and take no part in scientific projects connected with the Bither network: l=100-M-N, K=0
* They can assign part of their excess hashing power to scientific networks and the rest of it to the Rental Processor network: L=(100-M-N-K) #0, K#0

3- Miners themselves can determine the percentages of their excess computing power and make changes if needed. The changes that are applied by miners will be executed by the network in the next one or in a maximum of next two blocks.

4- Every new node in the network has a complete list of trusted masternodes and will be attached to at least three of them. The implementation and utilization of the initial number that are needed for network startup are done by the development team all the way to the selection of the trusted masternodes (in a special process that is defined and announced). Evidently, this process is in the short-term and done merely for the initial setup of the network. Immediately after the users declare that the new nodes are ready and after the completion of a predefined process, this situation will quickly move toward decentralization.

5- In addition to the computing and issuing orders of the hashing power divisions by the DPU unit, the supervision of the network’s function, as well as the performance of the orders, will also be the responsibility of the trusted masternodes.

In order to reach more decentralization, definition, recognition of the trusted masternodes, and also to issue orders and provide supervision, a part of the accumulated funds will be spent on more research around these fields.

**Figure 10**
![Figure 10](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/12.png)

Let's illustrate this by an example: Imagine that the Bither network, has 50,000 GH/s computing power in total, In this situation, we also assume that 1000 networks of the second layer and 2500 networks of the third layer are already in the Bither network. In the structure of the Bither platform, the amount of hashing power and the condition of the main network and their dependent networks in each block are calculated separately. The trusted masternodes calculate the processing power of the network and announce the division percentage to other nodes.

In the above example, the computing power of the network is divided approximately as follows:

Main network: 6% of the total computing power (50,000 X 6/100 = 3000 GH/s)

The internal network of the second-layer projects (in total):  10% of the total computing power (50000*10/100=5000GH/s)

According to orders received from miners, the remaining 84% will be distributed among the Rental Processor network and research projects that need hashing power (50000*84/100=42000 GH/s).

Point 1: Although the distribution of hashing power can vary widely, under any circumstances, a minimum portion of hashing power is spared for major network functioning to keep the security of the network.

Point 2: In the Bither network’s mine setting, a user-friendly application will be available for miners. With the help of this application and their own confirmation, they can assign a percentage of their excess hashing power to one or more networks of their own choice. The Bither network will not make this decision for them.

**Figure 11**
![Figure 11](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/13.png)

Point 3: Considering the nature and structure of the network, mining the Bither platform’s coins would be ASIC resistant; it means that only graphics cards and CPUs can be used for mining.

Explanation: Nowadays, Bitcoin mining has become the monopoly of companies that have invested only in mining. The monopoly of mining subsequently leads to unequal distribution of digital currency; this is at variance with the primary philosophy of Bitcoin founded by Satoshi Nakamoto. Bitcoin was supposed to be a digital currency that anyone with a personal computer could take part in and mine new coins; currently, it is no longer possible to mine bitcoin with a PC at home as there is no chance to compete with big mining farms. The reason behind this monopoly of mining is the production of special processors that are designed only for mining (Application-Specific Integrated Circuit - ASIC). Graphics processing units (GPU) and central processing units (CPU) are not able to compete with these ASICs. One approach toward preventing such a situation is to make changes in the hashing algorithm, in a way that no one would be able to design an ASIC for mining.

By implementing a modern architecture for mining and defining trusted masternodes, the Bither platform presents a new solution to this problem. The role masternodes play in the distribution of hashing power, is an innovative approach to solving the problem of ASICs. This way, ordinary users will continue to be able to mine coins.

This is as secure and stable as a ‘Proof of Work’ network because We have made Bither Platform incentivizing enough for miners to make sure it can attract as much hashing power as other secure ‘Proof of Work’ networks.

Let us examine how the Bither network defends itself against an attack: Imagine that an attacker wants to conduct a 51% attack on the Bither network. Although approximately 14% of the total hash rate is assigned to the recording and security of transactions, the attacker still faces a complete network to become successful (not a network of which only 14% is assigned to such process).
 
Through the masternode, each node registers itself in the network and therefore receives the necessary information and orders from trusted masternodes. Moreover, the Bither network receives the same amount of hashing power from different sources; the mining device of the attacker also has to comply with the same protocol. In fact, from the very beginning of the attack, with the help of orders issued by trusted masternodes, the Bither network is able to conduct separations and distributions, which automatically reduces the power of the attacking hashing power.
 
In this platform, the main blockchain is responsible for the security of the transactions. For the first time, a standard structure for multi-mining is defined in order to incentivize miners to work on Bither’s network. The way this process works is as follows: A percentage of each second-layer project’s tokens will be assigned to mining systems. Initially, this percentage will be put to vote in the Bither community (owners of Bither coins). If at any point, that percentage needs to be changed due to price changes or other reasons, it will be put to vote once again. In order to do so, masternodes will at first send an activation signal (as an initial voting) and then, a general vote will become active in the network so that all members of the community can take part in determining this percentage.
 
Considering the workload that the second layer systems put on the main network, the necessity of implementation of such structures have been felt for a long time. For example, if there are 500 second-layer networks on Bither, the miner will mine 501 coins and tokens (mining a certain percentage of 500 tokens on the second layer + Bither). We think that this process is fairer because the networks in the second layer should do something in exchange for the workload they put on the main network.
 
Another important improvement in the Bither network is the semi-independent transactions in lower networks. Every internal network (based on the second layer) itself takes over the task of initial recording and verification of transactions. After that, through a special protocol and according to schedules and priorities, a summary of transaction records is delivered to the parent network (the main Bither network) for final and official recording.
 
The fee for the transfer of internal transactions (based on the second layer) will be paid by their own independent coin. The advantage of this method is that it does not need the Bither coin for both its gas supply and internal transaction fees. Consequently, in order to transfer the token of a project, it will be enough just to have that token. Also, for third-layer networks, there will be no need for a Bither balance; by obtaining some higher-layer tokens (their parent coin that is on the second layer), they can execute their own transactions. Indeed, the compulsion for having a positive balance of the main network's coin in order to be able to transfer lower network tokens is one of the disadvantages of the current blockchain, which leads to the dissatisfaction of users. With its new architecture, the Bither network completely fixes this issue.

**Figure 12**
![Figure 12](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/14.png)

The next advantage of this method is that it makes it costly for non-standard platforms (that can be defined by some people) to spam the network. Problems that the CryptoKitties game caused for the Ethereum network have made it clear for everyone that the current way in which the dependent networks are managing their transaction processes needs to be restructured.
 
Another new service that Bither provides is the possibility of a modular use of hashing power in lower networks. Think of a project that needs hashing power for its complicated computation in genetic or astronomical research. Considering the definitions and set modules on the Bither platform, the said project easily defines the number of its coins at its launch. Then, without assigning computing power to unnecessary computations, it uses the computing power toward the development of a scientific project of its own choice. Via a smart contract, they can reward participants in exchange for received hashing power. These smart contracts, which are written specifically for the Bither network, calculate the input hash of each miner. Then, according to predefined conditions of these smart contracts, the miners will be given tokens accordingly.
 
Bither miners can use their commands to assign a part of their hash rate to networks that need hashing power. Alternatively, networks can advertise their system to get their required hashing power directly from the Bither network. Currently, there is no standard protocol with a modular-based “Proof of Science” mechanism. Subsequently, Bither will pave the way for the development of such scientific projects.

**Figure 13**
![Figure 13](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/15.jpg)

The implementation of projects that need hashing power will be possible via two protocols (one invariant and one dynamic):

A) In the invariant protocol, the project that needs hashing power modularly sets out its token distribution method (rate distribution, total supply). In this model, the minimum received hash is determined and then a fixed number of tokens is distributed among contributors. Contributors here means miners of the Bither network who -via their commands- have assigned a part of their excess hash to the mentioned network. In addition to them, independent miners can also directly assign hashing power to it if they are interested in the project. In this protocol, mining is competitive; the percentage of the contribution is calculated and the fixed number of tokens is distributed on a percentage basis.
 
B) In the dynamic protocol, the project that needs hashing power does not distribute the token on a percentage basis. In return for any amount of hash that is assigned to the network, the number of tokens is specified beforehand. These tokens will be distributed among contributors on a standard schedule. In this model, the number of distributed tokens can vary in proportion to the received hashing power. Another advantage of the Bither platform is the possibility of defining a third layer. While having a relative independence, third layers receive their practical commands from the second-layer networks below and in return, they submit a report of transactions and other activities. Imagine that an academic complex is active in medical sciences and it wants to categorize its activities in different areas. For instance, a category for the activities regarding vaccines, finding new drugs and genetic research and so on. In every one of these categories, they will be defined as separate tokens on the third layer and will be executable under the supervision of the mother network on the second layer. Moreover, third-layer transactions will be checked and confirmed on the second layer; therefore, these networks put no load on Bither’s main network.
 
In order to prevent spam projects that intend to harm the network (by putting valueless tokens inside the Bither network), a fixed number of Bither coins (for registration of second layers) should be paid to the network. This amount is gradually given to the miners and this fixed number is 100 Bither coins at the beginning of the network’s setup. Every six months, there will automatically be a vote to determine this fixed number. This initial payment will be gradually distributed among the miners.

**Figure 14**
![Figure 14](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/16.png)

## The Bither Stock Network

The “Bither Stock” network is an internal network on the second layer. Shortly after the setup of the main network, the developer team will set up the Bither Stock network on its basis. The aim of Bither Stock is to create a system based on blockchains, in the form of a blockchain holding-company and in order to provide the possibility of leasing a part of the hashing power of the network. This internal network has a fixed number of coins, all of which will be released at the beginning of its operation. 
For example, for projects that need a larger-scale of computing power in a given period but do not have the possibility to obtain and keep supercomputers, Bither Stock can be a good choice. The initial contributors play an undeniable role in the development of the Bither network. With their support and trust in the technical team, they allow the network to grow and mature. As a reward, a quarter of Bither stock tokens will be dedicated to them.

The owners of Bither Stock are shareholders in leasing hashing power (based on the second layer), which will have a lifetime fixed income on a weekly basis. These transactions take place using “Rental Processor” that is a token on Bither’s third layer. It is considered as the network currency for internal transactions toward leasing hashing power. The price of hashing power in the Bither Stock network will be depending on supply and demand, and a 2% commission will be taken for each transaction. This amount will be saved at a fixed address that can be checked by everyone and the total received commission will be distributed among shareholders (according to the ratio of their share to the total one hundred million tokens). This distribution will be done on a weekly basis with Rental Processor as the currency (a minimum will be defined).

In fact, the implementation of the second-layer network of Bither Stock and its dependent third-layer network of Rental Processor serve as an exemplar to demonstrate the capabilities of the Bither platform. Bither Stock is a holding company and in exchange for keeping their share, its shareholders will have an adequate lifetime income. This network will have its own independent website (Bitherstock.io) and the decision making and voting in this network will be completely independent and outside of the Bither platform’s ecosystem.

During the presentation of the Bither network’s token (during presale), 25 million tokens of the Bither Stock network will be given to the contributors, which can also be transferred, bought or sold. In the end, shortly after the release of the main network and swapping of the “Bither token” with “Bither’s main coin”, the sidechain of Bither Stock will be released too and its tokens will be swapped.

To handle transactions in the sidechain of Bither Stock, 2 billion Rental processor tokens are also created, a quarter of which will be distributed among Bither's supporters and participants. It means that for each Bither stock token, they will receive 20 Rental processor tokens as well.

As a matter of fact, since the Rental Processor token is needed for the hash rate of the network to handle transactions, it will be listed on major exchanges and can be traded after the launch.

## Innovations and Attractions of Bither

For the first time, Bither has presented a completely new platform which has many advantages for executing smart contracts, setting up scientific projects that need hashing power, creating second and third layers toward categorization of activities for tokens and so on and forth.

**Figure 15**
![Figure 15](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/17.jpg)

## Bither will present all these advantages to the cryptocurrency society:

* A. Optimized use of energy and combined mining ability with a special attraction for miners: Few miners can overlook the combined method that has been presented in the Bither platform. Evidently, the attraction of active miners (in the area of cryptocurrency) helps in enhancing the network’s security. Moreover, the optimized use of energy and computing power will be one of the most important advantages of the Bither network. This resolves the critics’ concerns regarding PoW based networks.
* B. Creating thousands of sidechains in the network: In addition to a  two-layer architecture, the Bither platform goes one step further and builds a third layer on its network structure. Such a three-layer structure is completely new and makes structuring of projects far easier for developers and start-ups.
* C. Recording transaction details on sidechains rather than the main network: Considering the scalability issues and the risk of networks being spammed by low-value transactions (they recently caused chaos in the Ethereum network by running simple games), all transaction details are recorded in the sidechains and only a low volume summary of them will be transferred to the main network which makes it is easier to handle the execution of a large number of microtransactions of a given token, if it is done on its own sidechain. Considering the mentioned algorithm, a large number of transactions, will not cause disorder in the main Bither network. Moreover, by having thousands of sidechains in the second and third layers of the network, its sustainability will also be guaranteed.
* D. Operating internal transactions without using Bither coins: In currently existing platforms, in order to transfer a token defined in the main network, the network fee has to be paid by the main coin. Due to the algorithm of Bither, transaction fees of a certain sidechain are paid by the internal token rather than the main coin, namely BTR. This makes it easier for users to conduct their transactions without having to pay the fee with the main coin.
* E. A standard platform for scientific projects: One of the most important features of the Bither network is its optimization of computing power usage and a hashing power allocation system in the lower networks. The Bither network aims to serve as a computing power resource for scientific and academic projects that have an undeniable role in the future improvement of human well-being. Bither is the only standard platform in the area of cryptocurrency that has a pre-defined and modular base for the implementation of scientific projects. Undoubtedly, one of the main goals of the Bither team is to support modern and applied sciences that need complicated computations. Considering the prepared base in Bither, research institutions and universities will be able to conduct their scientific research. Bither’s programming team’s forecast is that a vast number of research institutes and universities will welcome Bither; by using its modular systems.
* F. A call for hashing power for mineable projects at the start of their activity: Bither can provide an appropriate base for mineable coins. Due to being new and publicly unknown, many mineable projects, at the outset, suffer from a shortage of hashing power which can heavily influence the security of such networks. These projects can temporarily run on the Bither network. This primary temporary start will have an important advantage for these projects. Their security will be guaranteed in the Bither network and free from being worried about attacks, they can focus on their marketing. Due to the possibilities of the Bither platform, these projects can independently create a portal for attracting hashing power for their own non-independent network. Once they attained the minimum required hashing power, they can run their own network independently and swap their tokens.
* G. Profitable mining during market downturns: During market downturns, the profitability of mining reaches its lowest and even in some cases lead to a loss for miners. In such a situation, even if miners are optimistic and wait for another increase in prices, due to the current costs of mining such as electricity and device maintenance, they may not be able to keep doing that.  With Bither, they can still make a profit by leasing the computing power which is always welcomed by research and scientific institutions. By allocating an appropriate part of the excess computing power to the Bither Stock network, not only a miner covers his costs, but he can also earn an income.
* H. Defining a safe standard to prevent fraud in the initial coin offerings (ICO): There are two ways to implement an ICO in the Bither platform. Like projects such as Ethereum, NEX etc, Bither also provides the possibility of creating any subchain. However, in the standards visible in the exploration of the Bither platform, these projects are shown with the color yellow. The solution put forward by Bither is to define ICOs by the color green and placing them among standard projects. ICOs that are categorized by this color, are ICOs in which the main team has based the project plan on smart contracts (in the modular model) and this project plan is not editable. Obviously, no project can have two different project plans. People who are interested in the project can check the validity of the project plan that has been based on smart contracts, by comparing it with the project plan presented in the project's website or its official portals. In the event that the developing team finishes one stage of the project, this process is confirmed by the token holders' vote, a percentage of the raised funds (that have been stated for each stage by the core team at the time of pre-sale) will be released to be used for implementation and progression of the next phase. In case of a pre-stated period (for example two months ago at the time of pre-sale with contributors' knowledge) passing from the time of completing a stage and not sending the trigger (for finishing that stage)  by the developing team, a vote will be taken to automatically refund the investors. Also, in cases that the completion of a phase is not confirmed at every stage by token holders, voting for refunds will be activated.
* I. Defining and creating holding companies: Holding companies are different from sub-branch companies. The Bither platform makes it possible for holding companies to be unlimitedly defined and created in a modular model. In these systems, profit of the sub-branches can be shared with holding companies and shareholders by automatic distribution. For example, suppose that a holding company dealing with toy manufacturer is created on the second layer of the Bither network. This company is supposed to be an accelerator for various manufacturers each producing a different type of toy such as dolls, construction toys, board games etc. These separate manufacturers, while under the management (support) of the main holding company, enjoy their own autonomy. People with ideas and technical abilities can go to the accelerator company and present their plan. After technical and market assessment of each idea and primary confirmation, the accelerator company puts the idea of investment for designing and manufacturing the said toy in the form of setting up a new company to vote among its shareholders. After receiving enough votes, the project will receive the investment. After this stage, a semi-independent company will be created on Bither’s blockchain’s third layer and under the second layer’s holding network. In this example, let's assume that 70% of the new company's shares is for the projects applicant team and 30% belongs to the holding company. During financial periods and after auditing, the project's profit is calculated and 30% of it that belongs to the holding company is allocated to the second layer's network and is distributed by the percentage among the network's token holders. This process cannot be easily implemented in current networks and needs special reprogramming and coding. In Bither however, this process can be easily implemented and executed in the modular model. Another scientific example of this ability is the definition and implementation of the Bither Stock network on the second layer of the Bither platform which is supposed to be formed by shareholders of this network. On the second layer (on the lower layer of the Bither Stock network), there is the Rental Processor which is the computing power leasing network. The commission for leasing computing power in this system is collected and distributed among the Bither Stock shareholders at designated times.
* J. Setting up decentralized and user-friendly exchanges benefiting from the three-layered structure of Bither: Decentralized exchanges would be able to renew their systems and redefine more efficient standards. A central core can be easily defined for a decentralized exchange on the second layer and tokens can be defined on the third layer with a peer to peer method for their equivalent coins.

## Practical examples applicable to the Bither network

* i. An accelerator company for computer games that are seeking to attract investment, not in need of hashing power, though:

There are many people around the world who want to invest in different sectors in order to gain appropriate and legitimate profits. The online gaming industry is one of the areas which is attracting many investors. In 2017, gamers, all over the world, spent about 108.4 billion dollars, which has witnessed an 8% increase compared to 2016. Bither has created an appropriate base for active companies in this area. Purchasing items, upgrading and performance enhancement in different games, takes place via various methods. However, by integration/unification and simplification of purchase and payment, more profit can be achieved.

Most of the time, games are only attractive whilst playing with them and after the game is finished and its effect subsided, they lose their attraction. The Bither blockchain can be profitable for gamers by providing them with a daily income. There can be many tokens defined on the third layer of Bither's sidechain. By defining an income token in this project, gamers who for any reason earn points such as gold or coin can gain profit in return for receiving some of the blockchain network's tokens. In the Bither blockchain, gamers can even become famous; it is so inevitable that when the game ends, the history of the gamers' scores in that game also ends. Since, here, accounts are only addresses, it would be more convenient for those who wish to play anonymously. Moreover, in order to develop further levels of the game, via surveys and other methods, companies can get help from the gamers themselves.

By setting up the project at the base of Bither, there will be the possibility of attracting investment for different projects. After a call for a vote for different game plans and scenarios, the best ideas will be chosen by shareholders. Investors will have a few days for consultation and studying the plans before voting for the chosen projects and plans. After this stage, using the available fund, the number of game developers can be increased, even the game engine can be designed again, and more hardware gadgets can be created for the mentioned game.

After releasing the games, there will be a number of methods through which the profit can be distributed among the investors. Thanks to the nature of blockchain, this can happen in the most transparent way. Therefore, in addition to profitability for investors and project employees, the ground will be prepared for implementation and execution of different types of projects on a larger scale and based on more trust.

**Figure 16**
![Figure 16](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/18.png)

On the other hand, for example, let's assume an accelerator for computer games attracts some investment. This company is supposed to invest in six different areas. 

Evidently, in the current structure of blockchain, there is no possibility for separation of activities under holding companies and no standard structure has been defined for such purpose. In the Bither platform's network, a second layer token can be defined as the holding company's investors' share and different work branches can be defined on the third layer. According to a predefined structure, after any given period, the profit of the independent systems of the third layer is calculated and distributed among the system's shareholders and also shareholders who are on the second layer (shareholders of the computer game accelerator holding company)

* ii. Genetic research projects (merely computing power attraction and not in need of investment attraction):

Nowadays, in medical science, processing big data is a crucial requirement. Medical image analysis, genome sequencing, genetic mapping, drug discovery process, and predictive modeling etc. all need big data processing in a short space of time.

Imagine a drug company that in one of its projects attempts to recognize the genome or genomes that cause Alzheimer's. In such a project, there would be a pressing need for a supercomputer for studying and simulation. From an analysis of previous findings, in the relationship between the genes and different moods of Alzheimer's, this supercomputer, would decode human genomes. Supplying a powerful supercomputer for such a purpose would encounter difficulties in design, high maintenance costs, and the increased possibility of unexpected accidents due to its centralized system. On top of that, it will be very time-consuming as well.

Bither gives an appropriate solution for such projects. In a very short time, the project would be set up on the Bither platform without any initial payment for the design, installation, and setup of the supercomputer. the project can benefit from the computing power of the network members interested in participating in it. In return for the received computing power, appropriate tokens (for example for every mega hash equals one token) will be presented. These tokens will have values and can be traded in the exchange.

On the Bither platform, all events are securely recorded with complete transparency, Therefore, no attack will be able to cause disorder or manipulate the research results. Also, in regard to important results and special information, it is possible to make private data only visible to company owners, the non-confidential information can be accessible by the public. This process is achievable by encrypting the confidential results of the research and then putting the codes on the blockchain.

**Figure 17**
![Figure 17](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/19.jpg)

* iii. The project of an inner-city post by drones (simultaneous attraction of investment and hashing power):

Throughout history, many professions have gone through major changes. One profession that in future will go through a lot of change, is the postal service.
 
There isn't a single store that doesn't want to grow and as we know, one way of increasing the sale is to provide fast and reliable delivery services. Imagine the store owner in order to increase their sale, sets up a free delivery for purchases over $200 and also guarantees fast delivery for purchases lower than $200. Of course, the local postal service or other similar agencies, offer such services too, but they wouldn't have all its advantages at the same time. In this case, the advantages are 24/7 and faster delivery services.
 
Now imagine that a big store has decided to use drones for its delivery service in an effective way; however, they don't have the budget for creating thousands of drones. They also can not afford to buy hundreds of servers in order to run the drone management software and create security for drone communications. Bither is the only standard platform that has a complete answer for all the problems that such projects face. Bither is an appropriate solution for overcoming the obstacles regarding creativity.
 
In addition to attracting funds, the Bither platform, gives the above project, the opportunity to receive its needed computing power from the network. After the project is defined on Bither's base, by selling tokens, it attracts investments. Using these investments, it can complete the designing and building stages for drones with the lowest weight and longest operational range. For this purpose, optimized systems should be installed on drones. These optimized systems should be lightweight, cheap with low energy consumption.
 
After this stage, Bither's hashing power helps to set up and run the project. In addition to speed, precision, drone security, and faster AI development, using the network's hashing power, lowers the costs too. A second by the second report is recorded on blockchain's ledger, and in addition to making the profit and loss of the company transparent, accounting operations are also reduced. In fact, with the lowest number of employees, in addition to providing and selling products, this store can take responsibility for an inner city postal service that is fast, accurate and transparent.

**Figure 18**
![Figure 18](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/20.jpg)

### Description and formulation

Bither Miners: The miners who are connected to Bither's main network.

K<sub>i</sub>: The surplus computing power that Bither network miners, by their own choice, allocate to a certain project.

S<sub>i</sub>: The computing power received from the miners who are out of Bither network.

X<sub>P</sub>: The predetermined percentage of tokens to distribute among the miners of the main network.

A: The number of days for tokens distribution (defined by the project-holders).

H<sub>min</sub>: The minimum time a miner needs to remain connected to a sidechain network in order to receive tokens (defined by the project-holders).

T<sub>2</sub>: The total tokens that the project has allocated for distribution in exchange for the computing power.

t: The minimum amount of required tokens for the distribution.

I<sub>hp</sub> = K<sub>i</sub> + S<sub>i</sub> (total received computing power by the sidechain)

#### A) Invariant protocol:

H<sub>min</sub> = 1 hour

Distribution rate per hour: D<sub>XYZ</sub> = X + Y + Z = T<sub>2</sub> / 24A

Percentage of K<sub>i</sub>: K<sub>ip</sub> = 100 K<sub>i</sub> / I<sub>hp</sub> = 100 K<sub>i</sub> / (K<sub>i</sub> + S<sub>i</sub> )

Percentage of S<sub>i</sub>: S<sub>ip</sub> = 100 S<sub>i</sub> / I<sub>hp</sub> = 100 S<sub>i</sub> / (K<sub>i</sub> + S<sub>i</sub> )

K<sub>ip</sub> + S<sub>ip</sub> = 100

Tokens distribution:

X = x<sub>p</sub> . D<sub>XYZ</sub> = x<sub>p</sub> T<sub>2</sub> / 24A

Y = K<sub>ip</sub> (D<sub>XYZ</sub> - X) = K<sub>ip</sub> (D<sub>XYZ</sub> - x<sub>p</sub> . D<sub>XYZ</sub>) = K<sub>ip</sub> . D<sub>XYZ</sub> (1 – x<sub>p</sub>)

&nbsp;&nbsp;&nbsp;&nbsp;= (T<sub>2</sub> / 24A) (100 K<sub>i</sub> / (K<sub>i</sub> + S<sub>i</sub> )) (1 – x<sub>p</sub>) = (100 K<sub>i</sub> T<sub>2</sub> (1 – x<sub>p</sub> )) / (24A (K<sub>i</sub> + S<sub>i</sub>))

Z = D<sub>XYZ</sub> – X - Y = S<sub>ip</sub> (D<sub>XYZ</sub> - X) = (100 S<sub>i</sub> T<sub>2</sub> (1 – x<sub>p</sub> )) / (24A (K<sub>i</sub> + S<sub>i</sub> ))

#### B) Dynamic protocol:

H<sub>f</sub>: Total required computing power

D<sub>m</sub>: Minimum required computing power in exchange for tokens

Distribution rate per computing power: D<sub>hp</sub> = T<sub>2</sub> (100 – x<sub>p</sub>) / 100 H<sub>f</sub>

Y = D<sub>hp</sub> K<sub>i</sub> = K<sub>i</sub> T<sub>2</sub> (100 – x<sub>p</sub>) / 100 H<sub>f</sub>

Z = D<sub>hp</sub> S<sub>i</sub> = S<sub>i</sub> T<sub>2</sub> (100 – x<sub>p</sub>) / 100 H<sub>f</sub>

X = x<sub>p</sub> (Y + Z) / (100 - x<sub>p</sub>)

&nbsp;&nbsp;&nbsp;&nbsp;= x<sub>p</sub> ((K<sub>i</sub> T<sub>2</sub> (100 – x<sub>p</sub>) / 100 H<sub>f</sub>) + (S<sub>i</sub> T<sub>2</sub> (100 – x<sub>p</sub>) / 100 H<sub>f</sub>)) / (100 - x<sub>p</sub>)

&nbsp;&nbsp;&nbsp;&nbsp;= x<sub>p</sub> T<sub>2</sub> (K<sub>i</sub> + S<sub>i</sub>) / 100 H<sub>f</sub>

## How distribution and mining work on the Bither platform and the Bither Stock

200 million Bither coins will be distributed and mined in total and from this amount, 45 million coins will be distributed and pre-mined. After the release of the main network, the remaining 155 million coins will be available to mine, which will be gradually extracted by miners for approximately 295 months. For each block, the time of release will be 20 seconds and four coins will be extracted as a reward. This way, 6,300,000 coins will enter the cycle every year adding to the previous amount.

In effect, the total number of the Bither stock is 100 million and at the time of pre-selling Bither’s tokens, a quarter of the Bither stock tokens will be distributed among the contributors as a thank you to the supporters of the project. In fact, it can also be seen as an example of how a shareholding company can be run on the Bither network. By means of airdrop, 20 Rental Processor Token will be also distributed for each Bither Stock token. The Rental Processor token is the network's currency for the transactions regarding the rent of hashing power. The Bither stock's shareholders will receive a percentage of the rental-hashing power network's income on a lifetime basis.

**Table 1**

|Coin Name               |Coin Abbreviation    |Total Coin    |ICO    |
|:-----------------------|:--------------------|:-------------|:------|
|Bither                  |BTR                  |200 M         |45 M   |
|Bither Stock            |BSK                  |100 M         |25 M   |
|Bither Rental Processor |BRP                  |2 B           |0.5 B  |

The investment needed for the development of the Bither platform will be provided by a kind of public campaign and by the Ethereum. The address for the smart contract of Bither’s pre-sale is as follows:

    0x8C3eD5588Cdd3FdAC2331025377280Fb39757A5b

The GitHub link for the project’s smart contract is as follows:

    https://github.com/bitherhq

The reason for using Ethereum for pre-sale and also defining initial tokens of the Bither platform is its network's ability to create more complicated systems in a shorter period of time and lower cost. Ethereum based tokens are based on a structure that has the following advantages:

1. Security and ease of use: Considering that initially, Bither coins are distributed among project supporters as tokens, Ethereum is the most appropriate and the safest platform for token distribution.

2. Having good and supportive clients: Considering Ethereum’s popularity among blockchain users, and also familiarity of many users with its transaction process and its tokens, it will be easier and more convenient for supporters of the project to take part.

3. High liquidity ratio: The number of Ethereums and their distribution ratio is high and its transaction fee is lower than Bitcoin.

4. Its availability in most currency exchanges: As previously stated, the distribution system of both tokens of Bither and Bither Stock will take place simultaneously. In most currency exchanges, they have an accessible and premade infrastructure for ERC20 standard and can easily and quickly add the Ethereum tokens. Considering the above explanation and the fact that necessary coordination has been done with a number of currency exchanges, after the distribution process and presale is finished, adding Bither and Bither Stock to the exchanges will immediately start.

5. Smart contracts: Considering the complexity of distributing bonuses according to time and other characteristics, using smart contracts will bring more comfort and transparency.

## Distribution method of the Bither platform’s token (BTR)

The method for distribution and release of 200 million coins on the Bither platform’s network, will be as follows:

* 155 million coins (77.5%) will be gradually mined.
* 30 million coins (15%) will be dedicated to crowd sale. This amount will be first as a token but it will be swapped with the main coin after the setup of the Bither network.
* 10 million coins (5%) will be dedicated to the developer team to continue developing on the project. This amount will be released gradually in 10 stages.
* 5 million coins (2.5%) will be dedicated to marketing (Bounty program, Partnership, Faucet, referral systems and so on) in order to develop special plans.

The following chart shows the distribution method of the Bither platform’s token:

**Chart 1**
![Chart 1](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/21.jpg)

Point 1: From the total number of the Bither network's coins, 10 million will be given to the developing and programming team. All of these coins will be put in a fixed address which is publicly announced. After the setup of the main network, the new address which belongs to the Bither platform's main network will be again publicly announced. These coins will be given to the developing team in 10 stages for 4.5 years. In each stage, one million coins will be given and there will be six months between every two stages. This distribution method is due to the fact that the developing team has a long-term plan for the development and increase of the abilities of the project and the network.
 
The address for the shares dedicated to the team (for transparency in staged distribution):

    0x2869F6d1B27850CeB35730B62b0eD57fbC238681

Point 2: In order to introduce the network’s ability to more people, drip distribution via Bither platform’s faucet will be used. All of the coins that are considered at the beginning of the distribution (700 thousands of tokens) will be deposited in a fixed wallet called Faucet.

The internet address for Bither’s Faucet:

    https://bither.one/

The address for the Faucet account for distribution transparency:

    0x8a5254e405fa7d8335bb44d576fefa064c5ca3cc

Point 3: In case the total amount of allocated bonuses is not given out (especially because the number of bonuses will be reduced over time), the remaining part will be deposited to the marketing fund.

## Distribution method of the Bither Stock’s token (BSK)

The supply and distribution of the Bither Stock token will take place at the same time with the distribution of the Bither platform’s token. In fact, by depositing Ethereum into a wallet that has been announced for receiving the Bither token. The contributors receive both tokens simultaneously and without needing any procedure. The distribution and release method  for 25 million tokens of the Bither Stock network will be as follows:

* 15 million tokens (60%) will be directly deposited for contributors at the same time as the Bither platform’s token. 
* 3 million tokens (12%) will be given to the programming team of the project and the marketing development team.
* 7 million (28%) will be dedicated to the marketing (Donation, Bounty Program, Referral System) section in order to develop special programs.
The below chart shows the distribution method for the Bither Stock’s token:

**Chart 2**
![Chart 2](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/22.jpg)

Point 1: The initial amount that has been considered for the charitable donation fund is one hundred thousand tokens.

The total holding of Bither Stock will be saved in this fund, without the option of moving it in future. Due to the consistent profitability of the Bither Stock's shares, the income obtained from these shares (through receiving the Rental Processor tokens), will be collected in a special and announced fund. The spending method of the donation system will be through voting among Bither Stock's shareholders. Every three months, the community determines a receiver and then the donation will be transparently directed toward that receiver. These donations will be dedicated to charitable organizations (with transparent operations) and also medical research for the eradication of diseases etc.

The address for the donation fund for distribution transparency:

    0xF5274b31E390493317F07ccD536AC224A758E9b5

Point 2: To create an incentive among the cryptocurrency communities and to widen the introduction of the Bither project to everyone active in this area, an appropriate referral system has been thought of, in which 3.6% of the total Bither Stock’s tokens amount have been considered. By registering and becoming a member of the website for the presale of Bither, any user can receive their own unique link for promoting the system. The referrer gets 6% of both BSK and BRP of the amount that the referee (excluding bonuses) has purchased. For example, let's suppose that Allan registers via Michael's referral link and buys 2000 BTR. As a result, Allan earns 1000 BSK and he will be also rewarded 40,000 BRP. Because of Michael's effort in introducing the Bither network, as a reward, he also receives 60 BSK and 1200 BRP as a reward (note that the referrer will not receive any BTR).

Note: In case the total amount of allocated bonuses is not given out (especially because the number of bonuses will be reduced over time), the remaining part will be deposited to the marketing fund.

## The distribution method of the Bither Rental Processor token (BRP)

The Rental Processor Token (BRP), which Bither Stock holding company uses for leasing computing power, is defined in the third layer. The total amount of BRP is 2 billion; using airdrop, this amount will be distributed among the participants in a way they will receive 20 BRP for every BTR purchase.

During the current project, 500 million tokens will also be released in proportion to the release of 25 million BSK (20 times more). The distribution of BRP in marketing, referral program and so on will be the same as the method used for BSK.

Distribution of the rest of BSK and BRP (75%) will take place later. The date and method of this distribution will be announced publicly on Bitherstock.io by late September 2018.

## Details of the initial coin offering (ICO)

After the start of the marketing and introduction of Bither's features to the people who are active in the cryptocurrency space, pre-sale and presentation of tokens take place in two rounds. The date for the first round is 26th January 2019 (14:00 UTC). For 13 days, a presale will take place so that anyone interested can declare their readiness for supporting the project. Nine days after the first round (16th February 2019-14:00 UTC), the second round (meaning the official sale) will start. This round also will last for four weeks.

The fixed price for distribution without considering the bonuses is as follows:

**Figure 19**
![Figure 19](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/23.png)

The distribution method for the Bither and Bither Stock tokens is embedded as a smart contract in a fixed wallet that has been specified for deposits. While considering schedules and bonuses, this distribution takes place automatically after the deposit of Ethereum by the contributors. Immediately after that, the tokens can be checked and moved into the personal wallet.

It is mandatory for all contributors to register on the official website and to also input the Ethereum address from which the deposit is going to take place. Every individual's referrals and the level of their contribution will be determined through this method, and their exact commission will be updated and visible in the personal balance every 24 hours.

To make sure that everyone is going through the above-mentioned process, BRP tokens will be attainable only through the official website as well as the bonuses of the referral program. Consequently, if someone directly sends an amount to the official wallets in order to participate in the project without registration, they will not be entitled to receive any BRP tokens and bonuses.

Through the dashboard of their accounts, the participants can find the received BRP and bonuses. After the sale period, this amount will be transferred to the wallet the user has given in the registration form.

**Figure 20**
![Figure 20](https://raw.githubusercontent.com/bitherhq/whitepaper/master/images/24.png)
