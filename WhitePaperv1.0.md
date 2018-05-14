# Digital Credit White Paper v1.0

**May 13, 2018**

Bruce Zhang

digitalcreditio@outlook.com

[digitalcredit.io](http://digitalcredit.io)


**Abstract:** Digital Credit is designed using a brand new blockchain architecture by creating a decentralized, verifiable digital credit community and application platform, based on challenge, contest, test, teaching, posting, ranking, achievement, contribution, review and voting, implementation of POA (Proof of Ability), credit evaluation and digital credit actions for members in the community to create a decentralized, trustworthy, easy to use, immutable, autonomous digital credit community and application platform. Digital Credit simplifies the blockchain application development and implements a distributed, decentralized MVC framework: dMVC (decentralized Model-View-Control), which includes: model part: data structure, database and data storage; control part : actions, services, account managements, role and organization managements, tags and categories; Proof of Ability Actions, including: challenges, contests, tests, contributions, teaching, posts, rankings, achievements, reviews, voting, etc. ; digital credit evaluations, digital credit actions (including awarding rewards, issuing loans, approving crowdfunding, allowing sales of tickets, etc.), tokens and smart contracts, and dispute resolutions; Views: Clients, etc. This allows the creation of distributed, decentralized, authentic, trustworthy, easy to develop, immutable, safe, objective, fair, autonomous, digital credit communities and applications based on POA.

**PLEASE NOTE: CRYPTOGRAPHIC TOKENS(Digital Credit, DGCT) REFERRED TO IN THIS WHITE PAPER REFER TO CRYPTOGRAPHIC TOKENS IN TWO VERSIONS: 1. CRYPTOGRAPHIC TOKENS ON A LAUNCHED BLOCKCHAIN BASED ON EOS.IO. 2. ERC-20 COMPATIBLE CRYPTOGRAPHIC TOKENS ON A LAUNCHED BLOCKCHAIN BASED ON ETHEREUM. ERC-20 COMPATIBLE TOKENS(Digital Credit, DGCT) BEING DISTRIBUTED ON THE ETHEREUM BLOCKCHAIN WILL BE APPLICABLE TO A DIGITAL CREDIT SOLUTION THAT IS COMPATIBLE WITH ETHEREUM: ULTILIZE ETHEREUM TO IMPLEMENT TOKES AND SMART CONTRACTS, ULTILIZE DMVC TO IMPLEMENT OTHER DIGITAL CREDIT FEATURES. MORE DETAILS CAN BE FOUND IN THE COMPATIBILITY SECTION. **

Copyright © 2018 [digitalcredit.io](http://digitalcredit.io)

**DISCLAIMER:** This Digital Credit White Paper v1.0 is for information purposes only. digitalcredit.io does not guarantee the accuracy of or the conclusions reached in this white paper, and this white paper is provided “as is”. digitalcredit.io does not make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this white paper are free from error; and (iii) that such contents will not infringe third-party rights. digitalcredit.io and its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this white paper or any of the content contained herein, even if advised of the possibility of such damages. In no event will digitalcredit.io or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special for the use of, reference to, or reliance on this white paper or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses.

<!-- MarkdownTOC depth=4 autolink=true bracket=round list_bullets="-*+" -->

- [Background](#background)

<!-- /MarkdownTOC -->

# Background

## Pain points and Challenges in current credit system

1. Current credit reports and scores have limitations: (i) The credit system is often based on the creditor's current income level, payment and repayment records, credit history, number of applications for credit account, etc. It is impossible to completely and objectively evaluate the credit of the creditor. (ii) Once the creditor has made a mistake, such as accidentally forgetting to repay the credit card, it will have a great negative impact on its credit score. (iii) For freelancers who do not have a stable job, or who are in underdeveloped areas, poverty-stricken areas, or social bottoms, even if they have creditability, they often fails to obtain credit based on traditional credit models. (iv) The credit information of the creditor is passive and it cannot improve its credit rating through active actions.

2. Currently, online-based lending, crowd-funding, and ICO are often fraudulent because the financiers or borrowers are falsifying information and their capabilities are incompetent, ultimately causing losses to the funders. The fundamental reason is that funders cannot perform effective assessment and verification of the true identity and true capabilities of creditor.

3. In human resources, such as talent recruitment, often candidates will fictionalize or exaggerate their curriculum vitae and personal abilities. Initial interviews and short-term trial periods often fail to effectively test their true level of competence. When the company discovers the capabilities of recruiters are incompetent, it is often too late: corporate resources have been wasted, and there are numerous cases where companies are unable to recruit the right people in key positions and the company's development is delayed.

4. Some underdeveloped areas, poor people, individuals at lower levels of society, even if there are talented people in them, their talents are often wasted due to their inability to be effectively excavated. Because these people are of low birth and lack of social relations and self-powered display platforms, it is harder to obtain job opportunities and social recognition.

5. In some outsourcing areas, such as software outsourcing, design outsourcing and other outsourcing areas, project consignees often cannot effectively verify and assess the actual level of the recipient and suffer losses.

6. In the field of venture capital investment, investors are often unable to effectively verify and evaluate the true level of capabilities of the start-up entrepreneurs and suffer losses; start-up entrepreneurs who have great ideas and action forces are unable to obtain investment because of lack of social relations and connections.

## The keys to solve problems of current credit system

1. It must be able to ensure the objectivity, authenticity, and immutability of evaluations of creditors' credit rating, and can fully assess the credibility of creditors.

2. In addition to passively accepting credit assessments, creditors must also be able to actively upgrade their credit rating through positive and meaningful actions.

3. It is necessary to ensure a mechanism: when the creditor happens to defaults and frauds, the loss of the contributor is minimized.

4. Must ensure a mechanism: Encourage creditors to engage in positive, meaningful, valuable, positive actions, and not to do negative, meaningless, worthless, negative actions. (ie provide positive and negative feedbacks)

5. It is necessary to ensure a mechanism: the credit status of creditors and the records of credit actions will be permanently stored and cannot be changed; credit platforms will not lose or be tampered with due to hacker attacks, system failures or natural disasters.

6. It is necessary to ensure a mechanism: the evaluation of the credibility of creditors will not be affected by external factors such as their region, race, country, religion, wealth, social level, social identity, etc., and it is absolutely authentic, objective, fair and trustworthy.

## Blockchain technology opportunities

In 2008, with the release of Bitcoin, blockchain technology began to be widely used by enterprises and developers. Blockchain technology makes it possible to create decentralized, trustworthy, immutable, secure, and objective applications.

# Requirements for Blockchain Technology based Digital Credit Communities and Applications

By using blockchain technology, it is possible to implement a decentralized community and application platform that can be comprehensive, objective, authentic, fair, and effective to assess the credit status of creditors. In order to gain widespread use, communities and applications require a platform that is flexible enough to meet the following requirements:

## Support Millions of Users

Competing with businesses like Facebook, Linkedin, Indeed, Freelancer, Upwork and Topcoder, require the blockchain digital credit community and application platform capable of handling tens of millions of active daily users. In certain cases, a digital credit community and application platform may not work unless a critical mass of users is reached and therefore a platform that can handle very large numbers of users is paramount.

## Free Usage

Application developers need the flexibility to offer users free services; users should not have to pay in order to use the platform or benefit from its services. A blockchain digital credit community and application platform that is free to use for users will likely gain more widespread adoption. Developers and businesses can then create effective decentralized digital credit strategies.

## Easy Upgrades and Bug Recovery

Businesses building blockchain digital credit applications need the flexibility to enhance their applications with new features. The platform must support software and smart contract upgrades.

All non-trivial software is subject to bugs, even with the most rigorous of formal verification. The platform must be robust enough to fix bugs when they inevitably occur.

## Low Latency

A good user experience demands reliable feedback with a delay of no more than a few seconds. Longer delays frustrate users and make applications built on a blockchain digital credit application platform less competitive with existing non-blockchain alternatives. The platform should support low latency of transactions.

## High Performance

In order to support high-frequency and large-scale data interactions, the blockchain digital credit community and application platform should be able to use concurrent computing, load balancing, multi-threading, multi-core CPU operations to improve the performance of application execution.

## Openness

To make it easier for developers and enterprises to develop applications using the blockchain digital credit application platform, the platform should be open enough to include: open source codes, documents, and related communities to answer various technologies problems faced by developers and enterprises.

## Decentralization

Decentralization is the core of blockchain applications and a distinguishing feature of traditional Internet applications and blockchain Internet applications. Only when digital credit communities and application platforms have truly achieved decentralization can they ensure the objectivity, fairness, openness, and immutability of their credit assessment.

## Easy to Develop

The blockchain digital credit application platform, if the development is very simple, will will likely gain more widespread adoption.

## Verifiable

Credit evaluations obtained by creditors must be verifiable, so as to ensure the objectivity, authenticity, and validity of the credit assessment.

## Community

The community-based blockchain digital credit community and application platform can better guide its members to participate active interactions and encourage their active participations in community contributions.

## Autonomy

The blockchain digital credit community and application platform need to achieve self-government and encourage their members to engage in positive, meaningful, valuable, positive actions, not to do those negative, meaningless, worthless, negative actions.

## Distributed Storage, Persistent Storage, Immutability

Through distributed, decentralized data storage, data is always stored, cannot be tampered with, and data will not lost due to unexpected events.

## Default and Fraud Prevention, Loss Recovery

In order to prevent default and fraudulent actions in blockchain digital credit applications, such as refusal to repay loans, project failure to perform, crowdfunding scams etc., the platform should establish preventive measures to reduce the risk of such events, once the default and fraud occurred. Can help the funders recover the losses, or minimize the losses of the funders.

## Proactive Credit Assessment

Unlike traditional passive credit assessment models, blockchain digital credit communities and application platforms should allow and encourage members to improve their credit ratings through active, proven actions.

# Consensus Algorithm

The token and transaction portion of Digital Credit will be based on the well-known, decentralized, blockchain consensus algorithm [DPOS](https://bitshares.org/technology/delegated-proof-of-stake-consensus/) (Delegated Proof of Stake) and can implement [BFT](https://en.wikipedia.org/wiki/Byzantine_fault_tolerance) ( Byzantine Fault-Tolerant, Byzantine Fault Tolerance). Different from POW (Proof of Work) consensus algorithm, this consensus algorithm can ensure the decentralization of blockchain applications while ensuring the high performance of blockchain applications.

**Note: In order to develop Digital Credit community and application platform more effective, speed up the launching progress, and improve transaction performance, Digital Credit 1.0 will utilize [EOS.IO](https://eos.io/) to implement tokens and tokens transactions, smart contracts, account managements, role managements and other features. Data storage development will be based on [Tendermint](https://www.tendermint.com/) and [BigchainDB](https://www.bigchaindb.com/). The use of BigchainDB's decentralized and distributed database simplifies and encapsulates blockchain application development and creates an efficient, high-performance blockchain digital credit community and application platform.**

**Note: Digital Credit will use [IPFS](https://ipfs.io/) to store files.**

