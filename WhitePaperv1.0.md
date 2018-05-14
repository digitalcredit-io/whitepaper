# Digital Credit White Paper v1.0

**May 13, 2018**

[Bruce Zhang](https://www.facebook.com/bruce.zhang.35762)

digitalcreditio@outlook.com

[digitalcredit.io](http://digitalcredit.io)


**Abstract:** Digital Credit is designed using a brand new blockchain architecture by creating a decentralized, verifiable digital credit community and application platform, based on challenge, competition, test, teaching, posting, ranking, achievement, contribution, review and voting, by implementing POA (Proof of Ability), digital credit evaluation and digital credit actions for members in the community to create a decentralized, trustworthy, easy to use, immutable, autonomous digital credit community and application platform. Digital Credit simplifies the blockchain application development and implements a distributed, decentralized MVC framework: dMVC (decentralized Model-View-Control), which includes: model part: data structure, database and data storage; control part : actions, services, account management, role and organization management, tags and categories; Proof of Ability Actions, including: challenge, competition, test, contribution, teaching, post, ranking, achievement, review, voting, etc. ; digital credit evaluations, digital credit actions (including awarding rewards, issuing loans, approving crowdfunding, allowing sales of tickets, etc.), tokens and smart contracts, and dispute resolutions; Views: Clients, etc. This allows the creation of distributed, decentralized, authentic, trustworthy, easy to develop, immutable, safe, objective, fair, autonomous, digital credit communities and applications based on POA.

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

**Note: In the early lauched version, dMVC may only support certain languages such as Java, Javascript, and Python.**

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

When bob no longer needs this post object, and he can't find another object to transfer, he can transfer the post object to the recycle bin: recycleBin, or transfer it to himself, but the mark post object has already been discarded.

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

**Note: When the type of stored data is a file, dOPA will store the file in the IPFS server rather than through BigchainDB.**

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

You can also limit the number of lookups:

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

Services are somewhat similar to the web service in Java, through the json to achieve data interaction between the client and server.

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

The maximum length of the account name of Digital Credit is 12 characters (Chinese character occupy 2 characters, if the account name is all Chinese, up to 6 Chinese characters are supported). 12 characters including English characters (a-z, A-Z), numbers (0-9), underscore (_), underscore (-), UTF-8 encoded characters of other countries (eg Simplified Chinese, Traditional Chinese, Japanese, Korean, etc.)

When creating an account, Digital Credit will detect the name of the account in order to avoid content such as verbal abuse, language intrusion, discrimination, verbal violence, and political infringement.

### Account Actions

The account can perform some account-related actions, such as open/hide account owner's digital credit information, competition results, skill information, and so on. The application of Digital Credit may require the account owner to open certain rights to run a digital credit application. For example, an online loan application requires the account owner to show the digital credit record for the application, or a software development competition application that requires the account owner to show information about the skill information and program development-related skills to the application; or An ICO, crowdfunding application requires crowdfunders to show information about the relevant skills they describe.

The account owner can choose to grant permissions to certain actions of certain applications or some other account (such as a friend).

### Friends, Whitelists, Blacklists, and Groups

The account owner can add other accounts as friends, or add to whitelist, blacklist, or a group. To perform certain actions in batches, such as setting up their own digital credit information that only friends are visible, or only certain applications are visible.

### Personal Account, Application Account, Action Account and Group Account

The account can represent individuals, ie. the personal accounts. The account can also represent the application, ie. the application account. The account can also represent a series of individual accounts or application accounts or a collection of action accounts or group accounts. For example, there are four personal accounts: @Bob, @Alice, @Tom, @Cathy, there is an application account: @DCLending and action account: @DCcompetition. Among them, @Bob and @Alice formed a company @CompanyA, then @CompanyA is the company account; @Tom and @Cathy formed a company @CompanyB. @CompanyA and @CompanyB and @DCLending belong to the parent company @CompanyC.

There is a correlation between personal accounts, application accounts, action accounts, and group accounts. For example, membership: @Bob and Alice are members of @CompanyA; contractual relationship: @Bob has a two-year work contract with @CompanyA; affiliation: @DCLending and @DCcompetition belong to @CompanyC, etc.

### Permission Management

Accounts can manage permissions for account actions. Account privileges can be assigned to a range of personal accounts, application accounts, or group accounts. Digital Credit manages account permissions by setting account weights and account action thresholds.

The following example is referenced in EOS.IO:

<img align="center" src="https://github.com/digitalcredit-io/whitepaper/blob/master/eos%20permission.jpg" />

In this example, the @multisig account has three account action permissions: owner, active, and publish. The account of the owner permission is @bob and @stacy. The weight value of each account is 1, and the threshold of owner permission is 2. This means that once you want to obtain the owner permission of the @multisig account, both @bob and @stacy are required to issue permissions. The active threshold is 1, and both @bob and @stacy have a weight of 1, which means that only one person, @bob or @stacy, is required to issue permission.

### Identity Verification

In Digital Credit, certain actions require participants to process identity verification. Identity verification mainly guarantees the authenticity of the participants' identities. Make sure the account holder does not create multiple trumpet for the same person and affects the fairness and objectivity of certain actions.

### Account Data

The naming convention for data access in the account is @+account name+(.+ account data fields, which can be multi-level nested).
Example: @bob.skills.English = B, indicating bob's English skill level is B.

The account owner can independently open/close status of his/her own account data, and can open certain account data for friends, groups, applications or actions. When an account uses an application or joins an activity, the application account or action account will require the account user or participant to grant permissions to certain data access privileges.

Account data permissions are: NA (unavailable), R (read only), RW (read and write), W (write only).

One example:
When @bob uses an application called competitionApp, the @competitionApp account requires @bob open permission:

@bob.skills.Java read and write

@bob.competition read and write

@bob.credit read and write

@bob.groups read

@bob can use the competitionApp after @bob has confirmed the @competitionApp access request. @bob will not be able to use the competitionApp if @bob disagrees with any one of the requests.

## Role and Organization Management

Each account can belong to an organization, such as @bob, @stacy and @alice belong to a team @teamA, where @bob is the Team Leader, so when you get @bob.role.teamA, the return value should be "Team Leader."

For an organization, you can define a lot of actions and permissions. For details, refer to the [Permission Management](#permission-management) section.

For example: @bob's role in @teamA is both the Team Leader and Reviewer, and @stacy is the Reviewer in TeamA. Then when @alice submits a proposal for review, it needs to be reviewed by both @bob and @stacy before it can be passed.

For the self-organizing management purpose, Digital Credit will establish a mechanism to encourage community members to actively participate in the community to contribute to get higher organizational roles. For example, when a member whose contribution reached a certain level and his/her related ability meets the standard, Digital Credit can automatically promote the member's role to Reviewer. Reviewer is more privileged than the regular member and can review the content posted by the regular member. (Like traditional BBS forum management, forum administrators can assign permissions to different sections, such as assigning moderators, etc.)

