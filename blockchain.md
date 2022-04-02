# Blockchain; 101

Buzzword of the century, probably.

## What is it?

> A blockchain is a peer-to-peer network, that uses cryptographic functions to create a distributed ledger of immutable or tamperproof transactions.

Done, see you next week 👋

Just kidding, a simpler explanation would be along the lines of:

> "a blockchain is a database made up of blocks of information, that's shared across a number of computers, who make that work together to make sure the data isn't messed with by making constant checks"

## Ok, so how does that happen?

1. The transaction is saved in a record.
2. The computers in the network look at the trade and make sure that it is a real trade or transaction. This is a decentralized process that occurs among the different nodes of the network called consensus.
3. As each transaction is verified and accepted as being real, it’s added to a block.
4. Each block contains a code called a hash that is unique to that block. The block carries two hashes, one is it's own has and the second is the hash from the previous block, that way we always know where the block should be located in the chain.
5. Once the block is complete it is added to the chain, the hash that it carries ensures that it is in proper chronological order.

If you have some kind of idea of what the blockchain is, then great. If you'd like to dig a little further, read below for a further breakdown with some analogies 👇

These can be broken down into 6 areas:

- Transaction/Blocks
- Digital Signature
- Distributed to network
- Verified / Consensus
- Blocks are chained together, showing the history of transactions in chronological order.

### Blocks

Explanation:
This is a bunch of transactions, checked & squashed into a block.

<pre>
Analogy; Christmas
  1. Each person getting a present = Transaction/Record.
  2. Each present wrapping their presents in their own wrapping paper (grandparents always use the same wrapping paper, every year 😅) = Block.
  3. Those wrapped presents are added to the Christmas tree = Blockchain.
</pre>

<pre>
 Analogy; Bank account
  1. Your bank statement = Blockchain.
  2. Receipt of all your shopping items = Block.
  3. Each item on that shopping receipt = Transaction/Record.
 </pre>

 <pre>
 Analogy; Raising money for a business.
  1. You have a business that is raising money.
  2. You recieve your first donations from 4 strangers 1️⃣, 2️⃣, 3️⃣ & 4️⃣.
  3. Those transactions are check by all nodes / computers.
  4. If verified to be true, those transactions are saved into a block 🔢.
  5. Another 4 people send money, so again, those transactions are checked and another block is created to fit those new transactions 🔢⛓🔢.
  6. Then the process repeats again 🔢⛓🔢⛓🔢 ... Can you see the block & chains ... blockchain forming?
</pre>

<pre>
 Analogy; Saving money for a holiday with friends
  1. We've all got friends who are the most responsible, in this example we'll name them Alice, Bob, Lucy & Alejandro. They're each responsible for collecting money for a different thing, let's say flights, hotel & activities.
  2. We each send our share of the money to them = Transaction/Record 1️⃣, 2️⃣, 3️⃣ & 4️⃣
  3. Once Alice has recieved collected the money for the flights she'll check and everyone has paid = Block 🔢
  4. Bob repeats = Block 🔢
  5. Lucy repeats = Block 🔢
  6. All that money is moved the the holiday account so we can go on a great holiday ☀ 🍹 = Blockchain 🔢⛓🔢⛓🔢
</pre>

### [Encryption](/encryption)

Explanation:
This is simply a way of scrambling a message (by using one or more mathematical techniques and algorythms) so strangers and people that you don't want to read it won't be able to understand it. The only way to make it readable again is by having the password or the key. There are a variety of encryption methods which we can cover in another section.

<pre>
Analogy; Passing notes at school
  1. Remember passing notes to friends during class in school?
  2. It would usually involve asking someone to pass on a message scribbled down on a piece of paper to your friend at the other end of the class.
  3. However it could be read by one of the students passing it on or worse, intercepted and read by the teacher.
  4. So usually kids would use funny ways of encrypting the message which could be either using slang, backwards alphabet or even writing in code.
  ... Below are a few examples:

