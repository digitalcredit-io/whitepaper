# Digital Credit White Paper v1.0

**May 13, 2018**

[Bruce Zhang](https://www.facebook.com/bruce.zhang.35762)

digitalcreditio@outlook.com

[digitalcredit.io](http://digitalcredit.io)


**Abstract:** Digital Credit is designed using a brand new blockchain architecture by implementing POA (Proof of Ability) actions(challenge, competition, test, teaching, posting, ranking, achievement, contribution, review and voting, digital credit evaluation and digital credit actions etc.) to create a decentralized, trustworthy, easy to use, immutable, autonomous digital credit community and application platform. Digital Credit simplifies the blockchain application development and implements a distributed, decentralized MVC framework: dMVC (decentralized Model-View-Control), which includes: model part: data structure, database and data storage; control part : actions, services, account management, role and organization management, tags and categories; Proof of Ability Actions, including: challenge, competition, test, contribution, teaching, post, ranking, achievement, review, voting, etc. ; digital credit evaluations, digital credit actions (including awarding rewards, issuing loans, approving crowdfunding, allowing sales of tickets, etc.), tokens and smart contracts, and dispute resolutions; Views: Clients, etc. This allows the creation of distributed, decentralized, authentic, trustworthy, easy to develop, immutable, safe, objective, fair and autonomous digital credit communities and applications based on POA.

**PLEASE NOTE: CRYPTOGRAPHIC TOKENS(Digital Credit, DGCT) REFERRED TO IN THIS WHITE PAPER REFER TO CRYPTOGRAPHIC TOKENS IN TWO VERSIONS: 1. CRYPTOGRAPHIC TOKENS ON A LAUNCHED BLOCKCHAIN BASED ON EOS.IO. 2. ERC-20 COMPATIBLE CRYPTOGRAPHIC TOKENS ON A LAUNCHED BLOCKCHAIN BASED ON ETHEREUM. ERC-20 COMPATIBLE TOKENS(Digital Credit, DGCT) BEING DISTRIBUTED ON THE ETHEREUM BLOCKCHAIN WILL BE APPLICABLE TO A DIGITAL CREDIT SOLUTION THAT IS COMPATIBLE WITH ETHEREUM: ULTILIZE ETHEREUM TO IMPLEMENT TOKES AND SMART CONTRACTS, ULTILIZE DMVC TO IMPLEMENT OTHER DIGITAL CREDIT FEATURES. MORE DETAILS CAN BE FOUND IN THE [COMPATIBILITY](#compatibility) SECTION.**

Copyright © 2018 [digitalcredit.io](http://digitalcredit.io)

**DISCLAIMER:** This Digital Credit White Paper v1.0 is for information purposes only. digitalcredit.io does not guarantee the accuracy of or the conclusions reached in this white paper, and this white paper is provided “as is”. digitalcredit.io does not make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this white paper are free from error; and (iii) that such contents will not infringe third-party rights. digitalcredit.io and its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this white paper or any of the content contained herein, even if advised of the possibility of such damages. In no event will digitalcredit.io or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special for the use of, reference to, or reliance on this white paper or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses.

<!-- MarkdownTOC depth=4 autolink=true bracket=round list_bullets="-*+" -->

- [Background](#background)

<!-- /MarkdownTOC -->

# Background

## Pain points and Challenges in current credit system

1. Current credit reports and scores have limitations: (i) The credit system is often based on the creditor's current income level, payment and repayment records, credit history, number of applications for credit account, etc. It is impossible to completely and objectively evaluate the credit of the creditor. (ii) Once the creditor has made a mistake, such as accidentally forgetting to repay the credit card, it will have a great negative impact on its credit score. (iii) For freelancers who do not have a stable job, or who are in underdeveloped areas, poverty-stricken areas, or social bottoms, even if they have creditability, they often fails to obtain credit based on traditional credit models. (iv) The credit rating of the creditor is passive and its cannot be improved through active actions.

2. Currently, online-based lending, crowd-funding, and ICO are often fraudulent because the financiers or borrowers are falsifying information and their capabilities are incompetent, ultimately causing losses to the funders. The fundamental reason is that funders cannot perform effective assessment and verification of the true identity and true capabilities of the creditor.

3. In human resources, such as talent recruitment, often candidates will fictionalize or exaggerate their curriculum vitae and personal abilities. Initial interviews and short-term trial periods often fail to effectively test their true level of competence. When the company discovers the capabilities of recruiters are incompetent, it is often too late: corporate resources have been wasted, and there are numerous cases where companies are unable to recruit the right people in key positions and the company's development is delayed.

4. Some underdeveloped areas, poor people, individuals at lower levels of society, even if there are talented people in them, their talents are often wasted due to their inability to be effectively excavated. Because these people are of low birth and lack of social relations and self-powered display platforms, it is harder to obtain job opportunities and social recognition.

5. In some outsourcing areas, such as software outsourcing, design outsourcing and other outsourcing areas, project consignees often cannot effectively verify and assess the actual level of the recipient and suffer losses.

6. In the field of venture capital investment, investors are often unable to effectively verify and evaluate the true level of capabilities of the start-up entrepreneurs and suffer losses; start-up entrepreneurs who have great ideas and action forces are unable to obtain investment because of lack of social relations and connections.

## The keys to a better credit system

1. It must be able to ensure the objectivity, authenticity, and immutability of evaluations of creditors' credit rating, and can fully assess the credibility of creditors.

2. In addition to passively accepting credit assessments, creditors must also be able to actively upgrade their credit rating through positive and meaningful actions.

3. It is necessary to ensure a mechanism: when the creditor happens to defaults and frauds, the loss of the funder is minimized.

4. Must ensure a mechanism: Encourage creditors to engage in positive, meaningful, valuable, positive actions, and not to do negative, meaningless, worthless, negative actions. (ie provide positive and negative feedbacks)

5. It is necessary to ensure a mechanism: The credit status of creditors and the records of credit actions will be permanently stored and cannot be changed; credit platforms will not lose or be tampered with due to hacker attacks, system failures or natural disasters.

6. It is necessary to ensure a mechanism: the evaluation of the credibility of creditors will not be affected by external factors such as their region, gender, race, country, religion, wealth, social level, social identity, etc., and it is absolutely authentic, objective, fair and trustworthy.

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

Decentralization is the core of blockchain applications and a distinguishing feature between traditional Internet applications and blockchain Internet applications. Only when digital credit communities and application platforms have truly achieved decentralization can they ensure the objectivity, fairness, openness, and immutability of their credit assessment.

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

In order to prevent default and fraudulent actions in blockchain digital credit applications, such as refusal to repay loans, project failure to perform, crowdfunding scams etc., the platform should establish preventive measures to reduce the risk of such events, once the default and fraud occurred, the platform can help the funders recover the losses, or minimize the losses.

## Proactive Credit Assessment

Unlike traditional passive credit assessment models, blockchain digital credit communities and application platforms should allow and encourage members to improve their credit ratings through active, proven actions.

# Consensus Algorithm

The token and transaction portion of Digital Credit will be based on the well-known, decentralized, blockchain consensus algorithm [DPOS](https://bitshares.org/technology/delegated-proof-of-stake-consensus/) (Delegated Proof of Stake) and can implement [BFT](https://en.wikipedia.org/wiki/Byzantine_fault_tolerance) ( Byzantine Fault-Tolerant, Byzantine Fault Tolerance). Different from POW (Proof of Work) consensus algorithm, this consensus algorithm can ensure the decentralization of blockchain applications while ensuring the high performance of blockchain applications.

**Note: In order to develop Digital Credit community and application platform more effective, speed up the launching progress, and improve transaction performance, Digital Credit 1.0 will utilize [EOS.IO](https://eos.io/) to implement tokens and tokens transactions, smart contracts, account management, role management and some other features. Data storage development will be based on [Tendermint](https://www.tendermint.com/) and [BigchainDB](https://www.bigchaindb.com/). The use of BigchainDB's decentralized and distributed database simplifies and encapsulates blockchain application development and can create an efficient, high-performance blockchain digital credit community and application platform.**

**Note: Digital Credit will utilize [IPFS](https://ipfs.io/) to store files.**

# Compatibility

With the popularity of the blockchain concept, more and more blockchain applications are being built on existing mature platforms such as Ethereum and Bitcoin. Thousands of blockchain and smart contract applications are built on these platforms. If the digital credit community and application platform can achieve compatibility with these existing blockchain platforms, it will attract more blockchain developers to develop blockchain applications based on Digital Credit, which will have a very positive effect.

Digital Credit 1.0 will utilize EOS.IO to implement functions such as tokens, token transactions, account management, role management, and smart contracts, and these functions will be encapsulated with dMVC. Therefore, the standard version of Digital Credit will be based on the DPOS consensus algorithm powered by EOS.IO (for tokens and smart contracts). Digital Credit 1.0 can also be called Digital Credit EOS.IO.

At the same time, Digital Credit will also implement compatibility solutions for other blockchain platforms, namely: using the tokens and smart contracts of existing blockchain platforms, and using dMVC to implement Digital Credit other features.

For example, Digital Credit will launch an Ethereum-compatible version of Ethereum that uses Ethereum's tokens and smart contracts, and uses dMVC to implement other Digital Credit functions, namely: Digital Credit Ethereum. Bitcoin compatible version will also be introduced, namely: Digital Credit Bitcoin and so on. Other compatible versions will be selectively developed based on the influence and acceptance of relevant blockchain platforms.

In the compatible version, such as Digital Credit Ethereum, tokens and smart contracts for the entire platform are developed based on Ethereum, while the remaining functions are based on dMVC, such as: database and data storage, control (account management, role and organization management, POAs: challenges, competitions, tests, contributions, learnings, posts, rankings, achievements, reviews, votings, digital credit assessments, digital credit credit actions, etc.), user view features. When certain functions of Digital Credit need to be completed based on tokens and smart contracts features, for example, members of the Digital Credit application need to initiate an ICO crowdfunding, then the crowdfunding tokens are  initiated by Ethereum platform other than EOS.IO. Another example: members of the Digital Credit application need to apply for a loan. If the loan is approved, the credit tokens for the member to obtain is from Ethereum, ERC-20-compliant, Digital Credit (DGCT). After Digital Credit is released, Digital Credit (DGCT) released by the official version of Digital Credit (standard EOS.IO version) will be exchanged with ERC-20 compliant Digital Credit (DGCT) released by Ethereum. Users of Digital Credit can flexibly switch the tokens used to settle, trade, and run smart contracts when using the Digital Credit main program.

# Design Patterns

In the traditional software development process, the MVC pattern is widely used. The full MVC name is Model View Controller, which is an abbreviation for model-view-controller. It is a software design paradigm that organizes code using a method of separating business logic, data, and interface display. Business logic is aggregated into one component, and there is no need to rewrite business logic while improving and personalizing custom interfaces and user interaction. MVC is uniquely developed for mapping traditional input, processing, and output functions in a logical graphical user interface structure.

In blockchain and decentralized, distributed application development, it is often necessary to develop a large number of underlying technologies, which are inefficient in development and cannot be applied to the efficiency and mode of modern software development. If distributed, decentralized blockchain application development is as intuitive and fast as some object-oriented languages, such as Java (JPA, Struts2), C#, and Ruby on Rails, it will be very beneficial for the development of blockchain applications.

# dMVC framework (Decentralized Model-View-Control)

The dMVC framework is designed and developed for [digitalcredit.io](http://digitalcredit.io) and is mainly used in an application development framework for the Digital Credit application platform. Development of decentralized distributed application is encapsulated and simplified as simple and intuitive as using Java, C#, and Ruby on Rails to develop applications using the traditional MVC framework.

dMVC will implement a cloud application development platform and a localized application development platform. The cloud application development platform is similar to Ethereum's smart contract platform: developers only need to upload code (Model layer, View layer and Control layer), and can publish their blockchain digital credit application in the cloud without setting up a development environment. By using the localized application development platform, developers should build local development environment (such as using Docker), and develop digital credit applications locally.

dMVC will support mainstream application development languages such as: Java, Javascript, Python, Go, PHP, C#, C/C++.

**Note: In the early lauched version, dMVC may only support certain languages such as Javascript, Python and Java.**

# Model

dMVC will simplify the data model part of blockchain applications. The data model part of dMVC will be similar to JPA (Java Persistence API), that is, developers can create data entities and mappings as easily as creating and processing Java classes.

## Data Structure

The data structure of the model layer in dMVC is very similar to the Java language object. At the same time, dMVC will implement an entity mapping interface similar to JPA in Java: dOPA(Decentralized Object Persistence API). Taking Java as an example, dOPA will implement a Java version of the API:dJPA(Decentralized Java Persistence API). The Java version of dJPA will use annotations to implement the mapping between objects and entities.

Example 1:

```java
@Entity
public class Post extends Asset {

    public String title;
    
    public String content;
    
    public Date postDate;

    @ManyToOne
    public Author author;

    @OneToMany
    public List<Comment> comments;
    
}
```

## Database and Data Storage

dMVC uses BigchainDB to implement decentralized database and data storage, and uses dOPA for encapsulation, simplifying data operations and storage functions. Taking dOPA's Java implementation of dJPA as an example, in dJPA, data is inherited from the Asset class and needs to be the Owner of the data. At the same time, the subclass of Asset can only perform two operations: create and transfer, and cannot perform update and delete similar to traditional relational databases.

Taking the Post class of Example 1 as an example, when we need to create a Post class entity, we need to execute a statement similar to the following:

```java
post.title = "Post Title";

post.content = "Post Content";

post.owner = bob;

post.metadata = metadata;//optional

post createdPost = post.create();//post object has been created and persisted. the createdPost object now can obtain its transaction id by getTransactionID method.
```

When we need to transfer the Post object to another role alice, we need to use the transfer method:

```java
Post transferredPost = createdPost.transferTo(alice);
```

In this way, the createdPost object no longer belongs to bob but belongs to alice.

When bob no longer needs this post object, however, he can't find another object to transfer, then he can transfer the post object to the recycle bin: recycleBin, or transfer it to himself, but to mark that the post object has already been discarded.

```java
createdPost.transferTo(recycleBin);
```

Or

```java
metadata.status = Metadata.OBSOLETED;

createdPost.transferTo(this, metadata);
```

When bob needs to modify the post object, he needs to transfer the post object to himself, providing the modified post object as a parameter. By default, the system will use the current Timestamp as the post modification time.

```java
createdPost.transferTo(this,updatedPost, metadata);
```

**Note: When the type of stored data is a file, dOPA will store the file in the IPFS rather than through BigchainDB.**

## Data Query

dOPA's data query is very similar to JPA, using dJPA as an example:

Find objects by the transaction id:

```java
Post aPost=Post.findByTransactionID(transactionID);
```

Find the object by owner:

```java
List<Post> posts = Post.findByOwner(owner);
```

Find all the objects:

```java
List<Post> posts = Post.findAll();
```

You can also limit the fetch result number:

```java
List<Post> posts = Post.all().fetch(20);//fetch the first 20 result
```

Find by field:

```java
List<Post> posts = Post.find("byTitle", "My first post").fetch();
```

Finding via JPQL:

```java
List<Post> posts = Post.find(
    
    "select p from Post p, Comment c " +
    
    "where c.post = p and c.subject like ?", "%hop%"
    
);
```

## Tags and Categories

Subclasses of Asset objects can declare their data's classifications and tags in metadata to facilitate querying. such as:

```java
post.metadata.categories.add(businessCategory);

post.metadata.tags.add(financialTag);
```

Remove categories and tags:

```java
post.metadata.categories.remove(businessCategory);

post.metadata.tags.remove(financialTag);
```

# Control

dMVC provides two control methods: one is Actions, which mainly deals with http request and http post; and the other is Services, which mainly uses json to perform data interaction between client and server.

## Actions

Actions is a bit similar to Struts/Struts2 in Java. It handles related behaviors by parsing user http requests and http posts.

For example: http request:/posts?category=business

We can have a Posts Action class that specifically handles post-related action classes:

```java
public class Posts extends Controller {
 
    Public static void getPostsByCategory(String category) {
    
        List <Posts posts = Post.findByCategory(category);
        
        render(posts);
        
    }
 
}
```

## Services

Services are somewhat similar to the RESTful Services in Java, through the json to achieve data interaction between the client and server.

For example: http post:/postService

Json:

```javascript
{'asset': {'data': {'post': {'title': 'new post',

    'content': 'post content'}}},
    
 'id': None,
 
 'inputs': [{'fulfillment': {'public_key': 'GtMiC8DQ274d3wsW7R4MMNvMU6DLcd4U9vg43tu9fFTp',
 
    'type': 'ed25519-sha-256'},
    
   'fulfills': None,
   
   'owners_before': ['GtMiC8DQ274d3wsW7R4MMNvMU6DLcd4U9vg43tu9fFTp']}],
   
 'metadata': {'category': 'business'},
 
 'operation': 'CREATE'
 
 }
 ```
 
 The server method:
 
 ```java
 public static void handlePostService(String json) {
 
    Json requestJson = new Json(json);
    
    if (requestJson.operation.equals("CREATE")) {
    
         //create a post
         
        ...
        
        renderJSON(returnJson);
        

    } else if (requestJson.operation.equals("TRANSFER")) {
    
        //transfer a post
        
   ...
        renderJSON(returnJson);
        
    } else {

    }    
    
}
```
## Account Management

### Account Name

The maximum length of the account name of Digital Credit is 12 characters (Chinese character will occupy 2 characters, if the account name is all Chinese, up to 6 Chinese characters are supported). 12 characters including English characters (a-z, A-Z), numbers (0-9), underscore (_), underscore (-), UTF-8 encoded characters of other countries (eg Simplified Chinese, Traditional Chinese, Japanese, Korean, etc.)

When creating an account, Digital Credit will detect the name of the account in order to avoid violated content such as verbal abuse, language intrusion, discrimination, verbal violence, and political infringement.

### Account Actions

The account can perform some account-related actions, such as open/hide account owner's digital credit information, competition results, skill information, and so on. The application of Digital Credit may require the account owner to open certain rights to run a digital credit application. For example, an online loan application requires the account owner to show the digital credit record for the application, or a software development competition application that requires the account owner to show information about the skill information and program development-related skills to the application; or an ICO, crowdfunding application requires crowdfunders to show information about the relevant skills they have described.

The account owner can choose to grant permissions to certain actions, applications or some other accounts (such as friends).

### Friends, Whitelists, Blacklists, and Groups

The account owner can add other accounts as friends, or add other accounts to whitelist, blacklist, or a group to perform certain actions in batches, such as setting up their own digital credit information that only friends are visible, or only certain applications are visible.

### Personal Account, Application Account, Action Account and Group Account

The account can represent individuals, ie. the personal accounts. The account can also represent the application, ie. the application account. The account can also represent a series of individual accounts or application accounts or a collection of action accounts or group accounts. For example, there are four personal accounts: @Bob, @Alice, @Tom, @Cathy, there is an application account: @DCLending and action account: @DCcompetition. Among them, @Bob and @Alice formed a company @CompanyA, then @CompanyA is the company account; @Tom and @Cathy formed a company @CompanyB. @CompanyA and @CompanyB and @DCLending belong to the parent company @CompanyC.

There is a correlation between personal accounts, application accounts, action accounts, and group accounts. For example, membership: @Bob and Alice are members of @CompanyA; contractual relationship: @Bob has a two-year work contract with @CompanyA; affiliation: @DCLending and @DCcompetition belong to @CompanyC, etc.

### Permission Management

Accounts can manage permissions for account actions. Account privileges can be assigned to a range of personal accounts, application accounts, or group accounts. Digital Credit manages account permissions by setting account weights and account action thresholds.

The following example is referenced in EOS.IO:

<img align="center" src="https://github.com/digitalcredit-io/whitepaper/blob/master/eos%20permission.jpg" />

In this example, the @multisig account has three account action permissions: owner, active, and publish. The account of the owner permission is @bob and @stacy. The weight value of each account is 1, and the threshold of owner permission is 2. This means that once you want to obtain the owner permission of the @multisig account, both @bob and @stacy are required to issue permissions. The active threshold is 1, and both @bob and @stacy have a weight of 1, which means that only one person, @bob or @stacy, is required to issue permission.

### Identity Verification

In Digital Credit, certain actions require participants to process identity verification. Identity verification mainly guarantees the identity authenticity of the participants, to make sure the account holder does not create multiple trumpet for the same person and affects the fairness and objectivity of certain actions.

### Account Data

The naming convention for data access in the account is @+account name+(.+ account data fields, which can be multi-level nested).
Example: @bob.skills.English = B, indicating bob's English skill level is B.

The account owner can independently open/close permissions of his/her own account data, and can open certain account data for friends, groups, applications or actions. When an account uses an application or perform a POA action, the application account or action account will require the account user or participant to grant permissions to certain data access privileges.

Account data permissions are: NA (unavailable), R (read only), RW (read and write), W (write only).

One example:

When @bob uses an application called competitionApp, the @competitionApp account requires @bob to open permissions:

@bob.skills.Java read and write

@bob.competition read and write

@bob.credit read and write

@bob.groups read

@bob can use the competitionApp after @bob has confirmed all of the @competitionApp access requests. @bob will not be able to use the competitionApp if @bob disagrees with any one of the requests.

## Role and Organization Management

Each account can belong to an organization, such as @bob, @stacy and @alice belong to a team @teamA, where @bob is the "Team Leader", so when you get @bob.role.teamA, the return value should be "Team Leader."

In an organization, you can define a lot of actions and permissions. For details, refer to the [Permission Management](#permission-management) section.

For example: @bob's role in @teamA is both the "Team Leader" and "Reviewer", and @stacy is the "Reviewer" in TeamA. Then when @alice submits a proposal for review, it needs to be reviewed by both @bob and @stacy before it can be passed.

For the self-organizing management purpose, Digital Credit will establish a mechanism to encourage community members to actively participate in the community to contribute to get higher organizational roles. For example, when a member whose contribution reached a certain level and his/her related ability meets the standard at the same time, Digital Credit can automatically promote the member's role to Reviewer. Reviewer is more privileged than the regular member and can review the content posted by the regular member. (Like traditional BBS forum management, forum administrators can assign permissions to different sections, such as assigning moderators, etc.)

## POA Actions

Members of Digital Credit can demonstrate their ability through proactive actions, that is, POA Actions. Proof-of-Ability actions include challenges, competitions, tests, contributions, teaching, postings, rankings, achievements, reviews, voting, and more.

### Skill Rating

In the ability proving actions, skill ratings for participants can be included. If it is an automatic review, the skill rating is automatically determined by the system; if it is a manual review, the skill rating is determined manually. For details of the review and its decision-making model, please refer to the [Review](#review) section. The ability proving actions can be used to judge the participants’ multiple skills. When skills is judged by the ability proving action, the name of the action will be included in the account data of the participants. For example: @bob.skills.Java.level.competitionA = A, which indicates bob's Java skills and was rated A in the competition named competitionA.

### Credit Rating

In the ability proving actions, the credit performance of the participants can also be rated, but only the contractual proof of ability can add credit ratings. For example, sponsor A initiates a competition, and eligible participants will receive a certain amount of tokens as startup funds, but require participants to submit solutions within a specified period. If the participant fails to submit the solution on time, it can be regarded as a failure of compliance, and the credit compliance rating of the participant will be affected. For example: @bob.credit.compliance.competitionA = D, it means that Bob's performance credit in the competitionA is D.

### Challenge

Challenges can include competitions in a broad sense. In Digital Credit, challenges can be unranked and winner-undetermined. For example, for some charity challenges, the challenge creator only needs to assess whether challenger has reached the challenge goal. It does not need to determine the winner(the challenge can also determine the outcome and the ranking, but generally such action will be performed as competition).

The action phases of challenge in Digital Credit include:

Challenge Initiation Phase

Challenge Registration/Registration Phase

Challenge Phase

Submission Phase(if any)

Challenge Review Phase

Results Announcements Phase

Challenge Award Phase

The sponsor or creator of the challenge can set rewards for the challenger after achieving/exceeding the challenge goal. Rewards can be tokens, achievements, titles, or offline rewards.

The sponsors or creator of the challenge can set challenger registration requirements. During the challenge registration phase, participants will fail to participate in the challenge if they cannot meet the basic requirements for participating in the challenge.

The sponsors or creators of the challenge need to set deadlines for the challenges. In some cases they can set the duration of the challenges to be long, such as one year or even longer. However, Digital Credit recommends setting milestones to ensure that participants in the challenge are participating the challenge step-by-step.

Some challenges require challengers to upload solutions online, such as solutions to a problem. Challengers can upload their plans multiple times before the deadline of the challenge, but they will be subject to the last upload.

After the challenge phase, challenge needs to be reviewed. There are two modes of review: automatic review and manual review. Please refer to the [Review](#review) section for specific assessment mode.

After the review phase, the results of the challenge will be announced. If so, the challenger's skill rating and credit rating will also be judged and recorded.

According to the smart contract, the challenge winner will receive a corresponding token reward (which can be single or multiple).

After the challenge results are announced, the challenger’s performance will be recorded: @bob.challenges.challengeA. In this example, bob's achievements and data in challenging challengeA will be recorded, for example: @bob.challenges.challengeA.score = 800. The general challenge is to record whether the challenge succeeded, usually identified by isSuccess. For example: @bob.challenges.challengeA.isSuccess=true, indicating that the challenge was successful.

### Competition

The competition is a kind of multi-person participation, and ultimately it is necessary to determine the outcome of the competition. There is also a situation when all the score of the participating contestants does not meet the standard. In this case, the competition may not have winners and rankings.

The action phases of the competition in Digital Credit include:

Competition Initiation Phase

Competition Registration Phase

Competition Phase

Submission Phase (if any)

Competition Review Phase

Results Announcements Phase

Competition Award Phase

The sponsor or creator of the competition can set the prizes for the winner of the competition (which can be determined by competition ranking). Rewards can be tokens, achievements, titles, or offline rewards.

The sponsor or creator of the competition can set the registration requirements of the contestants. During the registration phase of the competition, if participants cannot meet the basic requirements for participating in the competition, they will fail to participate in the competition.

The sponsors or creators of the competition need to set the deadline for the competition. In some cases they can set the duration of the competition to be very long, such as one year or even longer. However, Digital Credit recommends setting milestones to ensure that participants in the competition are participating the competition step-by-step.

Some competitions require contestants to upload solutions online, such as solutions to a problem. Participants can upload their proposals multiple times before the deadline of the competition, but they will be subject to the last upload.

After the competition phase, competition needs to be reviewed. There are two modes of review: automatic review and manual review. Please refer to the [Review](#review) section for specific assessment mode.

After the review phase, the results of the competition will be announced (ranking, scores, etc.). If so, the skills rating and credit rating of the participants will also be judged and recorded.

According to the smart contract, contest winners will receive corresponding token rewards (which can be single or multiple).

In programming or algorithm competitions, Digital Credit provides a virtual compiler environment such as C, C++, Java, Go, Python, and so on. Contestants enter codes and submit in a virtual compilation environment.

After the results of the competition are announced, the results of the participants will be recorded, for example: @bob.competitions.competitionA. In this example, the results and data of bob in competition competitionA will be recorded. Generally, the competition records needs to include the ranking value, for example: @bob.competitions.competitionA.rank=3.

### Test

Test is an action that tests the skills and abilities of participants and verifies whether their ability or skills meet the standards. The standardized test action includes the process of setting testing questions, testing, scoring.

Test action is mainly for the tester's ability or skills, but also can be irrelevant to ability or skills such as psychological testing. However the main purpose of the test is to assess the tester's ability or skills, and give corresponding rating.

The initiator of the test can first prepare a question bank and classify the questions from the question bank, such as single choice questions, multiple choice questions and so on. The initiators of the test can specify certain questions or just select the questions randomly from the question bank.

The early versions of Digital Credit prefer automatic review to tests. In other words, it tends to be more objective.

The action phases of tests include:

Questions Preparing Phase

Test Initiation Phase

Test Registration Phase

Test Phase

Test Scoring Phase

Results Announcements Phase

In programming or algorithm tests, Digital Credit provides a virtual compiler environment such as C, C++, Java, Go, Python, and so on. Testers enter codes and submit in a virtual compilation environment.

After the review phase, the results of the test will be announced and the testers' skills or abilities will be recorded and evaluated.

At the same time, the test scores of the testers will be recorded. For example: @bob.tests.testA.score=85.

### Contribution

In Digital Credit, contributions are mainly directed at the contribution to the Digital Credit community, including:
Contributions to the Digital Credit main program code (code effectively meets Digital Credit's programming requirements and passes review)
Contributions to the Digital Credit main program BUG fixing and approved
Contributions to the testing and verification of the Digital Credit main program and approved
Diversified client for Digital Credit main program, such as mobile phone, computer and web and approved
Build a node/super node for Digital Credit and pass the review
Develop an effective application for Digital Credit and submitted to application market and approved
Provide effective marketing solutions (such as advertising and promoting) for Digital Credit and approved
Provide effective and constructive suggestions for Digital Credit and is accepted.
Provide secure testing and repair for Digital Credit system and approved.

Once the contribution has been reviewed by Digital Credit, the contributor will receive a certain amount of reward, and the contribution will be recorded. Digital Credit divides the members' contribution levels into: S, A, B, C, and D.
S: S+++, S++, S+, S, S-, S--, S---
A: A+++, A++, A+, A, A-, A--, A---
B: B+, B, B-
C: C+, C, C-
D

The rewards for different levels of contribution are also different.

When a member's contribution is recorded, its contribution is named, naming convention: contribution category. contribution time
For example: @bob.contributions.mainCode.201809031400
For the above contributions, we can read the contribution related data from the contributor: contribution content, contribution time, contribution rating, and contribution award.
For example: @bob.contributions.mainCode.201809031400.level = B+

### Teaching

Digital Credit encourages members to provide free teaching courses for those who lack of skills. Teaching can also be paid (paid in tokens), but Digital Credit encourages open, free content for those who lack of skills or abilities. Each teaching participant and finisher can rate the teaching feedback. Teaching and courses need to be reviewed before they are released.

### Posting

Users can publish digital content in Digital Credit, including: articles, videos, photos, paintings, designs, music, games and more. The digital content published by the user needs to be reviewed before it can be announced. Content review includes: whether the published content contains personal attacks, pornography, violence, political infringement, misconduct, excessive exaggeration, deception, etc.; whether the published content is positive and meaningful.

Digital content published by users can be charged or free of charge. At the same time, digital content published by users will have digital copyright certification.

Digital content readers, viewers, and users can evaluate digital content. User's evaluation of digital content, overall evaluation, etc. will be recorded.

In addition to articles, digital content published by users as files will be stored in IPFS.

### Ranking

Ranking is a sort of action that ranks the user's ability action results, user ability scores etc., such as the ranking of contestants in a certain contest, the ranking of testers, or some common rankings, such as the ranking of user's contribution, user skills, etc..

The ranking will be based on the ranking algorithm. The ranking algorithm can be based on the Digital Credit main program or can be a customized program.

### Achievement

Achievement is some of the system's preset goals that users reached. For example: 30 successful contributions, successful in the top three in a competition and so on. Achievement can be preset by the system or customized by the application developer. When the user reaches an achievement, his/her achievement data will be stored.

### Review

Review is one of the most critical actions in Digital Credit, used to judge user actions, submitted content, user contributions, user capabilities, and skills.

#### Decision Mode

The review will have two decision modes: the auto review mode and the manual review mode.

#### Automatic Review

Automatic review is a process of objective automatic evaluation of user action, submitted content, and user contributions in accordance with pre-established conditions, rules, and algorithms. For example, if a test is an objective question (single choice and multiple choice) based test, the answer to the test is unique and objective, and the results can be obtained in an automated process. Automatic review procedures, rules, conditions, and algorithms all need to be submitted after repeated testing.

After the auto review is over, the results of the review, user-related capabilities, and credit data are also recorded and written.

Note: In the initial development of Digital Credit, in order to ensure the objectivity of the review, it would be more inclined to use the mechanism of auto-review decision-making as early as possible to prove the action.

#### Manual Review

When the review process cannot be automatically assessed through pre-defined procedures, rules, conditions and algorithms, manual review is required. Manual review is the process of manual evaluation by the reviewers.

Manual review includes the review board, scorecards, results aggregations, appeals, re-reviews, etc.

#### The review Board

The reviewers are users of Digital Credit community who have manual review qualifications. In Digital Credit, the reviewers are determined according to the skill and ability classification that the users who meet the qualifications of a certain type of skill or ability are qualified for manual review and will be included in the review board of such skills or abilities. For example, @bob is a Java language reviewer, but not a graphic design reviewer. To become a reviewer in a certain field, users need to reach certain capability conditions and contributions. The advantage of being a reviewer is that the reviewer can not only have the power to review the action in a certain field, but also get rewards from it, such as token rewards, and better ability and credit evaluation.

The reviewer' review results are public to the users being reviewed and are not visible to other reviewers. If the user is dissatisfied with the results of the review, he can file a complaint and request a re-review. If the user being reviewed feels that the evaluation of the review is seriously lacking in impartiality or has serious doubts about the assessment ability or skills, an arbitration application may be initiated. Once an user being reviewed initiates an arbitration application, it is evaluated by a higher-level reviewer, such as: the initiator of ability action, the owner of the ability application, or the system administrator. After a certain ability action has ended, such as a competition, the sponsors of the ability action can evaluate the performance of the reviewers, and the participants of the ability action can also evaluate the performance of the reviewers.

The reviewers are hierarchical. Higher-level reviewers receive higher rewards than lower-ranking reviewers. The rating of reviewers is determined based on their ability, review performance and contribution. The rating of the reviewers can be raised and lowered according to the performance of the reviewers, and even be disqualified from the review board.

The awards received by the reviewers are also related to the workload and difficulty of the review. For example, the more participants participate in the ability actions to be reviewed, the more difficult the review is, and the higher the reward is. In the same way, feedback from sponsors and feedback from sponsors of good action are better reviewed, and rewards obtained are also higher.

The number of reviewers is determined by the initiator of the ability action, generally not less than 3 and no more than 7 persons. The initiator of the ability action can set up a chief reviewer. The chief reviewer has a higher proportion than the other reviewers (but no more than 50%) and can receive higher rewards. When the ability sponsor initiates the ability action, after setting the number of reviewers, the number of chief reviewer, and the ability, skills, evaluation, and credit requirements that the reviewers need to meet, if the ability or skill requirements are met, the qualified reviewers may apply for registration. As long as the reviewers' ability, skills, evaluation, credit, and other requirements are met, his application for ability action registration will immediately be passed.

After the sponsor of the ability action has set the proportion of the chief reviewer (the proportion of the general chief reviewer is 30%-50%), the proportions of the other reviewers will be evenly distributed. If there is no chief reviewer, the proportion of all reviewers is evenly distributed. The scores of the participants in the ability action are finally obtained by summing up all the reviewers' scores.

The grades or scores of the reviewer will be downgraded or downgraded if he/she:

The reviewer failed to review and submit the scorecard on time.

The evaluation of the reviewer was seriously unfair and was successfully arbitrated by the participants.

The ability or skills of the reviewer did not meet the criteria and was successful arbitrated by the participants.

During the review process, the reviewer had linguistic violence, discrimination, personal assault and political infringement.

After the review process is over, the sponsors and the participants been reviewed of the ability action can evaluate the performance of the reviewers, which will also affect the rating and credit of the reviewers.

#### Scorecard

If a certain ability action is about to be initiated, the publisher of ability action needs to set a scorecard, and can also select the default scorecard provided by the ability action application itself. The reviewers need to score according to the scorecard and give the reason of each score.

#### Result Aggregation

After the review process is over, the scores will be aggregated according to the proportion of the reviewers and published to the reviewers. Participants can view the reviewer's rating sheet and the reason for the rating.

#### Appeal

When the participant to be reviewed is not satisfied with the rating of the assessment, a complaint may be initiated for a rating item. Once the participant initiates an appeal, the reviewer needs to answer and handle the appeal of the participant.

#### Re-review

The reviewer only need to answer the rating items that the participant questioned, and respond to the participant. After the Re-review, the reviewer may choose whether to amend the review score.

### Voting

Voting is an action of voting through resolutions. Digital Credit will use voting in community building, community democracy, and certain important and controversial issues.

When the community members meet certain qualifications, they will have the right to vote. After the voting is initiated, community members can choose to exercise their voting rights or they can give up.

After the voting is completed, the voting results will be announced and Digital Credit will execute the voting results based on the results of the voting resolution.

Voting itself can be used as a proof of ability, but voting itself is only a resolution for the community construction of Digital Credit, community democracy, or certain important and controversial issues. Digital Credit does not recommend that voting action be a hard ability requirement.

### Custom Ability Proof Action

In addition to standard ability proving actions such as challenge, competition, testing, teaching, posting, ranking, achievement, contribution, review, voting, digital credit application developers can customize new proof of ability actions. The application needs to undergo Digital Credit community review and repeated testing before its application can be put on the Digital Credit application market.

## Digital Credit Evaluation

Digital credit evaluation is the process of comprehensive evaluation of the user's digital credit. Digital credit evaluation often occurs when users need to perform some digital credit actions (such as applying for a loan, applying for crowdfunding, selling tickets, etc.).

Digital credit evaluation is a process that is performed automatically by the Digital Credit system and relies on programs, data, and algorithms to run. When Digital Credit conducts digital credit evaluation for an account holder, it will by default obtain the Read permission of all ability data, ability action data and credit data under the evaluation account, and Read and Write permission of the credit.evaluations field under the account. If the account holder rejects this permission request, the digital credit evaluation process will not be performed.

Digital Credit acquires account abilities, ability action data, and credit data using the list method. Take account body @bob as an example:

@bob.listAll, gets all field properties that can be read (or read/write) under @bob. If the field access under the name of @bob is NA, the relevant fields will not be displayed after the list method is executed.

@bob.listSkills, get the field properties of all ability evaluations under @bob.

@bob.listPOA, get all POA field properties under the @bob name.

@bob.listCredit, get the field properties of all credit data under the @bob name.

If we execute @bob.listAll, it will return the following result:
```
@bob.skills(R)
@bob.competitions(R)
@bob.challenges(R)
@bob.tests(R)
@bob.contributions(R)
@bob.teachings(R)
@bob.posts(R)
@bob.ranks(R)
@bob.achievements(R)
@bob.reviews(R)
@bob.votings(R)
@bob.credit(R)
```

We can further use the list method for fields under @bob, for example: @bob.credit.listAll, which returns the following result:
```
@bob.credit.compliance(R)
@bob.credit.evaluations(RW)
@bob.credit.disputes(R)
@bob.credit.creditActions(R)
```

We can see that the access right of the @bob.credit.evaluations field is read and write because after the digital credit evaluation is over, the evaluated digital credit data is written into the @bob.credit.evaluations field.

When Digital Credit conducts a digital credit evaluation on an account holder, it analyzes the ability rating, ability action, and credit data under the name of the account holder. The analysis process relies on algorithms that have been repeatedly tested and verified. The algorithm will be open source, and will continue to be updated and optimized.

### Central Account

When the Digital Credit main program is launched, one or more central accounts will be created. The Central Account is mainly responsible for issuing rewards, loans, and compensation for losses to community users.

The security design of the central account is different from the general account:
1. The central account is not controlled by a single key. Each transaction of the central account will communicate with at least 21 super nodes. At least 2/3 of the super nodes (ie, at least 14 super nodes) confirm the legitimacy of the transaction, then the transaction will be processed. Therefore, the central account cannot be controlled by any single individual.
2. Transaction actions and rules of the central account will be determined and cannot be changed once Digital Credit is officially launched.
3. The source code related to the transaction action of the central account can not be changed by single person when Digital Credit is officially launched.
4. Each super node running Digital Credit will verify the consistency of the central account code when performing central account-related operations.

### Autonomous, Positive and Negative Actionss

The construction of the Digital Credit community is highly dependent on self-government and encourages community members to engage in positive, meaningful, valuable, and positive actions, and not to engage in negative, meaningless, worthless, or negative actions.

Autonomy includes positive actions and negative actions, and positive actions include:
1. Awards (including token rewards)
2. Upgrade ability, credit rating
3. Issue title
4. Role promotion (for example, from ordinary members, to become a judge in a certain area)
5. The community broadcasting the action as a good example

Negative actions include:
1. Penalty (including token punishment)
2. Reduced ability, credit rating
3. Role demotion (for example, from a certain area reviewers to ordinary members)
4. Prohibit transactions
5. Community informs its violations
6. Restricted access (such as the prohibition of lending, crowdfunding, selling tickets, and participating in certain ability proving actions)
7. Close account

## Digital Credit Credit Action

Different from the ability proving action, the digital credit credit action is based on the ability and credit status of the creditor. Its specific performance is to award awards, issue loans, approve crowdfunding, and allow tickets to be sold.

### Awarding Rewards

The reward in credit action is not the same with the reward in the ability proving actions. The issuer of the reward in credit action is the central account, and the reward issuer in the ability proving action is the initiatorof the POA. Awarding a reward is a special type of digital credit. Once awarded, rewards will not be withdrawn.

The award is mainly for members who have contributed to the construction of Digital Credit community. Please refer to the [Contribution](#contribution) section for details. Awarding awards is generally an active action of Digital Credit. The main purpose is to encourage members of the Digital Credit community to make positive and meaningful contributions to the community.

### Issuing Loans

After Digital Credit evaluated the digital credit of the creditor, it can issue loans to the creditor. Loans can be interest-free or with interest. The entity applying for a loan needs to be authenticated.

The issuing entity of the loan may be the central account of Digital Credit, or it may be a third party. The qualifications of the third party issuing the loan need to be approved by Digital Credit.

The tokens for issuing loans are generally DGCT, and can also be digital tokens such as EOS, ETH, Bitcoin and more. The loan token issued from the Digital Credit Central Account can only be DGCT.

The loan has a loan term and a repayment method. The borrower can sign a smart contract with the lender according to the relevant loan term and repayment method.

When approaching the loan repayment date, Digital Credit will check the borrower's repayment account address. If it finds that the balance of the repayment account is insufficient for repayment, a notification will be sent to remind the borrower. When the borrower fails to repay the loan on time, its due date will be recorded in its credit history. When the borrower is overdue for a long period of time, the loan issuer may request Digital Credit to recover the loan after a dispute has been filed. Digital Credit’s recovery of loans includes freezing accounts, reducing credit ratings, recording defaults, and even broadcasting violations.

### Approving Crowdfunding

In Digital Credit, crowdfunding can include crowdfunding with token issuance, ie, ICO, or crowdfunding without token issuance (crowdfunding is DGCT, BTC, ETH, EOS or other tokens). Individuals applying for crowdfunding need to have identity verification.

In the official release of Digital Credit, Digital Credit EOS.IO will support the token ICO issued through EOS.IO; Digital Credit Ethereum will support the token ICO issued by Ethereum.

When ICO crowdfunding applications are issued on Digital Credit, Digital Credit requires ICO fundraisers to:

1. The ICO fundraiser must apply for an ICO release in the form of an organization. The minimum number of people in an organization is two.

2. The members under the organization applying for the crowdfunding of ICO must meet basic skills requirements. For example, ICO organizations need to divide the roles of members in an organization, such as team leaders, developers, designers, testers, and so on. If the ICO project is planned to be developed in the C/C++ language, the developer role in the organization should meet the minimum skill requirements for C/C++ that can perform ICO project. These developers can demonstrate their own C/C++ skill rating by participating in competitions, challenges, tests, and other capabilities to meet the requirements of participating in the ICO project. Digital Credit does not require all members in the ICO project organization pass the skill requirements, but will request the number of members required to meet the criteria based on the amount of crowdfunding they apply for. For example, the maximum amount of crowdfunding for the ICO applied for is 20 million U.S. dollars, and the number of people whose skills and ability requirement is higher than 50%, and the minimum is 1 person. If the amount of crowdfunding for applying for ICO is higher, the proportion of required standards is higher.

3. The organizations that apply for launching ICOs need to provide the exact project schedule and milestones, as well as the number of crowdfunding tokens that need to be obtained after each milestone is completed. ICO crowdfunding tokens will not be transferred to the ICO application group's account all in one. Instead, they will be transferred in batches according to different phases and milestones. When the ICO application organization failed to complete the milestone target on schedule, and after the Digital Credit found that the project had a large gap with the milestone target and progress was slow, Digital Credit could temporarily stop transferring the subsequent ICO crowdfunding token to the ICO organizational account. If the ICO project ceases to be updated, Digital Credit believes that it is unable to perform or fraud, and Digital Credit can return the remaining crowdfunding tokens to the funders. At the same time, the credit rating of the ICO project organization and all members of the organization will be lowered, or even prohibited from trading, permission limits, closure of accounts, and even the entire network. The first Crowdfunding Coin obtained by the ICO crowdfunding organization is the Startup Tokens, and the start-up Tokens must not be higher than 40% of the ICO Total funding amount.

4. The ICO project for the organization that applied the ICO must be open-source at Github. Digital Credit will regularly check the progress of the open source project. If progress does not meet expectations or if there is no progress at all, Digital Credit will warn the project holder, or even suspend the follow-up token transfer for the ICO project. 

For crowdfunding actions without token issuance, it is similar to crowdfunding with token issuance. Crowdfunders ultimately need to submit a shaped product, service, and work to complete the initial crowdfunding performance and also need to set milestones for crowdfunding projects. With regard to crowdfunding without token issuance, the issuer may be an organization or individual and the crowdfunding may be as low as one. Fundraisers must meet the minimum skills required for their crowdfunding project. Similar to ICO crowdfunding, when crowdfunding fails to complete milestones on schedule, or progress is slow, or has no progress, or crowdfunding projects have stopped, Digital Credit can stop the follow-up of the supply of crowdfunding tokens and return the crowdfunding tokens.

### Allowing Sales of Tickets

Tickets are credits that require advance approval through Digital Credit. Tickets are similar to tickets for live concerts, movies, ball games, and courses. It is the content provider in the Digital Credit that has previously accessed the content or the consumer has received a replacement coin to allow him access to use the content. Digital Credit will review the ability of members who need to sell tickets, and if they can meet the requirements, they will be allowed to sell tickets.

If the purchaser of the ticket is dissatisfied with the content provided by the seller’s promise of the ticket, a dispute can be made through Digital Credit. After the arbitration of Digital Credit found that the seller of the ticket did not complete the commitment to the contents of the ticket purchaser’s content, it could record its credit default action and even suspend its ticket sales.

### Other Custom Digital Credit Credit Action

In addition to awarding actions, issuing loans, approving crowdfunding, and allowing sales of tickets, Digital Credit allows application developers to customize other credit actions for digital credit, but needs to undergo digital credit review and repeated testing. Applications can be placed on the Digital Credit application market.

## Tokens and Smart Contracts

### Token

The tokens in Digital Credit, in the first official release, will have two forms: 1. Token DGCT through EOS.IO. 2. Token DGCT through Ethereum. Both of these tokens are called DGCT, but one is a token that EOSI.IO implements, and one is an ERC-20-compatible token. In the official release process, users can switch between two token solutions and can exchange one another. In subsequent releases, Digital Credit will also be compatible with Bitcoin, Bitcoin Cash or other tokens.

The credit issuance part of Digital Credit is encapsulated by dMVC. Developers of Digital Credit do not need to know EOS.IO, C/C++ and Solidity specifically and can easily write programs to release tokens.

### Smart Contract

The smart contract in the Digital Credit EOS.IO version is based on EOS.IO, while the smart contract in the Digital Credit Ethereum version is based on Ethereum. In Digital Credit, smart contracts include:
1. A reward contract that demonstrates the ability to challenge, competition, posting, teaching, contribution, review, etc.
2. Contracts for awarding credits, loans, crowdfunding, ticket sales, etc. in digital credit credit actions.

When both parties to the contract agree and sign the contract, the contract comes into effect, and when the terms of the contract are fulfilled, the contract is executed.

Digital Credit encapsulates smart contracts with dMVC. Developers of Digital Credit do not need to know EOS.IO, C/C++ and Solidity specifically and can easily write programs to implement smart contracts.

## Dispute Resolution

### Default or Fraud Treatment

When there is a breach of contract or fraud in Digital Credit, such as overdue loans, ICO projects not proceeding as planned, ICO fraud, etc., Digital Credit will conduct default treatment, including:

1. Penalty (including token punishment)
2. Reduced ability, credit rating
3. Role demotion (for example, from a certain area reviewers to ordinary members)
4. Prohibit transactions
5. Broadcast its breach of contract in community
6. Restricted access (such as the prohibition of lending, crowdfunding, selling tickets, and participating in certain POAs)
7. Close account

### Minimize Loss and Recovery

Digital Credit sets a lot of strict rules to ensure that when users experience default or fraud, the damage they suffer can be minimized. Digital Credit also specifies some rules to ensure that when losses occur, user losses can be minimized in the shortest possible time.

For example, Digital Credit has set strict ICO requirements. For example, the tokens raised by ICO will not be issued to the project party all in one, but will be distributed in bulk according to the actual progress of the project. For details, see the section [Approving Crowdfunding](#approving-crowdfunding).

### Loss Compensation

In the event that Digital Credit’s own errors, loopholes, bugs, and other mistakes cause user losses, the Digital Credit [Central Account](#central-account) will compensate for losses based on the user’s specific losses.

### Account Loss Prevention and Account Recovery

In order to prevent user accounts from losing control, Digital Credit has set up the following security measures:
1. Users need to set security verification questions, mobile phone number, email, etc. when setting up an account.
2. The user can fill in identity authentication information when establishing an account.
3. The user can choose to fill in the security verification question when the account private key is modified, or enter the mobile phone verification code, email verification code etc..
4. The user can choose whether to limit the IP range of the account login, or set security alerts. That is, when the user logs in at an unconventional IP address, he or she is required to enter a security verification question or enter a mobile phone verification code, an email verification code etc..
5. When the ownership of the user account is lost and the private key is changed, the user can retrieve the lost account by answering the security verification question, mobile phone verification code, and Email verification.
6. When the user has forgotten the security verification question, he can also retrieve it by recalling the ability actions or digital credit actions participated in the past one month.
7. Theoretically, when the user logs in from a different IP, if he can't answer the security question correctly and fill in the correct mobile phone and Email verification code, the user cannot log in to his Digital Credit account.
8. The user can set a second verification when the transferred token is greater than a certain amount. (Security verification questions, mobile verification, email verification, etc.)

# View

## Client

Digital Credit will support multiple clients such as: web, PC, Mac, Linux, iOS, Android, etc. The client includes a primary client and a custom client. The main client is the client officially released by Digital Credit and runs the main program of Digital Credit. The hird-party client developed by the application developer can be found from application market in Digital Credit, or it can be an independent client.

### Main Client

The front-end of the web moderator client is generally written in a script language running on the server, such as: jsp, php, asp, asp.net, Node.js, and so on. Digital Credit allows application developers to write web front-ends using a variety of server-side scripting languages.

The Digital Credit main client for PC, Mac, and Linux will be developed by default using the Go language and communicate with the Digital Credit server via the service.

The main program of mobile phone client such as iOS and Android, Digital Credit will be written in Swift and Java language, and communicate with Digital Credit server through service.

### Third-Party Client

Application developers can develop third-party clients based on the framework provided by Digital Credit. For example, develop your own client but use the services of the Digital Credit server. Third-party clients need to be reviewed if they want to be registered the digital credit application market.

## Application Development

### Development Language

The Digital Credit application development language defaults to Javascript (Node.js) and Go, and will support Python and Java in the early releases.

### API

dMVC will provide complete Javascript, Go, Python and Java APIs to help developers easily develop decentralized digital credit applications.

### HTTP service

The Digital Credit platform allows developers to develop HTTP services for invocation.

### RPC

The Digital Credit platform will also support developers developing RPCs for remote calls.

### Cloud Service

Digital Credit allows developers to develop digital credit applications and services in the cloud and publish digital credit applications to the cloud provided by Digital Credit without having to build their own environment.

### Front-End Scripting Language

Digital Credit allows developers to develop digital credit applications through a variety of front-end scripting languages, including: jsp, asp, asp.net, php, Node.js, and more.

## Publish Apps/Services

### Registration of Application/Service

Digital Credit community members can apply for an App account and App Key. App accounts and App Keys can be used by application developers to call Digital Credit services. Some services and permissions may require that application developers have certain qualifications to apply. These qualifications may include: skills or ability requirements, credit requirements, etc.

The App account and App Key issued by the developer through Digital Credit can register digital credit applications or services based on Digital Credit. After the registration application/service is submitted, the application/service registration will only become available after approval of Digital Credit.

Applications/services that are registered and approved can be submitted to the application market of Digitial Credit.

### Application Market

Digital Credit's application market supports two application submission methods: one is cloud service approach, and the other is local service approach.

The cloud service approach: Application developers upload code online to the Digital Credit dMVC online development platform based on the dMVC design framework. After passing the test and verification, it can be used in Digital Credit. Developers of cloud services do not need to build any local environment or server and share the distributed servers of the Digital Credit community to implement data storage and call functions.

Local service approach: Application developers build an application development environment locally, and after submitting applications or services based on Digital Credit services and APIs locally, they submit a Digital Credit for review. After the submission is approved, their applications or services can be found in the Digital Credit App Market.

### Main Net

The main network is the officially applied network provided by Digital Credit. The main network establishes Digital Credit servers in a distributed manner. In Digital Credit 1.0, Digital Credit will use Tendermint and BigchainDB to build distributed, decentralized data storage servers. In the Digital Credit EOS.IO version, EOS.IO will be used to implement tokens and smart contracts; Digital Credit Ethereum will use Ethereum to implement tokens and smart contracts.

Digital Credit's community and cloud service applications will all run directly on the main network; local service applications will call Digital Credit's methods and data, and the application will run on the application developer's server.

### Nodes and Super Nodes

Digital Credit 1.0 will use Tendermint and BigchainDB for data storage and will use a minimum of 21 server nodes to run the Digital Credit service. Digital Credit will also welcome more nodes to enhance the security of the Digital Credit network. When the joining server node meets the requirements of the super node, that is, when the server performance and security meet certain requirements, the server node will be selected as a super node. For each node that runs a Digital Credit service, Digital Credit will give corresponding rewards based on the degree of contribution of the node. Super node owners will receive higher rewards than regular nodes.

### Test Net

The test network, Digital Credit will provide a test network environment. Application developers can freely test their digital credit applications on the test network. When the test environment of the application requires the use of other tokens, such as Bitcoin, ETH, etc., the corresponding token costs and fees are borne by the testers themselves.

### Private Net

The private network is built by third-party who uses the source code of Digital Credit for application development, and does not connect to the main network of Digital Credit and implements the Digital Credit function in its own environment. Because Digital Credit is open source software, as long as the third party complies with Digital Credit's GPL License(Please see [License](#license) section), Digital Credit will not restrict the use and modification of Digital Credit's source code by third parties, including setting up a private network.

# Business Application Scenarios and Areas

## Investment

In modern investment area, most investors are unprofessional, but it is very difficult for them to identify those professional investors and conduct “follow-up” because they have no way to effectively verify investment levels of other investors.

Digital Credit Solution: Investor’s investment ability can be verified in Digital Credit. Therefore, investment is no longer a difficult task, thus ordinary investors only need to follow up the “guru” for investment.

For example, holding a long-term, regular investment competition to evaluate performance of investors (assuming the use of simulation investing environment to assess the returns of participants), and regularly rank the participants’ investment performance (eg, weekly, monthly, quarterly etc.) Because the investing performance is automatically verified by the system, its investment performance and stability can be effectively verified by the system. In such investment system, it is easy for ordinary investors to find those who are professional at investment by their investment performance in competitions. Those professional investors can obtain greater returns by launching crowdfunding, lending, and selling tickets (sharing their own investment decisions).

## Financial Lending

In modern Internet lending applications, the real ability of lenders and the level of real income are often difficult to be verified, which will lead to risk.

The ability and credit of lenders are objective and real in Digital Credit. Therefore, the creditworthiness of lenders can be assessed most objectively and the appropriate loan amount can be given. Therefore, loans based on Digital Credit need neither mortgage nor guarantee. They can be issued only on the basis of the true ability and credit of the lender. When the lender defaults, the default will be recorded, even facing other penalties from Digital Credit, see the [Default or Fraud Treatment](#default-or-fraud-treatment) section. Therefore, financial lending in Digital Credit is relatively low risk and flexible.

## Crowdfunding, ICO

In current internet crowdfunding area, especially ICO, it has been criticized more severely. The main reason is the lack of verification of the authenticity of ICO fundraiser’s project and the lack of verification of ICO team’s ability and authenticity.

Crowdfunding and ICO in Digital Credit will have ability/skills requirement to fundraisers and their teams, and this capability needs to be verified by the Digital Credit system. (You must participate in the POA actions, and it is possible to obtain the ability evaluation through the ability rating, such as participating in the challenge, competition and test.)

Digital Credit has relatively strict requirements for ICO. One of them is that for ICO crowdfunding tokens, Digital Credit will not assign all tokens to the ICO initiator at one time, but will be distributed in stages according to the progress of the ICO initiator’s project. The pre-designated milestones of the ICO project will be reviewed. When the ICO project fails to achieve the milestone goal, or if there is a long-term lack of progress or project stagnation, subsequent token allocations will cease.

If a crowdfunding or ICO party has breached the contract or engaged in fraud, Digital Credit has corresponding penalty measures. See [Default or Fraud Treatment](#default-or-fraud-treatment) for details.

## Venture Capital, Start-Up Investment

In many cases, due to the lack of awareness of entrepreneurial and start-up investors about the true capabilities of the target, there will be investment errors or risks. Digital Credit can effectively verify the capabilities of its members. Therefore, investors who participate in entrepreneurial ventures and start-up investments do not have a lack of understanding of the ability of the target to be voted, and they also avoid many risks.

## Software and Project Outsourcing

In the field of software and project outsourcing, the project undertaker's capabilities are often unable to effectively test and may cause the project consigner to waste time and money. Digital Credit enables project commissioners to publish projects in the form of competitions, which can ensure that the project is the excellent selection, reduce risks and increase project success rate. At the same time, Digital Credit allows project delegates to effectively acquire participants’ abilities and skills in order to reduce risks and increase project success.

## Human Resources

In the field of human resources, such as talent recruitment, candidates often fictionalize or exaggerate their curriculum vitae and personal abilities. Preliminary interviews and short-term trial periods often fail to effectively test their true ability levels. When companies discover the ability of recruiters are not competent, it is often too late: corporate resources have been wasted, and there are many cases where companies can't recruit suitable people in key positions and delay corporate development.

Digital Credit allows talent recruiters to understand the real and proven ability of the recruiting target to effectively screen applicants and increase recruitment success.

## Other Business Areas

Other business areas such as arts, music, sports, advertising, marketing, corporate consulting, and planning can all benefit from Digital Credit's verifiable abilities and verifiable credit features.

# Non-Profit, Non-Commercial Application Scenarios

## Poverty Problem

The problem of poverty is a headache thorny issue for all countries. There are many root causes of poverty. One of them is that the poor people do not have better social opportunities. Poor families will certainly have possibilities to raise outstanding ability person. However, because their abilities cannot be identified due to their low social level and lack of social relations, it is difficult for them to be affirmed by the society and thus lose many job opportunities and credit opportunities.

Digital Credit can provide a fair and just platform. As long as you can prove your ability, then you have the opportunity to get a loan or even a real job opportunity. 

At the same time, the Digital Credit community will reward community members who are actively helping the poor to educate and elevate the skills of the poor, encouraging them to contribute to social issues through positive incentives.

## Social Equity Problem

The issue of social equity is also an issue that many countries cannot handle effectively. One of the root causes of the problem of social equity is that the bottom society does not have the social opportunities it deserves. For example, people from low-level families lack more social relationships than those from wealthy families, so their abilities cannot be effectively recognized and it is difficult for them to obtain equal social opportunities. 

In the Digital Credit community, they are completely equal. All opportunities and credit opportunities are based entirely on ability and credit and have nothing to do with other factors. Digital Credit will not judge the members of the community in addition to their ability and includes any factors other than their ability and credit. Therefore, Digital Credit is a fair community, and it can give the bottom society a chance to show their true talent and job and credit opportunities. 

## Corruption Problem

There are many root causes of corruption. One of the reason is the true capabilities of civil servants or social public servants have not been effectively verified. Using Digital Credit, anyone’s true ability can be effectively verified. For the government, hiring a competent public officer can reduce the corruption problem more than the incompetent public employee.

## Refugees, Illegal Immigration Problem

Problems of refugees and illegal immigration are very troublesome for countries. The key to the problem of refugees and illegal immigrants is that these people lack effective identities. Without identity, there is no credit and there is no educational opportunity. As a result, these people who lack identity often engage in illegal or criminal activities, or engage in gray jobs.

Through Digital Credit, these refugees or illegal immigrants can obtain loans through their ability and credit proofs, and have the opportunity to engage in legal work so as to maintain social stability.

## Other Public Welfare Issues

Other public welfare issues, such as environmental protection, charity, etc., can all benefit from the verifiable ability and verifiable credit features in Digital Credit.

# Conclusion

Digital Credit, by using blockchain technology, builds ability proof actions (challenge, competition, testing, teaching, posting, rankings, achievement, contribution, review, voting, etc.), digital credit action (awarding rewards, issuing loans, approving the crowdfunding and allowing sales of tickets, etc.), autonomous communities with positive incentives and negative incentives to create a decentralized, trustworthy, easy-to-use, immutable, autonomous, ability and credit verifiable digital credit community and application platform. Digital Credit community and application platform can be applied to multiple fields including business areas (investment, financial lending, crowdfunding, venture capital, software and project outsourcing, human resources, etc.) and public welfare fields (poverty problem, social equity problem, corruption problem, refugees and illegal immigration problem, etc., and can provide effective solutions to these areas.

# License

Without permission, anyone may use, reproduce or distribute any material in this white paper for non-commercial and educational use. (ie: other than for a fee or for commercial purposes) provided that the original source and the applicable copyright notice are cited.

Digital Credit is an open source project that complies with the [GPL License Version 3](https://en.wikipedia.org/wiki/GNU_General_Public_License) .