![Elementary School Cipher](https://images.saymedia-content.com/.image/c_limit%2Ccs_srgb%2Cq_auto:eco%2Cw_1000/MTc2MjY5NzAwNDUwMjk3MDIy/codes-ciphers-cryptology-and-teasers.webp)

![Hieroglyphics/Codes](https://images.saymedia-content.com/.image/c_limit%2Ccs_srgb%2Cq_auto:eco%2Cw_1000/MTc2MjY5NzAwNDUwMjMxNDg2/codes-ciphers-cryptology-and-teasers.webp)
</pre>

### Distributed Systems

- A distributed system is a system that spread across smaller systems, meaning all of the power is not in one specific place, this means that it is much harder to hack / infiltrate these types of systems as you would have to take down all of the smaller systems and there could be many. This is sometimes confused with [decentralised systems](/decentralisation).
- Analogy ...

### [Consensus](/consensus)

Explanation:
Consensus is a way for a group to agree, specifically with blockchain we are referring to a group/network of computers agreeing that a transaction is correct.

<pre>
Analogy; Voting
  1. Each person votes (digitally or on paper), then submits their vote = Transaction/Record.
  2. All votes are counted, by several different groups = Consensus method.
  3. Groups who counted the votes, share results and agree the numbers are correct = Consensus reached.
</pre>

<pre>
Analogy; Wedding
  1. Two people are being married = Transaction/Record.
  2. The crowd are asked to speak if they do not agree = Consensus method.
  3. If everyone stays quiet and allows the wedding to continue a non-verbal agreement has been reached = Consensus reached.
</pre>

## How can it be used for?

- Storing confidential information.
  - Passwords
  - Writing
- Making sure information is not tampered with, changed or deleted.
  - Contracts
  - Receipts
  - Goverment or council spending.
  - Communication like emails, messages, videos or publications.

## Why is it important?

- Trustless

  - People & companies usually have their own motives that they don't share.
  - It can be difficult to trust strangers to keep their word, stick to an agreement or a contract.
  - So using [smart contracts](smart%20contracts.md) as an example which are contracts written in code, the code will execute as intended from start to finish allowing you to relax and not worry about the trust issue that comes with trading or transacting with friends, colleagues, strangers and companies, etc.
  - The code is there to see, although it can be tricky to read and understand, admittedly that is an area which needs to be improved (translating smart contracts into understandable contracts so individuals can read what they are signing in English as a pose to reading it in solidity).
    ... For example, the recent continuous hikes in energy costs are very striking as we are at the mercy of the energy companies, however if our contracts/agreements were in smart contracts they would not be able to continuously raise the prices of energy consumption as they currently are.
    ... Another example is with politicians, we all know one thing is certain, that they can't be trusted because as time has shown they promise the world and then as soon as they are voted in they change their policies, again with smart contracts there could be certain deadlines for each proposal they outline & perhaps when the success percentage drops below a certain number; let's say they fall behind target by 50%, the contract would automatically set off a re-election, that way we don't have to trust empty promises but instead trust the immutable agreements.

- Tranparancy

  - The ability for information to be public and / or truthful, so what we're being told by the news, seeing online and reading can be verified and checked with other open-sources, web3 holds this principle close which is why most of the projects are open-source allowing anyone to view and even contribute to their codebase & overall project.
  - ... For example, since politicians usually throw money at most problems, assuming they used a public blockchain, the public could easily follow the money and therefore track every single transaction they made as well as follow, which would help with the accountability across goverment spending and check if it is being used in the publics best interest.

- Freedom

  - The freedom to transact, communicate and learn without oversight is important for many reasons.
  - Freedom to education, some people are banned from certain literatures due to having authoritarian governments / leaders, for example in Cuba, North Korea and other countries reading anti-government or anti-state literature can be seen as illegal and can result in people being improsened or disapearing.
    ... For example, in Cuba there are so many black markets due to the restriction & censorship of books that the goverment see as dangerous, which is another way to say "we're scared of education & would like to keep the population ignorant"
  - Also communicating without feeling that someone would listen or sharing to your conversation is ideal, as this is a slipery slope to censorship.
    ... For example, even in developed countries, we all know that services like WhatsApp pick up keywords from your conversations and use those as targetted advertising, if you'd like to prove it, it's best to try an experiment by setting aside 1hr per day for a week, choose a random but very specific topic to discuss with a friend/partner such as "xyz" then check your advertisement results across instagram, facebook & even google _(Spoiler alert, you'll randomly get advertisements for products/services that provide "xyz")_.

- Privacy
  - We all deserve privacy to be our authentic self, especially in the modern age of social media where products / services are designed to make syour life as public as possible, cancel culture, selling of our data to marketing companies who in turn push products, services & agendas as well as political propoganda onto us via targetted advertising, and some employers snooping into your life outside of work.
    ... For example, cambridge analytica using targetted advertising to push political propaganda, fake news and fear to effect election results helping political parties across both UK, USA and many other countries.
