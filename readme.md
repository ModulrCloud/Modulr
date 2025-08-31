# Welcome to Modulr!

We're thrilled to have you here! Modulr is building the next generation of decentralized cloud services, and we'd love for you to join us in shaping the future.

### 🛠️ **Developer Discussions & Community Support**

If you're a developer interested in contributing to Modulr, have questions, or simply want to join the discussion with like-minded enthusiasts, we invite you to connect with our community:

>**Discord**
>
  We will be releasing a discord so that developers can easily communicate and help with the project. Keep in mind that all contributions are rewarded. i.e. you can earn on network tokens. This will be automated in the future with Code Ledger.

---

# What is Modulr?

Modulr is a PoU (Proof of Utility) blockchain; that can best be thought of as a decentralized cloud service in which anyone can participate. There are three different utilities that can be performed on the network, that work together to create similar functionality as conventional cloud service providers.

1. **Computation** - The thought behind this function would be items that either are too complex for a ordinary machine to complete in a reasonable amount of time (training AI models, 3D rendering or DNA sequencing) or something that requires modifying data that must be shared with a group (think servers).

2. **Storage** - In order to compute you must have access to data to compute on. Modulr has storage built into it's language so you don't have to use another service. This allows for things such as databases and the ability to store large AI models. 

3. **Access** - This is a functionality that will be expanded more in the future, but for now think of this as the ability to have access to specialty equipment in a specific location such as linking two or more users together, surrogates or VPN like services. When fully realized it is meant to replace the IP protocol by enable secure communications that are digital signed from the source.

 When mixing these three utility types this will enable a full cloud experience that can do things such as spin up gaming servers, webpages and virtual computers. What makes this different than the way the internet is ran today is that anyone can participate and earn rewards for providing utility to the network. This reduces the need for massive data centers and spreads out computational resources throughout a geographic area. This will **NOT** eliminate centralized services, in fact there will be ways (via access) in which you can still direct to a centralized service. The goal of the network is to allow both the centralized and the decentralized systems to co-exist and allow the consumer to choose.

# Co-Chains

Co-Chains is how the network expands it's abilities and services. Anyone can create and own a co-chain, in fact there is a classification of user called **Creators** mentioned later. The Creator can set their fees thus earning based off the code they have written. Modulr natively does NOT allow the creation of tokens, but co-chains could add that functionality. The goal in doing this is to reduce the amount of tokens that go in circulation.

All of the base co-chains will start with `Modulr.` as that is our organization name on Modulr. This system not only brands our product but it also allow users to easily know who the owner is of this particular chain. This is encouraged for other developers, but not required as you can name your co-chain what you please.

## Why Co-Chains?

There are multiple reasons we call them co-chains rather than layer 2s:

1. Co-chains allows for better security since at each block completion a co-chain blends it's hash with a co-chain it's linked to, this reduces the risk of a attack on the network.

2. It expands Pseudo (Modulr's Pythonic programming language), by allowing others to import functions (services) from other chains. You can choose to private a function or set fees on it. Remember you own it...

3. It provides a sense of ownership for your work and allows you to monetize on it so you can continue to make it better and help you with your personal goals. You can also transfer ownership of a co-chain to another user or organization on the network.  

4. Personally it's better than saying layer 2; you're a creator on this network and providing value, you should be recognized for it.

## Understanding Co-Chains: Building Blocks of Modulr

Co-chains are specialized blockchain applications built on Modulr’s decentralized protocol. They enable developers to create targeted solutions, each tailored to specific use cases, while still integrating seamlessly with the broader ecosystem. To illustrate their potential, I am designing several foundational co-chains. These not only add value to the network but also serve as practical examples for developers aiming to build on Modulr.

### Why I’m Building These Co-Chains

As the creator of Modulr, my goal is to demonstrate how co-chains can unlock innovative solutions. By developing these foundational co-chains, I aim to:

1. **Showcase Efficient Data Management:**  
    Demonstrate how to use storage, computation and access, to interact with the network in a secure and efficient.
    
2. **Highlight Co-Chain Collaboration:**  
    Illustrate how co-chains can integrate and expand upon one another to create complex, interdependent systems (e.g., using Modulr.Web with Modulr.Social to integrate streaming video).
    
3. **Inspire Developer Creativity:**  
    Present co-chains that provide tangible value to users, showcasing how developers can design systems that drive engagement, adoption, and utility.
    
4. **Encourage Best Practices:**  
    Serve as a blueprint for building secure, scalable, and sustainable blockchain applications that align with user needs and network goals.
    

### A Platform for Innovation

These co-chains are not just standalone solutions; they are stepping stones for developers. By integrating and iterating on the concepts presented, developers can reduce duplication, enhance functionality, and focus on creating new value for the ecosystem. Whether it’s a decentralized streaming platform, a social media protocol, or a robust marketplace, the possibilities are endless when co-chains work together.

### Modulr.Core

Modulr.Core serves as the foundation of Modulr, coordinating critical protocols, utilities, and governance across the network. Its responsibilities include:

1. **Messaging and Communication**:
    
    - Establishes a base peer to peer messaging protocols to facilitate communication between all user types (validators, partners, creators and clients).
    - Introduces an **emergency messaging system** that allows Creators to broadcast critical updates and alert messages to all users on the network.
2. **Asset Management**:
    
    - Establishes token and credit system:
        - **MDR**: A tradable asset across the network and used to incentivize validators and users alike.
        - **MTR (Modulr Task Runner)**: A credit system that is used to perform services on the network and allows partners to decide how the value of the service they are providing. MTR Cannot be traded it must be used for services on the network.
3. **Alias System (UnaS)**:
    
    - Provides users with customizable usernames (e.g., `@username`) for simplified transactions and easier identification.
    - This system is case insensitive so users won't have to worry if any potion is capitalized or not.
4. **Chain Rules Framework**:
    
    - Sets the format for defining co-chain-specific rules, including:
        - Developer compensation.
        - Tokenomics structure.
        - Validator preferences.
5. **Interoperability and Subnet Management**:
    
    - Stores contact information for co-chains, ensuring seamless redirection to updated versions.
    - Maintains cross-network links for interoperability across multiple networks and subnets.
6. **Digital Asset Management**:
    
    - Enables **digital asset assignment**, allowing one or more users to co-own assets and share fees (e.g., between a songwriter and a musician).
    - Supports user groups to collectively manage assets.
    - Introduces **Open Transactions**, keeping asset transactions active for ongoing exchanges (e.g., tips or recurring contributions).
    - Implements **Standard Digital Asset Contracts**, a predefined system for defining asset rights and restrictions.
    - Introduces the **Digital Asset Protection (DAP) Protocol**, allowing assets to be protected and claims to be enforced both on and off-chain.
7. **Security Protocols**:
    
    - **Will Protocol**: Allows users to predefine where their digital assets should go if their account becomes inactive for a user-defined period.
    - **Freeze Protocol**: Locks an account to prevent any transactions if a breach is suspected, activating the Will Protocol if necessary.
    - **Limiter Protocol**: Sets transaction limits or delay timers for assets, minimizing losses during potential account compromise.
    - **Delay Protocol**: This allows users to place a brief delay on transactions that can be rejected by another by that same address. E.x. Private key is leaked and an attacker is attempting to drain funds, but user has the Modulr app on their phone notices the funds being sent and can block them. *Note: This delay doesn't affect the freeze protocol.*
8. **Licenses and Contracts**:
    
    - Provides a framework for creating:
        - Digital Asset Contracts (e.g., usage rights and restrictions).
        - Terms of Use for individual co-chains.
9. **Subscription Model**:
    
    - Implements a subscription system, enabling users to pay recurring fees for co-chain services with predefined expiration dates.
10. **Redemption System**:
    
    - Allows users to generate unique codes that others can redeem for assets, similar to prepaid or gift cards. Which is how MTR will be claimed. 
11. **Reliability Score**:
    
    - Tracks and evaluates user behavior to identify trustworthy participants and mitigate bad actors.
12. **Activity Metrics and Ratings**:
    
    - Maintains standardized metrics for co-chain activity and performance.
    - Implements a rating system for users to assess co-chains’ reliability.
13. **Convergence Protocol**:
    
    - Prevents blockchain size from becoming unmanageable by consolidating historical data into a new genesis block while preserving data integrity.
14. **Block Time and Synchronization**:
    
    - Establishes and maintains consistent block time across the network to ensure synchronization.
15. **Directory for all co-chains:**

	- Stores the validator addresses (contact information) for other co-chains so that if a user doesn't have that information stored in their system, they can request it.

---

> The following co-chains listed will simply have a summary as the scope of this document is to provide an idea of the capabilities of the core system. Each co-chain has it's own whitepaper which will be linked at the bottom if you wish to learn more. 

### Modulr.AI

Modulr.AI (formally Mimic) is Modulr’s dedicated AI co-chain, designed to revolutionize how artificial intelligence is deployed and used across decentralized networks. The Mimic co-chain focuses on creating **specialized AI models** tailored for specific tasks, ensuring efficiency, modularity, and adaptability. These models are connected to a **hypervisor system**, which intelligently routes incoming requests to the appropriate AI for seamless performance. Most important its used all throughout Modulr as a system for assisting user interaction as well as moderation. 

If you would like to learn more please see [Modulr.AI](cochains/AI.md)

---

### Modulr.Web

Modulr.Web (formally Pages) is Modulr’s decentralized Web system, offering a modern alternative to traditional web technologies. Replacing HTML and CSS with **M3L** (Multi-Media Markup Language) and **GSS** (Global Style Sheets), Modulr>Web provides a scalable, efficient, and privacy-centric experience for both creators and users.

If you would like to learn more please see [Modulr.Web](cochains/Web.md)

---

### Modulr.Robotics

Modulr.Robotics (formally LINK) is Modulr’s **standardized protocol for remote robotics**, designed to make piloting physical systems as seamless as accessing an app. Whether operating a humanoid surrogate, flying a drone, or steering an autonomous mower, LINK provides the ultra-responsive foundation for decentralized embodiment.

By creating a shared communication and control standard, LINK ensures secure, modular, and low-latency access to machines within a user's region, while enabling global coordination and oversight through AI-assisted supervision across Modulr subdomains.

If you would like to learn more please see [Modulr.Robotics](cochains/Robotics.md)

---

### Modulr.Store

Modulr.Store (formally Auction House) is Modulr’s decentralized marketplace for minting, trading, and protecting digital assets on the network. It uses **MDR** as the default transaction token. Users can seamlessly swap other digital assets such as robotics routines, AI models, co-chains themselves and yes monkey pictures.

If you would like to learn more please see [Modulr.Store](cochains/Store.md)

---

### Modulr.Code

Modulr.Code (formally Code ledger) is the heart of software development on Modulr, specifically designed for Pseudo. It combines decentralized collaboration, code verification, interactive education, and monetization into one seamless experience for developers. Code Ledger isn’t just a repository—it’s a **living ecosystem** that rewards innovation, encourages learning, and ensures secure development.

If you would like to learn more please see [Modulr.Code](cochains/Code.md)

---
### Modulr.Database

Modulr.Database (formally SQeeL) is Modulr’s decentralized SQL database system, designed to create and manage on-chain databases with seamless scalability, robust user features, and enhanced developer tools. Built to balance power and usability, SQeeL transforms decentralized database management into a streamlined, interactive experience.

If you would like to learn more please see [Modulr.Database](cochains/Database.md)

---

### Modulr.Social

Modulr.Social (formally SMACK) redefines decentralized messaging and social interaction, offering a robust protocol for communication, community building, and content ownership. Smack is not a social media system but rather a **protocol** that enables platforms and creators to build decentralized applications and networks tailored to their needs.

If you would like to learn more please see [Modulr.Social](cochains/Social.md)

---

### Modulr.Gaming

Modulr.Gaming (formally Player2) is Modulr’s innovative co-chain designed to revolutionize gaming through decentralized technology, immersive storytelling, and cutting-edge tools for developers and players. From multiplayer experiences to single-player narratives, Player2 empowers creators to build the next generation of games while offering players unparalleled ownership and interactivity.

At the core of Player2 is the **Echoes Trilogy**, a showcase of Player2’s capabilities that spans generations and genres. This episodic RPG series invites players to explore rich worlds, confront legendary adversaries, and shape the fate of interconnected stories across time and space.

If you would like to learn more please see [Modulr.Gaming](cochains/Gaming.md)

---

### Summary on Co-Chains

As you can see, Modulr offers an expansive framework for developing diverse co-chains, each contributing unique functionality to the ecosystem. While I may not be able to personally develop every co-chain idea presented here, my goal is to create a strong foundation that inspires innovation and ensures the protocol can adapt to the varied needs of these co-chains.

Through firsthand experience in building these systems, I’ve learned that actively using a product uncovers insights that might otherwise be missed. My hope is that developers approach their creations with a focus on delivering tangible value—not just another asset class—to enhance the ecosystem as a whole.

#### Potential Co-Chain Ideas

To spark inspiration for future development, here are a few ideas for co-chains that I believe could thrive on Modulr:

1. **Decentralized Rideshare and Delivery Services**  
    Imagine a decentralized version of Uber or DoorDash, enabling peer-to-peer ride sharing and delivery services without centralized control. Such a system could bring fairer pricing, more equitable profit distribution, and enhanced user control.
    
2. **Decentralized Marketplace**  
    A decentralized Amazon-like co-chain could link small, independent shops into a unified network. This would empower local businesses to compete with larger corporations while offering consumers diverse options from around the world.
    
3. **Decentralized Science (DeSci)**  
    A co-chain designed for scientific collaboration could connect users to a network of scientific equipment. From weather stations and geomagnetic sensors to RF analyzers and telescopes, this system could create a global monitoring network for advancing research and discovery.

4. **Decentralized Learning Platforms**  
    A co-chain dedicated to education, offering decentralized courses, certifications, and knowledge sharing. Instructors can host live classes, sell pre-recorded lessons, or even provide one-on-one tutoring sessions. This co-chain could integrate Mimic to act as a personalized tutor, guiding students through material and answering their questions.
    
5. **Crowdfunding and DAO Co-Chains**  
    A co-chain designed for fundraising via decentralized autonomous organizations (DAOs). Projects can raise funds through transparent smart contracts, while contributors have voting power to decide the project’s direction. This system could include milestone-based funding, ensuring accountability for developers.
    
6. **Digital Healthcare Services**  
    A decentralized Tela-Health co-chain where patients can securely connect with healthcare providers for consultations, prescriptions, and medical advice. Health data could be stored privately on the network, and Mimic could assist with diagnostics or routine health inquiries.
    
7. **Decentralized Talent Marketplaces**  
    A co-chain where freelancers and businesses connect without intermediaries. Users can showcase their skills, bid on projects, and receive payments through Modulr’s token systems. Built-in reputation systems ensure fair and trustworthy transactions.
    
8. **Event Ticketing and Management**  
    A co-chain for creating, selling, and managing event tickets. Tickets would be issued as digital assets, ensuring authenticity and preventing fraud. Event organizers could even create virtual venues using Live and Player2 for decentralized concerts or esports events.
    
9. **Decentralized Energy Sharing**  
    A co-chain allowing users to buy, sell, or share surplus energy locally. Homeowners with solar panels, for instance, could sell excess electricity to their neighbors in real time, creating a decentralized energy market.
    
10. **Legal and Compliance Services**  
    A co-chain offering tools for creating, sharing, and enforcing digital contracts and agreements. It could feature a library of pre-built templates for licenses, NDAs, and other legal documents, with built-in dispute resolution protocols.
    
11. **Decentralized Travel Booking**  
    A co-chain that connects users with travel providers, allowing them to book flights, hotels, and tours directly. This system would remove intermediaries, reducing costs and providing a more transparent booking experience.
    
12. **Supply Chain Management**  
    A CRM (Customer Resource Management) system that allows users to track and monitor manufactured goods over an entire organization. This system could provide manufacturing instructions, estimate material usage and plan accordingly and provide real time tracking that could be provided to customers. 

13. **Decentralized Music and Video Streaming Services**  
	This co-chain enables creators and platforms to host music and video content in a decentralized ecosystem. By integrating features from **Live**, it facilitates seamless content streaming with robust scalability and low latency. The use of **rental digital asset contracts** allows content providers to define specific usage rights, such as viewing-only or limited-time access, ensuring creators maintain control over their work while providing users with a seamless experience.

	This co-chain paves the way for decentralized streaming platforms—think of it as a blockchain-powered alternative to services like Netflix or Spotify—where content ownership, control, and monetization are shifted back to the creators and their audiences. Additionally, creators can use the built-in functionality of Pages to host their libraries and leverage AdCoin for monetization options.

## Co-Chain choice (Open vs. Closed Source)

While I firmly believe in the principles of open-source development, Modulr also provides the flexibility to run closed-source code. This capability is achieved through **Preferred Partners**, systems that execute Creator code directly without requiring compilation by the Code Ledger co-chain. However, implementing closed-source systems introduces challenges, particularly regarding security and transparency, as public scrutiny of the code is limited.

This approach may seem to contrast with the ideals of decentralization, but Modulr is designed to go beyond rigid definitions. By blending the strengths of both decentralized and centralized systems, Modulr ensures developers have the freedom to use the tools that best meet the unique requirements of their applications. Whether it’s full transparency through open-source projects or the tailored control of closed-source solutions, Modulr is built for the future—empowering developers to innovate without compromise.

---

# User Types in Modulr

Modulr features four distinct user types, each designed to balance power and ensure no single entity can compromise the integrity of the chain. Here's how they function:

1. **Creators**  
    Creators are the architects of a co-chain. They define its functionality, tokenomics (fees), and governance rules. Upon launching a chain, owners receive a digital asset certifying their ownership, which can be transferred or shared with up to two additional partners. Owners also select **preferred validators** (often themselves) and determine the number of validators on their network, with a minimum of three.  
    *Concerns about centralization? Don't worry; safeguards are in place.*
    
2. **Validators**  
    Validators act as the backbone of the network, akin to routers. Their responsibilities include:
    
    - Connecting clients with partners to fulfill requests.
    - Validating and recording transactions, ensuring data integrity.
    - Maintaining the **Username Database**, a secure directory mapping usernames to public keys.  
        Validators play a crucial role in keeping the network functional, secure, and efficient.
3. **Partners**  
    Partners are Modulr’s equivalent of miners, but instead of solving cryptographic puzzles, they perform meaningful tasks in three utility categories: computation, storage, and access.
    
    - Partners collaborate with validators by fulfilling jobs listed in the **Jobs File**.
    - After completing a task, they sign a receipt with the client, ensuring transparency and accountability.  
        Partners are essential for driving the decentralized cloud services that Modulr provides.
4. **Clients**  
    Clients are the end-users of Modulr’s resources, engaging with services for entertainment, productivity, or business. They’re not merely consumers but an integral part of the chain's security.
    
    - Clients sign receipts upon completing transactions, ensuring trust and verifying job fulfillment.
    - By participating in this process, clients help secure the network while benefiting from its decentralized services.

---

# Block Generation

Blocks on Modulr are generated using a fixed block time rather than size to ensure consistent and predictable operation. This design choice mitigates the risk of rapid chain expansion by offloading completed items such as job files, work files, and payout lists to partners for storage. Additionally, a process called **The Convergence** consolidates the chain to optimize storage and performance; this is explained further in the encryption standards section. Each block is generated in three distinct stages, with each stage consisting of three steps.

The timing of block generation will initially be experimental. Blocks need to be long enough to accommodate a sufficient number of job requests while maintaining responsiveness for users. The current target is **60 seconds per block**. While blocks finalize at this interval, transaction propagation is near-instantaneous, providing users with a fast and seamless experience.

### **Transaction Throughput and Responsiveness**

Modulr decouples transaction placement from block finalization. Transactions are processed and placed in the **job file** almost immediately after being initiated, allowing clients and partners to proceed without waiting for block finalization.

This approach ensures:

1. **High Transaction Throughput (TPS):** The network can process a significant number of transactions per second by leveraging real-time job file updates.
2. **Responsive User Experience:** Transactions are swiftly propagated to validators, enabling rapid initiation of utility tasks.
3. **Scalability:** Validators and partners dynamically distribute workloads to maintain system responsiveness even under high demand.

---

### **Stage 1 - Initialize**

1. **Request:** A client submits a service request to the validators. Validators record this request in a job file, enabling partners to identify and fulfill the required utility.
2. **Link:** Partners signal their availability to the validators, indicating they can perform the requested utility. This step helps maintain a steady flow of tasks to eligible partners.
3. **Sync Jobs:** Validators synchronize the job file for the current block with other validators to ensure consistency across the chain.

### **Stage 2 - Link**

1. **Search:** Validators actively monitor for available partners to fulfill job requests or directly contact known partners for specific tasks.
2. **Partner(s) Found:** Upon receiving sufficient responses, validators establish a connection between the client and selected partners. Proxies may be employed to safeguard against potential DDoS attacks.
3. **Connection Established:** The connection details and corresponding block number are recorded in the **work file**. Validators also listen for relevant hashes from interconnected co-chains.

### **Stage 3 - Utility Complete**

Utility tasks are not required to conclude within a single block and may span multiple blocks. Completion occurs either when the client or partner terminates the transmission or at predefined payout intervals (e.g., every 4 hours on the main chain).

1. **Receipt:** Both the client and partner must submit a receipt of the utility. This receipt, signed by both parties, serves as verification of the transaction. Submissions from both parties are recommended to ensure redundancy.
2. **Utility Complete:** Validators mark the utility task as complete, recording the completion block and appending the transaction receipt. _Note: Receipts must remain under 128 characters to optimize storage, though they may link to larger off-chain files._
3. **Payout:** At the Creator’s defined intervals, payouts are processed. Transactions not included in the current payout are appended to the **pay sheet** for inclusion in the next interval. Validators hash the payout data and append it to the block, sharing the hash with interconnected co-chains.
4. **Subscription Model**: MDR will introduce the subscription style model system. If users choose they can subscribe to Modulr's services for a flat rate which allows near infinite requests. *There is an anti-spam system*

---

### **Note on Adjustments**

Block timing and related parameters may be adjusted based on real-world data to ensure optimal transaction throughput and storage efficiency. This iterative approach ensures Modulr remains both responsive and sustainable as the network grows.

---

## Tokenomics

Modulr employs **MDR** to incentivize validators and partners. Partners do not directly earn MDR from the network however, that is only done via the validators. Rather the partners set their price for services on the network and that fee for the service is paid to the partner. This fee system is done via the **MTR** credit system which is an asset that can only be used for services on the network. More on this later.

*Note: The blockchain experienced a soft launch on April 24, 2024. All token emissions from this date until the network officially launches are effectively burned and will not enter circulation.*

---

### Modulr Token (MDR)

MDR is the backbone token of the Modulr network and the primary reward mechanism for validators. It follows a deflationary model inspired by Bitcoin, introducing scheduled reductions in daily emissions — referred to as **halvings** — to promote long-term sustainability while ensuring validator incentives remain intact.

#### Key Features

1. **Initial Allocation:** 4,000,000 MDR minted at launch. Of this supply, **1,000,000 MDR exists on Ethereum as eMDR**, while **3,000,000 MDR remains on the native Modulr chain**.
    
2. **Cross-Chain Bridge:** MDR will be transferred between the Modulr chain and Ethereum through a **slot-based bridge mechanism**:
    
    - When a user sends MDR from Modulr to Ethereum, it is locked into a **slot** on the Modulr side, and an equivalent amount of eMDR is released from a bridge wallet on Ethereum.
    - When a user sends eMDR back to Modulr, it is locked on Ethereum, which **opens a slot** on Modulr and releases the native MDR.
    - This design ensures the circulating supply remains balanced across ecosystems.
    - _(Note: The current v1 contract introduces a controlled bottleneck to maintain stability. A v2 contract is planned to optimize throughput and reduce friction.)_
        
3. **Daily Emission:** Begins at **4092 MDR per day** and reduces every four years through halvings until stabilizing at **1 MDR per day** indefinitely. *(Emission values follow binary division, aligning with 2ⁿ reductions.)*
    
4. **Dual Access Model:**
    
    - **Subscription:** Users can pay MDR to unlock flat-rate access with capped transactions per minute.
    - **PAYG (Pay-as-you-go):** Users can pay per transaction, consuming MDR as needed.
        
5. **Perpetual Incentive Model:** By never reducing emissions to zero, Modulr ensures validator rewards persist indefinitely, while scarcity still increases over time.
    

---

#### Halving Schedule

|Halving|Year|Tokens Per Day|
|---|---|---|
|1|1|4,092|
|2|4|2,048|
|3|8|1,024|
|4|12|512|
|5|16|256|
|6|20|128|
|7|24|64|
|8|28|32|
|9|32|16|
|10|36|8|
|11|40|4|
|12|44|2|
|13+|48+|1|

---

#### Why MDR is Different

Unlike traditional cryptocurrencies that force every user into volatile per-transaction fees, MDR introduces a **subscription + PAYG hybrid model**. This gives users the freedom to choose a plan that fits their needs, while giving Modulr a sustainable revenue stream that mirrors familiar Web2 services.

Additionally, MDR’s **slot-based bridge system** ensures that liquidity between Ethereum and Modulr remains tightly controlled, reducing risks of oversupply, arbitrage abuse, or bridge exploits. This approach creates a unique blend of **cross-chain flexibility with supply discipline**, paving the way for safe interoperability.

---

### Modulr Task Runner (MTR)

MTR (Modulr Task Runner) is the closed-loop credit system that powers services across the Modulr ecosystem. Unlike speculative tokens, MTR cannot be traded, redeemed, or withdrawn — it can **only** be used for on-network services such as storage, computation, or access to robotics.

This design avoids regulatory pitfalls like AML concerns while keeping Modulr simple, transparent, and consumer-friendly.

#### Key Features

1. **Service-Only Utility**
    
    - MTR credits cannot be redeemed for cash or transferred outside the network.
    - Prevents speculation and ensures compliance with financial regulations.
        
2. **Familiar Access**
    
    - Acquired via prepaid cards, digital vouchers, fiat payments, or crypto via MDR or eMDR (Ethereum wrapped MDR).
    - Users who pay with MDR or eMDR receive **bonus allocations** of MTR.
    - Services are priced transparently in the user’s native currency, so costs always feel real-world grounded.
        
3. **Fair Market Pricing for Partners**
    
    - Partners set their own service costs either per GB, per CPU cycle, per hour of service (such as robotics access).
    - If prices are too high, users can choose competitors, creating a true digital economy.
        

---

#### How MTR Flows Through the System

1. **Consumption**:
    
    - A user spends MTR to request a service (e.g., robotics access at $10/hour).
    - Their credits are deducted immediately on the network.
        
2. **Payout File**:
    
    - All consumed MTR is recorded in a **payout file**, which is paid out every **4 hours**.
        
3. **Conversion**:
    
    - At payout, MTR is automatically converted into MDR by purchasing MDR at the current market rate.
    - The MDR is then sent directly to the partner, providing fast, liquid payments.
        
4. **Fiat Option (Optional)**:
    
    - Partners who prefer fiat can opt in to monthly payouts which is subject to a $100 minimum prior to payout.
    - This service is slower and costlier, but enables institutions or regulated entities to participate without handling crypto directly.
        

---

#### Why MTR Matters

- **For Users**: A simple, prepaid credit system that feels natural (like Steam or phone cards) while staying transparent with fiat-equivalent pricing.
- **For Partners**: Fast payouts in MDR with the option for fiat if needed. True market-driven pricing ensures fair competition without rigid, enforced blockchain fees.
- **For Regulators**: A closed-loop system that avoids redemption or speculation, framing Modulr as a **service-first platform**, not a financial product.

---

## Token Guidelines

- **Decimal Precision:** All tokens and credits are divisible up to **12 decimal places** for precision, using metric prefixes (e.g., milli, micro, nano). For instance, **100µ MDR** represents **0.0001 MDR**.
- **Cross-Chain Token Sharing:** MDR is distributed across co-chains based on transaction volume, ensuring equitable rewards for validators.
- **Burn Address:** A dedicated burn address, reserved as `@Burn`, is built into the protocol to enable irreversible token destruction.

---

### Fees

Modulr’s fee system reflects its core principles of digital ownership and fairness:

1. **Partner-Set Fees:** Partners can independently set fees for services, with a portion allocated to the Creator. Validators cannot set fees.
2. **Chain-Set Fee:** This fee is what is set by the co-chain you are utilizing and is simply added to the price that the user sees when they select a service to avoid hidden fees.
3. **Network Suggested Fee:** Partners can opt for a network-suggested fee based on what the Modulr protocol recommends.
4. **Auto-Fee System:** Dynamically adjusts fees based on token value and network activity.
5. **Fee Reduction Voting:** Users and partners can vote to reduce fees temporarily if token values become overinflated.
6. **No-Fee Model:** Partners and co-chains can opt to charge no fees, though this forfeits emission-based rewards. This supports non-profit initiatives.

---

## Digital Assets on Modulr

In the era of decentralized networks, **digital assets** are the backbone of user engagement, creativity, and commerce. Unlike traditional NFTs, which merely record ownership, Modulr’s assets are designed to bring enforceable rights, clear usage terms, and choices for creators and users alike. This section provides an overview of the contract types, enforcement mechanisms, and protections that make Modulr’s digital assets uniquely valuable.

#### Predefined Digital Asset Contracts

Each digital asset on Modulr is governed by a **predefined contract** that determines how it can be used, shared, and monetized. These contracts are color-coded for easy recognition, ensuring transparency for creators and users at all levels. Here’s a summary of the five contract types:

1. **⚪ Unregistered (Gray)**: Basic NFT-like ownership recorded on-chain without enforceable rights or protections.
    
    - **Details**: Unregistered assets simply establish ownership on the network but lack any claims or IP protections. If the owner chooses, they may upgrade an unregistered asset to a registered type with full protections later; however, the protections only apply from the reclassification date onward.
    - **Example**: An artwork uploaded without protections can later be upgraded to ensure royalties on resale, but initial transactions remain unaffected.
2. **🟢 Rental (Green)**: Limited, single-use access for temporary asset consumption.
    
    - **Example**: Renting an e-book, video, or course with limited access rights.
    - **Key Benefits**: Provides short-term access without resale rights, allowing creators to retain full control over the asset’s use.
3. **🔵 Single Use + Content Sharing (Blue)**: Unlimited personal use with limited sharing rights for reactions, commentary, and resale with royalties back to the creator.
    
    - **Example**: Purchasing a video to enjoy personally, resell with royalties to the creator, or share in a reaction or commentary format (e.g., YouTube reactions).
    - **Key Benefits**: Supports creative engagement through limited sharing while maintaining control and royalties for the creator.
4. **🟣 Ownership (Purple)**: Full ownership, granting users the right to share or resell the asset as-is without modifications.
    
    - **Example**: Buying a collectible or media asset to keep, share, or resell without altering.
    - **Key Benefits**: Grants users greater control over the asset while preserving the creator’s original work and intention.
5. **🟡 Full Use (Gold)**: Complete ownership with the freedom to modify, remix, resell, and use without restriction.
    
    - **Example**: Licensing music or an artwork to incorporate into new projects, remix, or resell with modifications.
    - **Key Benefits**: Highest level of creative freedom, ideal for assets meant for open use, allowing users to fully repurpose the asset as if they created it.

These predefined contracts address the limitations of traditional digital assets, giving both creators and users well-defined rights and responsibilities.

#### Enforcement Through Digital Asset Guardians (DAGs)

Modulr’s **Digital Asset Guardians (DAGs)** are independent entities responsible for enforcing the network’s Digital Asset Program. By bridging decentralized principles with real-world compliance, DAGs ensure that asset contracts are meaningful and actionable.

#### Key Roles of DAGs:

1. **Asset Validation:** DAGs verify that digital assets comply with Modulr's standards and terms. This includes monitoring for unauthorized use or duplication of existing works.
2. **Dispute Resolution:** DAGs mediate disputes between creators and claimants, providing a fair and balanced resolution mechanism.
3. **Revenue Distribution:** For assets with multiple contributors or shared ownership, DAGs oversee revenue splits to ensure fair compensation.

#### Mimic’s Role in Enforcement:

- **Duplicate Detection:** Mimic analyzes digital assets for potential duplicates, flagging works that may infringe on existing copyrights.
- **Consumer Warnings:** If a duplicate is detected, Mimic provides a warning visible to potential buyers, along with the creator's response.
- **Neutral Role:** Mimic does not block minting but empowers consumers with transparent information, enabling informed decisions.

#### Consumer Protections:

- **Transparency:** Buyers can see warnings and creator responses directly on the asset's listing.
- **Accountability:** Creators minting flagged works must provide an explanation, fostering trust and reducing misuse.

#### Why DAGs Are Essential

Without an enforcement mechanism, digital asset contracts are meaningless. DAGs bring legitimacy to Modulr’s asset system by offering active protections and reliable dispute resolution. By combining DAG oversight with Mimic’s AI-driven insights, Modulr ensures a balanced ecosystem that empowers creators and protects consumers.

### Claim Filing and Dispute Resolution

To ensure transparency and fairness, Modulr incorporates a decentralized process for filing and resolving claims regarding digital assets. This system operates independently through DAGs and is supported by the protocol's foundational tools.

#### Filing a Claim:

1. **Initiating a Claim:**  
    Creators or rights holders can file a claim via a DAG. To initiate, they must:
    
    - Provide evidence supporting their ownership or IP rights (e.g., copyright documentation, timestamps, or original work).
    - Pay a **claim fee** (determined by the DAG and dependent on their Reliability score) to discourage frivolous claims.
2. **Sponsor Involvement:**  
    Claimants select a **sponsor**, an independent DAG member or organization, to vouch for their claim’s validity. Sponsors validate the provided evidence and enhance the credibility of the claim.
    
3. **Notifying the Asset Owner:**  
    Upon filing, the current asset owner is notified and given a set period (e.g., 7-14 days) to respond. The asset in question may be temporarily frozen to prevent transfers or modifications during the dispute.
    

#### Responding to a Claim:

1. **Providing Evidence:**  
    The accused owner can contest the claim by presenting their own evidence, such as proofs of prior creation or purchase.
    
2. **Counter-Claim Filing:**  
    If the accused believes the claim is false or malicious, they can file a **counter-claim**, which also requires a fee based on their Reliability score.
    
3. **Resolution through DAGs:**  
    DAGs mediate the process by reviewing evidence, consulting sponsors, and reaching a verdict. All findings and outcomes are transparently logged on-chain.
    

#### Resolution and Outcomes:

1. **Valid Claim:**  
    If the claim is deemed valid:
    
    - The asset is transferred to the rightful owner.
    - The claim fee is returned to the claimant.
    - The original owner may face a **Reliability score penalty** for knowingly or unknowingly minting an infringing asset.
2. **Invalid Claim:**  
    If the claim is rejected:
    
    - The claim fee is awarded to the accused owner as compensation.
    - The claimant’s Reliability score is penalized to discourage baseless claims.
3. **Legal Escalation:**  
    In cases involving significant legal implications, DAGs may require both parties to identify themselves and comply with jurisdictional laws.
    

#### Mimic’s Role in Disputes:

Mimic aids both parties during the claim process:

- **Claimant Support:** Mimic assists in gathering evidence and preparing documentation for the claim.
- **Owner Support:** Mimic helps owners compile counter-evidence and verify timestamps or metadata.
- **Transparency Tools:** Mimic provides clear, accessible overviews of claim details and outcomes for all stakeholders.

---

#### Protocol Forks for Ownership and Representation

Modulr’s protocol remains neutral, avoiding mandatory enforcement to reduce network burden. Instead, **protocol forks** enable flexibility and creator-defined enforcement:

- **Ownership Fork:** Sets the asset’s primary owner, governs revenue distribution, and can initiate actions like asset freezes in case of disputes.
- **Representation Fork:** Allows creators to assign an **enforcement mechanism** (such as DAGs) for handling claims, enforcing rights, and managing disputes if needed.

These forks create the foundation for a decentralized enforcement system, giving creators full control over their level of protection without altering the core protocol.

#### Built-in User Protections and Decentralized Dispute Resolution

Modulr’s digital asset model includes comprehensive user protections to create a balanced environment:

- **Transparency with Color-Coded Contracts:** Clear asset terms prevent misunderstandings and allow users to make informed decisions.
- **Accountability in Dispute Resolution:** Both claimants and users are accountable in disputes, with sponsors providing support and verification to prevent misuse.
- **Modular, Decentralized Enforcement:** Optional DAGs and protocol forks allow enforcement and monitoring to evolve without impacting the core protocol, promoting innovation within the Modulr ecosystem.

#### Advantages of Enforceable Digital Assets on Modulr

The Modulr digital asset model brings unique advantages over traditional NFTs and decentralized assets:

- **Clear Rights and Responsibilities:** Predefined contracts outline specific usage rights, empowering creators and users to understand and control asset interactions.
- **Optional, Effective Enforcement:** By choosing DAGs, creators can access a robust IP protection system that operates independently of the main protocol.
- **Upgrade Flexibility for Unregistered Assets:** Unregistered (Gray) assets offer a straightforward entry point, with the flexibility to upgrade protections as desired.
- **Future-Proof Flexibility:** The enforcement system, combined with protocol forks, allows the ecosystem to grow, adapt, and incorporate new enforcement mechanisms without requiring protocol changes.

Through enforceable digital assets, Modulr enables a **new standard in digital ownership** for Web4, balancing creator rights with user freedom while remaining scalable and neutral at its core.

---

## Network Fundamentals

### Accounts

Anyone can generate an account on Modulr just as they can with any other blockchain, by generating a public/private key pair. Once you have generated your keys, simply send in a new user request message. Usernames, which begin with an @ symbol (e.g., @Undline), provide an easy means of transferring digital assets using a name instead of a long public key. These names are resolved on the validators' end using UnaS (Modulr Naming System), which acts like DNS.

While usernames are not a requirement, public keys are necessary for adding you to the public ledger and allowing other users to reach you. This ensures that even new users without tokens can still participate and interact on the network. Users can receive tokens through drops or earn them by actively participating in the network.

If you choose to register a username, we implement a staking system to ensure they are genuinely used and to prevent malicious actors from squatting on common names. Users are required to stake a set amount, equivalent to **44 USP**. If the user remains active on the network (using chains, sending digital assets, or creating content consumed by other users), they will receive the stake back. The account will be reviewed 30 days after generation to determine if it qualifies for the refund. If the user fails to meet the activity requirements, the period will be extended by another 30 days. If after 90 days, the user still doesn't meet the requirement the stake is lost.

Although this approach necessitates a stake for securing a unique name, it effectively prevents gaming the system while maintaining user anonymity within the base protocol. Note that account names are non-transferable due to security concerns, ensuring that each username is tied to its original account.

Accounts are refundable after demonstrating active participation in the network, and usernames should be considered a critical part of the security infrastructure, especially when we need to switch encryption protocols in the future. If you cannot come up with a name, one can be autogenerated for you. Users should choose a username for enhanced security, as it allows us to modulate our encryption schemes more effectively.

#### Key Points:

1. **User Request:** Generate a public/private key pair and send a new user request message to create an account.
2. **Public Key Requirement:** Public keys are necessary for adding you to the public ledger and for other users to reach you.
3. **Username Registration (Optional):** Register a username with a refundable stake, reviewed after 30 days of network activity.
4. **Non-transferable Usernames:** Usernames cannot be transferred to ensure security.
5. **Autogenerated Names:** If needed, usernames can be autogenerated.
6. **Enhanced Security:** Users should choose a username for better security and encryption modulation.
7. **Token Acquisition:** New users can receive tokens through drops or earn them by participating in the network.

### Organizations

#### 1. Purpose & Identity

Organizations are a **foundational user type in Modulr**, designed to extend the power of the network from individuals to groups. While Clients, Creators, Partners, and Validators define how individuals interact with the network, **Organizations define how groups collaborate, govern, and operate collectively**.

At their core, organizations provide:

- **Shared Identity:** Each organization is represented by a `%` prefix (e.g., `%Modulr`) and exists as a distinct on-chain entity, separate from the personal accounts of its members. This identity can own assets, enter contracts, and interact with other users and organizations across the network.
- **Collective Workspace:** Organizations act as decentralized equivalents of modern productivity suites like Google Workspace, but with direct access to Modulr’s entire service stack (compute, storage, access, robotics, AI, marketplaces). Members can share resources, coordinate projects, and manage assets without relying on external intermediaries.
- **Governance & Hierarchy:** Organizations are built for structured decision-making. They include role-based hierarchies, voting systems, and multi-signature safeguards to ensure that no single individual can compromise group operations.
- **Public Accountability:** Unlike closed Web2 platforms, organizations in Modulr are inherently **transparent and auditable**. Their actions, governance, and financial flows are recorded on-chain, ensuring both accountability and trust.

By introducing organizations as a first-class feature of the protocol, Modulr makes it simple for teams, businesses, DAOs, and communities to **establish a digital presence, pool resources, and operate with collective authority** all while being secured and enforced by the network itself.

---

#### 2. Minting & Pricing

Organizations are **not free accounts**, they are network-native entities that must be provisioned through the Modulr protocol. To prevent spam, ensure commitment, and anchor long-term sustainability, every new organization requires a **minting cost** at creation.

Key principles of minting and pricing:

- **Oracle-Pegged Value**  
    The cost of minting an organization is **pegged to a fixed real-world value** (via decentralized oracles), rather than a static MDR amount. This ensures predictability for users regardless of token volatility.
- **Flexible Policy**  
    The protocol does not hard-code an absolute number. This leaves room for **ecosystem adjustments** such as promotional discounts, inflation adjustments, or tiered pricing for different types of organizations.
- **Subscriptions and Seats**  
    Once minted, organizations operate under a **subscription model**.
    - A flat subscription covers bundled access to Modulr utilities.
    - **Per-seat pricing** ensures scalability: larger organizations with many members contribute proportionally more, while small teams can remain cost-efficient.
    - Guest or contractor seats can be provisioned at reduced cost with limited permissions.
- **Service-Level Fees**  
    While the organization itself is permanent once minted, certain attached services (e.g., hosted websites through Modulr.Web) may require **recurring renewal fees**, similar to how traditional domain names and hosting operate. This prevents dormant or abandoned services from consuming resources indefinitely.
- **Minimum Membership Requirement**  
    To prevent misuse or “phantom orgs,” each organization must have at least **two distinct members**. This ensures that an org represents a genuine collaborative unit, not just a single user extending their identity.
- **Access Path**  
    Organizations are provisioned through the **Modulr portal** (official website and provisioning system), not through the Modulr.Store. This distinction reinforces their role as **infrastructure primitives**, not retail assets.
- **Non-Refundable Mint**  
    The minting fee is **non-refundable** and not tied to any staking period. Once created, the organization persists indefinitely, unless explicitly dissolved through governance.

---

#### 3. Core Capabilities

Once minted, an organization is a **first-class actor on Modulr**, with its own rights, resources, and responsibilities. Its core capabilities include:
- **Shared Treasury**  
    Every organization has a collective wallet with **multi-signature controls**, ensuring that no single individual can unilaterally spend or reallocate funds. Treasuries can be used to pay for compute, storage, robotics access, or external services across the Modulr network.
- **Role-Based Governance**  
    Organizations employ **role-based access control (RBAC)**. Critical actions such as adding members, transferring leadership, or executing treasury transactions require role-defined permissions and, in many cases, multi-signature approvals.
- **Dual Asset Ownership**  
    Organizations may hold collective digital assets (treasuries, licenses, or contracts) while individual members within the org can retain personal control over specific items. This hybrid model allows, for example, an AI model to be managed by a subset of developers while the broader org controls financial flows.
- **Direct Network Participation**  
    Organizations can act as independent entities within the ecosystem:
    - **Minting digital assets** under the organization’s identity.
    - **Contracting partners and validators** to provide services directly to the org.
    - **Publishing notifications and newsletters** to subscribed members or contributors with the option to extend into **Modulr.Social** for community-wide messaging.
    - **Engaging with co-chains** if an org owns or operates a co-chain, it can coordinate validators and partners at scale.
- **Public Auditability**  
    Unlike private SaaS workspaces, all organizational activity on Modulr is **on-chain, transparent, and auditable**. Financial flows, governance actions, and membership changes are verifiable by the public. This transparency ensures accountability and prevents abuse.
- **Succession Protocols**  
    To protect against inactive leadership, organizations may define **succession rules** that automatically reassign authority if a required transaction is blocked due to prolonged inactivity.
    - **Cool-down safeguards** prevent abuse, ensuring that transitions only occur when absolutely necessary.
    - **Out-of-Office Mode:** Members can flag themselves as unavailable, temporarily reducing their permissions without risking permanent role loss. This ensures continuity without punishing normal absences.
- **Indefinite Persistence**  
    Organizations do not expire or dissolve automatically. Once created, they remain active indefinitely unless explicitly dissolved through governance ensuring stability for long-term projects, businesses, and DAOs.

---

#### 4. Value Stack (Bundled Features)

Every organization on Modulr comes with a **baseline suite of utilities** included at creation. These features ensure that an org is not just a name on-chain, but a fully operational workspace from day one.
- **Web Presence (Modulr.Web)**  
    Each org will have an automatically provisioned website a digital headquarters for the group. This provides an immediate public-facing identity, eliminating the need to configure external hosting or domains.
    - The first year of hosting is bundled with the organization mint.
    - Afterward, recurring renewal fees apply, similar to traditional domain models.
- **D-Mail Instance**  
    Organizations will receive their own **decentralized mail system**, optimized for threaded, forum-style communication. This allows teams to track conversations more clearly than traditional inbox models and ensures discussions remain persistent and auditable.
- **Shared Storage & Compute**  
    Orgs gain access to shared storage and compute quotas, usable across the Modulr network. Subscriptions and per-seat models can expand these allocations as needed.
- **Branding & Analytics**
    - **Custom Branding:** Orgs can apply logos and color schemes to their websites, D-Mail, and other interfaces.
    - **Analytics Dashboards:** Heatmaps, time-on-page metrics, and content delivery statistics will allow orgs to understand how users interact with their Modulr.Web presence.
- **AI Assistance (Modulr.AI)**  
    Each org will be able to deploy an AI assistant trained on its own documentation and communication history. This makes it possible for members (or even customers) to query the org directly, receiving accurate answers without digging through lengthy records.
- **Automation Workflows**  
    Through Pseudo and Code Ledger, organizations can create custom workflows to automate repetitive tasks. Examples include:
    - Triggering payouts after invoice approval.
    - Auto-assigning roles or permissions after a vote.
    - Processing job requests from clients or partners.
- **Future Extensions**  
    Planned co-chains will expand the org bundle even further:
    - **Modulr.Social**: Organizations will automatically reserve a handle, enabling them to connect their governance and messaging with public community features.
    - **Modulr.Database**: Future orgs will gain integrated access to decentralized databases for structured information storage and querying.
    - **Third-Party Co-Chains**: The ecosystem is open as orgs can adopt services built by outside teams. For example, an HR/payroll co-chain (similar to how Gusto works in Web2) could manage salaries, scheduling, and member payouts directly through organizational treasuries.

Together, this **value stack transforms organizations from static entities into living workspaces**. With web presence, communication, storage, branding, AI, and automation planned as part of the core bundle plus future integrations across social, data, and third-party services. Every org begins its life fully equipped to operate, grow, and scale.

---

#### 5. Extended Integrations

Organizations are not limited to the core bundle of utilities. They can expand their functionality through both **native integrations** provided by Modulr and **third-party co-chains** built by the community. This makes every org an adaptable workspace that can scale as its needs evolve.
- **Federation of Organizations**  
    Two or more orgs can ally, share resources, and jointly govern specific assets. Federation allows for collaborative ventures where, for example, two robotics firms could co-own a fleet of devices or manage a shared treasury with multi-signature safeguards across both orgs.
- **Marketplace Participation**  
    Organizations can list products, services, or digital assets directly in **Modulr.Store**, turning their workspace into an economic actor. This could include selling compute cycles, offering access to robotics fleets, publishing software packages, or even selling real-world assets tokenized through Modulr.
- **Opt-In Discoverability**  
    By default, organizations are private identities. However, they can opt into discoverability, appearing in directories or external listings. This makes it easy for clients, partners, or collaborators to find orgs offering specific services.
- **Legacy Interoperability**  
    Through bridge co-chains, organizations can integrate with familiar Web2 tools such as Google Docs, Slack, or GitHub. This enables gradual migration from centralized platforms while maintaining compatibility with existing workflows.
- **Notifications & Social Integration**  
    Beyond internal newsletters, organizational announcements can extend into **Modulr.Social**, linking governance updates, project launches, or public communications to the wider network. This makes every org not only a workspace but a social presence.
- **Custom Extensions**  
    Because Modulr is modular by design, orgs can adopt specialized services as the ecosystem matures. Potential examples include:
    - **HR & Payroll Co-Chains**: Manage salaries, benefits, and payouts directly from the organizational treasury.
    - **Compliance & Audit Tools**: Enterprise-grade KYC/AML or reporting features, provisioned by third parties.
    - **Knowledge Management Apps**: Enhanced wikis or research tools layered on Modulr.Database.
    - **Collaboration Suites**: Voice, video, or task management built as co-chains and plugged into the org workspace.

---

#### 6. Roles & Governance

Organizations use **role-based access control (RBAC)** to define who can perform what actions. Roles are not just labels, they are **on-chain assets** bound to a member’s identity. This ensures that organizational authority is cryptographically verifiable, transferable, and enforceable.
- **Transferable Roles:** A role can be reassigned (with proper approvals) just like a digital asset.
- **Revocable:** Roles can be revoked by governance in the event of misuse or member removal.
- **Visible Across Modulr:** A member’s role in an org can appear in their Modulr.Social profile or linked identity, serving as both recognition and reputation.
##### Predefined Roles & Examples

- **President** – The highest authority, able to approve leadership transfers, appoint managers, and remove members.  
    _Safeguards:_ Member removal may require an additional signature, or may be limited to roles below a defined level. Orgs can also choose to replace this role with DAO-based governance.  
    _Example:_ The President nominates a removal; a Treasurer co-signs before the action finalizes.
- **Treasurer** – Manages finances and budgets.  
    _Example:_ The Treasurer signs off on a payroll batch that distributes funds from the org treasury to contractors.
- **Developer** – Maintains code, digital assets, or AI models.  
    _Example:_ Developers upload a new machine learning model into the org’s shared repository, with ownership linked to their role.
- **Manager** – Handles daily operations, including membership management.  
    _Example:_ A Manager approves three new Contributors and, based on delegated powers, may terminate a Contributor without requiring higher approval.
- **Support / Auditor / Marketing / Moderator** – Specialized functional roles, scoped by permissions.  
    _Example:_ A Moderator suspends a disruptive member, subject to automatic review if the role lacks full termination rights.

##### Governance Tools
- **Voting & Proposals:** Orgs can configure which roles have voting privileges, and whether those votes are weighted (e.g., President = 3 votes, Developer = 1 vote).
- **Delegation Chains:** Roles may delegate authority. For example, the President appoints a Manager, who in turn manages Contributors.
- **Custom Roles:** Beyond the predefined list, orgs can compose new roles by combining specific permissions from a master set.
- **Multi-Signature Safeguards:** Critical actions (treasury spending, leadership transfers, high-level member removals) can require multiple signers.
- **Templates:** Orgs may launch with prebuilt governance structures or design their own.
    - _Example:_ A **Startup Template** might include:
        - President (weighted 3 votes, full permissions)
        - Treasurer (2 votes, financial powers only)
        - 2 Developers (1 vote each, technical powers only)
        - Contributors (no voting rights)
        - Decisions require 5 weighted votes to pass.

---

#### 7. Future Expansion

Organizations are designed to be **foundational primitives** of Modulr; simple to understand at creation, but capable of expanding as the ecosystem matures. While the core capabilities provide everything needed to launch and operate from day one, future integrations will make Orgs even more powerful:

- **Compliance & Enterprise Tooling**  
    Third-party co-chains can provide **KYC/AML checks, audit reports, and governance compliance** for organizations that require enterprise-grade features.
- **Finance & Payroll Systems**  
    Specialized co-chains may manage **accounting, budgeting, or payroll** directly from organizational treasuries. For example, an HR/payroll co-chain could schedule salary payouts, manage benefits, and generate tax-friendly reporting.
- **Communication Layers**  
    Beyond D-Mail, future ecosystem apps may extend organizations into **voice, video, or real-time collaboration suites**, integrated directly into their Modulr identity.
- **Knowledge Management**  
    Organizations could adopt **wiki-style documentation systems** enhanced by Modulr.Database, allowing structured storage and retrieval of information. AI assistants trained on these knowledge bases would make onboarding and support seamless.
- **Cross-Org Collaboration**  
    Federation may evolve into more formalized structures, where multiple orgs can form **alliances, joint ventures, or consortiums** with shared governance and pooled treasuries.
- **Discovery & Reputation**  
    Organizations may opt into **network-wide directories** or discovery systems, making it easier for clients, contributors, and partners to find them. These directories could tie into reputation metrics, surfacing trusted orgs for specific services.
- **Template Ecosystem**  
    Developers will be able to create and sell **org templates** via Modulr.Store prebuilt structures for startups, DAOs, nonprofits, research groups, or gaming guilds. This enables rapid bootstrapping with tested governance models.

Ultimately, organizations represent **the bridge from individuals to institutions** on Modulr. They begin as a digital workspace but can evolve into full-fledged enterprises, DAOs, nonprofits, or even global federations and they are all backed by the same protocol that secures storage, compute and access across the network.

### Consensus and Rotation

Modulr operates on a 2/3 majority consensus mechanism, the reason behind this is that since a Creator is able to set up to 44% of the available slots with **known validators** (which guarantees them a spot), they have to get buy in from another 23% of unknown validators. This consensus system also works in regulating unknown validators since they must have buy in from at least 11% of the known validators. There is a potential problem with this however, the Creator could simply create more validators that are not listed and have them run on the network. 

Due to this potential vulnerability, a rotation schedule for validators will be implemented that forces **active validators** to swap out with **passive validators** which should reduce the risk. 

Between the rotation schedule and the 2/3 consensus mechanism I believe this will enforce the network to move forward. This also allows up to 32% of the validators to act in a deceptive way. There is a mechanism for validators and partners who operate in a deceptive manner which is called the Reliability score. If malice is detected your Reliability score is dropped. 

### Reliability Score

The idea behind the Reliability score is so that a validator or client can judge the merits of a user without having to do blockchain analysis on that user. This system **MUST** be closely monitored and can **NEVER** be used as a means of preventing transactions from occurring. This isn't a social credit score, but more of a reliability rating of that particular user. All users can experience a reduction in their Reliability score, but validators and partners are the most affected since it can prevent them from providing service on the network. Much like the ledger, the score is maintained by the validators (meaning they request the score to be updated), but is stored by the partners. 

#### Reliability Score - Loss

Validators can loose their Reliability score if

1. They provide false records of transactional events
2. They do not maintain up to date user / job / work / payout files
3. They fail to perform a transaction on a particular user(s)
4. Drop connection without notice
5. Being blocked from a large number of clients

Partners can lower their Reliability score if

1. Failure to maintain saved files
2. Falsify a transaction with a client
3. Are too slow for the task they promised they could do
4. Drop connection without notice
5. Blocked from several clients - *Not sure about this one*

#### Reliability Score - Gain

It's important to stress that this is **NOT** a social credit score, but like a credit score you can rebuild it. Since I am sure there will be instances where this happens by accident (especially with disconnects). 

Validators can gain Reliability score by

1. Being a passive validator
2. Participating on the test net
3. Recovering from a outage 7x (that means the resource has been used 7 times with no problems)
4. Having a higher number of connections than your peers

Partners can gain Reliability tokens by

1. Participating in the test net
2. Getting un-blocked
3. Recovering from a outage 7x (that means the resource has been used 7 times with no problems)

I am concerned about using the block feature as a means of determining a Reliability score as I am sure it will be used in a poor manner however, clients only hurt themselves when they block other users since that prevents them from using their services. Also, we should consider placing a mechanism that disregards the block if it's noted that client has a abnormally large blocked list. 

In order to make building the Reliability score more transparent we are introducing the XP system. With this system you will be able to see how much XP you need to get to the next level on your Reliability score. Along with XP, we will have seasonal events where if a participant meets the goals of the network they can earn XP boosts. 

### Scaling and Security

Modulr should move very quickly since we use so few validators in order to issue work on the chain, however there is a problem with network delay due to physical size so the use of parallel networks is to be used. The idea is that a parallel network operates in the same manner as each other with the exception being their user base. The user declares which network they wish to be apart of and with that they are provided a list of the validators that are responsible in that region to interact with. This doesn't mean that you are stuck on that network permanently though. You can initiate a transfer at anytime and your assets will travel with you. Again the reason for the parallel networks is to increase QoS by making content more local to that specific space, this includes the ledger. Much like how tokens are dispersed across co-chains they are also dispersed the same way with networks. Token allotment is decided by network 1 and is based on activity. 

##### How do you create a new network? You don't :) 

I still haven't decided just how I am going to do this, but I believe it will most likely be a mixture of algorithmic as well as Creator responsibility. Perhaps I could leave it to a vote?

#### Convergence

I believe that this blockchain is going to get large fast even with some of the space constraints that I am already planning on implementing. So what I am planning on implementing is a by product of the fact that we have decentralized storage on chain. What I am planning is that at least every flooring we implement The Convergence which is a process where we store all of the blockchains information on file and effectively restart the blockchain using the hash of the old chain as a genesis block. This would effectively lower the barrier in regards to how much RAM a validator needs since they can offload it onto the partners to store. The convergence will also occur when we have a cryptography swap (example switching to Kyber).

### Security

There is a concern with quantum computing on the rise that traditional cryptographic algorithms may become obsolete. If history tells us anything is that it's a matter of when a cryptographic algorithm will be cracked rather than if. Because of that potential danger, Modulr can modulate and / or change it's cryptographic algorithm. *This is why we have usernames rather than just use public keys* Initially we will use standard AES encryption since that is industry standard and seems like it should work for quite a while longer. When we are close to that algorithm being compromised we will initiate a crypto swap. This will notify users to generate a new public / private key pair using a more secure cryptographic algorithm. The user then responds with the public key to the new protocol and signs it with the current private key so we know it comes from them. The Validators then update the users file to reflect the new public key and on the day of go live we use those signatures instead. If a user fails to update their keys then during the next transaction we initiate a forced key migration (which sounds worse than what it is, basically we send a emergency message back saying to update the key). If that fails, then we allow the account to continue, but notify them that the account is high risk and can be compromised at anytime. Modulr should NEVER force a user to update their keys, but should warn them of the danger of not doing so. *Important to note, once we reach zero day (meaning the attack is live) we do not allow the user to change the key since we don't know if it's them. Instead they can use the freeze feature and hopefully it will go to a updated account. Or they can loose their digital assets if and when someone cracks their account.*

- Interesting thought would be to allow users to update their key at anytime, but I am not sure why anyone would do this. The validator has to mark the active public key anyway so it wouldn't matter if they did update their keys. 
	- Could lead to an attack if users are constantly updating their keys. Maybe charge for out of sequence key update?

## Pseudo Language

#### What is Pseudo?

Pseudo is a Pythonic-style language designed for securely creating real-world programs that run directly on chain within the Modulr protocol. It's main goal is to allow developers (Creators) a way to execute decentralized applications while maintaining a high level of security, fixability and accuracy. It provides a sandboxed environment that ensures no partner nor validator can exploit the system, protecting personal files and resources during the execution of these scripts. Pseudo is a heavily typed language so you will need to declare a variables type prior to using it such as: `my_var: i32 = 0`.

##### Sandbox Environment

Pseudo runs all of it's scripts within a sandboxed environment that is designed to limit access to the hosts (partner or clients) machine, so that malicious code should not be able to access data or resources that are outside the scope that the program can run within. This is done by the partner dedicating portions of their system for Modulr specific tasks; for example when setting up a new worker the user is asked how much of their storage space they want to dedicate to the blockchain (has to be within 4GB segments). At that point the 'working folder' cannot go outside this area. Any attempts to do so will result in a drop in Reliability score from the Creator. 

##### On Chain Compilation

Other than having the language create a sandbox environment, another security feature is that Pseudo code is compiled on chain. This means that if there is an attempt to access data outside of the range / scope of this program it will return as an error. The one exception to this rule is when Modulr is being ran on a local network, although technically it's still remote because the partner user type would need to compile the code. 

##### Co-Chain Extensibility

Developers can import functions from other co-chains, extending the language functionality using the `from` and `import` keywords (in the same way that python does). *I am debating on 'installing' a co-chain as a means of preventing issues with naming conflicts, but I think this will work as is*

**Example**

```Pseudo
from pages import ratings, client

if ratings(Modulr.info) >= client.age:
	show()
```

In this example we are importing the ratings section of pages as well as the client profile and from there we are checking to see if this client profile is allowed to see this page.

#### Custom Types

Pseudo introduces new custom types that make coding easier are much easier to understand as well as accurate. One of those types is the decimal type, which is meant to resolve the issue with float accuracy. This is done by creating two of *x* size, with one being the whole number and the other being the decimal number. 

**Example**

```Pseudo
# Create a decimal number of 32 + 32 bits in size
token_balance: d32 = 123.456
big_numba: i64 = 1,234,456
```

Types are declared in the same way they are in Python (yes you can declare types in Python, but it only helps the intellisense) using the colon (:) symbol. I also showed that you can use the comma to separate large numbers to make them more readable. 

#### New Keywords

##### When

The **when** keyword is meant to be used for asynchronous process (which are common for Modulr since everything will happen over the network). This provides a structure that makes this easier to read and write when you are waiting on a specific event. Plus it eliminates the need to poll a resource all the time to wait on a specific value.

**Example**

```Pseudo
from pages import partner

READY: bool = 1
NICE: i16 = 69
partner_status: listener = partner.ready

when partner_status == READY:
	some_method(NICE)
```

This is not the best example since you would normally say `when partner.ready == READY`, but I also wanted to show off the listener type. The when keyword operates much like an if statement with the exception being it only runs when that event has happened. I will expand this so that you can use this for parallelization in the future rather than just an asynchronous tasks. 

#### Case Insensitive

At this time it is our intent to make the language case insensitive, meaning that the keyword `when` and `WHEN` are the same. This is also true for variable names like `apple` and `Apple`. I don't believe this will cause issue other than coding style debates which will always be a problem.

## Decentralization

Ensuring that the network stays decentralized and ensuring that there is no concentration of resources going to one area is a key factor with Modulr. With that in mind the chain will envelop protocols that are designed to keep with those philosophies. One such method is the separation of powers between the different user types. With that in mind this section will discuss how these separation of powers come into play regarding the network.

#### Creators

While Creators do create the rules for the chain, they are bound by the fact that they cannot enforce them as this is a role that is split between Clients, Validators and Partners. It is very possible that a Creator could release an update and if the Validators and partners choose not to run observe it, the new version would simply be skipped. This was done to stop potentially bad code from running on the network and to keep Creators honest in their updates. This doesn't mean they cannot spin up a new chain with this new code, but it does ensure that the community agrees to the terms outlined in those changes. 

#### Validators

Validators are only as authoritative as clients allow them to be, if a group of validators are acting within self interest clients can simply ignore them and drop their Reliability scores and since the network is only interested in staying online it will switch over to validators that have that higher Reliability score. Validators can also be blocked by a Creator through various means (primarily through setting the minimum threshold on the Reliability score), but a Creator could block a particular Creator from participating. Lastly validators are graded based on the connections they make and if partners are not contacting them this lowers their Reliability score (as it does with clients) and they will be taken offline. There is a small exception to this with the use of known validators, but there is a threshold to which even a known validator will lose their spot if the Reliability score drops. 

#### Partners

What use is a partner that is never used? If a partner is not being utilized then they are just burning electricity for no tokens and just like validators partners can loose Reliability score if they are providing no utility. Unlike partners, a Creator cannot remove them from the chain from providing utility (I don't think its necessary). Partners can drop in Reliability if they claim to perform utility and either cannot perform the utility as promised or doesn't do it at all. The validator has the choice to not provide a partner with work *only if* they have a proven track of being unreliable.

#### Clients

It is illegal on Modulr to not process a transaction regardless of how poorly a user acts on chain. If you make a request and you meet the fee then the transaction is performed. So, what Modulr does in cases where a client who has a low Reliability score, is in cases where you are submitting a claim against another user it reduces the likelihood you will win that claim without substantial proof. How do clients have low Reliability scores? Mainly through false claims, but also when they act in either of the other user types. Think that you are a partner who has earned tokens and then you want to use network resources with those tokens, but you provided poor service. As always, you can redeem yourself by acting as a partner or validator. 


### Latency / Cost

While a balance of power is key that doesn't completely ensure decentralization, so another method we use is latency. Along with affecting your Reliability score, having a low response time (or cost) makes you more preferred on the network and in the case of partners, gives higher rewards. This encourages the network to be more spread out since if you are closer to the client (assuming the same hardware and networking) then it will guarantee you win the latency game. Remember that latency is how fast you can respond to a clients request. You could be right next door to your client using LoFi, but if it takes you 10ms to process a request that another partner a state away can process in 1ms then you will loose. 

### Pool-less Protocol

While having a separation of power between the validators who maintain the blockchain and the partners who hold the ledger and process the payments. There is another reason the validators exist, and that is to keep mining pools away from Modulr. There is no need for them; the Validators already perform token distributions and traffic control so there is no benefit for another entity to perform that function. This also gives the partners full rewards since validators don't earn SP.

## Wallets

Had a thought while doing some development work in regards to having hot and cold wallets, and since Modulr needs the ability to sign transactions (fairly regularly) I think it may be wise to implement the idea of hot and cold wallets so that users already have that as a additional means of security. What this would mean is that instead of just one public address in a user accounts name you would have two. I need to think more on this and how it should be implemented. I will say for sure that fees between those two wallets will be zero.

# Code Bounties

In this section I am going to list out the active *bounties* for the Modulr project. The Bounty program is meant to not only list what is needed for chain development, but also provide reward structures for each *contract* that is listed. 

One of the ideas I have for Modulr is to make it so that open source software doesn't mean free, which means for everyone not just the project. This not only refers to the organization which can receive tokens, nor the Creator(s) who can collect fees, but also freelance developers who are looking to assist in a project. 

Modulr itself has a startup developer fund of 1 million GP as well as 10 million SP. Modulr will also use this fund to support new co-chains since new blockchains coming into Modulr help support the eco system and make Modulr better. 

Currently there are no active bounties at this time as the system is still under development, but I am going to make some examples of what a warrant should look like. *Note: this is currently being posted in GitHub, but will eventually only exist on Modulr once the Code Ledger side chain goes live*

## Example of Bounties


### Example of a Co-Chain Contract

**Wanted**:  Need to develop a co-chain that allows users to lease high end hardware with low latency to a users for use in gaming environments. The name of this chain is **Player2** and the goal is to allow thin clients the ability to stream content and extremely low latency rates (>10ms) via the access protocol. 

**Status** - Open

**Payout**: 10,000GP

**Participants**: @Undline(0)

**Total Contribution**: 0 - Never

**Breadcrumb** - Need to outline the technical specifications as well as how this can work.

**Timeline**: Technical outline due out by August 2025

#### Explanation

While Modulr is the only chain that should be requesting new chains (although anyone can do that). I believe this shows a good example of what a contract should looks like. 

1. **Wanted** - This defines what is being sought after and should be treated as an overview, meaning what the final product should be. *I should probably limit this field to a specific amount of characters to enforce the idea that this should be a brief description.*
2. **Status** - The current status of the contract. Open means you are looking for candidates, active means that the module is being worked on and is not open for additional candidates at this time (this should only be reserved for large projects that may have too many participants) and closed which means the contract was completed.
3. **Payout** - As the name suggests, it's the total payout from the contract. This payout will be subdivided across all participants on the team with an emphasis on usage. Meaning how often a contribution is used or referenced. *payout is going to be the trickiest portion of the algorithm to implement since people will always try to game the system to get more.*
4. **Participant** - This is the account(s) / organization that is currently registered to work on this contact. There is also a listing of how much of the project (in percent) that has been contributed by each individual.
5. **Total Contribution** - Refers to how many commits have been made to the project along with the last date. This gives any prospective developer an idea on how active a project is.
6. **Breadcrumb** - This section gives the developer an idea on what is the primary focus at this time. I think this would only be needed for building Co-Chains, but it's possible this may be helpful in smaller projects as well. 
7. **Timeline** - This states where the project is at in it's development stage as well as target dates. ideally displayed in something like a Gantt chart. 

I believe there will need to be more things that need to be added so this needs to be open for extension...

### Example of a Improvement Contract

**Wanted** - Add documentation to the readme file that describes what a warrant / contract looks like. 

**Status**: Active

**Payout** - 4SP

**Participant** - @Undline(100)

**Total** **Contribution** - @Undline(20) - 2024-06-23

**Breadcrumb** - Describing how the Warrant system works for improvements

**Timeline** - 2024-04-04

#### Explanation

The definitions are the same from before, but this shows two things. First, what it should look like when you have some contribution going on and second, that it doesn't have to be *code* that is being worked on. Ideally anything that can be represented digitally could be used here. In this case we are requesting that better documentation exist.

### Example of a module update

**Wanted** - Need to implement a LRC caching system for faster response times when a client requesting pages that are in high demand.

**Status** - Open

**Payout** - 2GP

**Participant** - None

**Total Contribution** - None

**Breadcrumb** - Start

**Location** - data_strcutures.py

**Timeline** - 2024-07-09

#### Explanation

This is a quick example of what it would look like to have a contract open on a specific module. In this example I added a new category called location. I am not sure if the other contacts would need it so I am going to leave it as `none` in those files.


### Example of an Improvement Contract

Wanted - Need to add functionality that allows multiple clients to stream updates to one another over a singular document. The largest challenge will be managing conflicts. Mutex certain portions of the document?

**Status** - Open

**Payout** - 100GP

**Participants** - None

**Total Contributions** - None

**Breadcrumb** - Define project objectives

**Location** - New 

**Timeline** - None

This example is meant to show how you could create a contract that adds functionality to an existing project. 

### Example of a Hardware Contract

**Wanted** - Need to create a wireless device that can use multiple radio frequencies that broadcast Modulr routing protocols that enable fast local communication. 

**Status** - Open

**Payout** - 100,000GP, 40,000SP

**Participants** - None

**Total Contributions** - None

**Breadcrumb** - Define operating parameters to stay compliant with local laws. Use LoRA and WiFi as a starting point?

**Location** - Altera 

**Timeline** - None

Not sure if this will work out well, but I was thinking we could also make real world projects using this same open system. In this case the location could be to use a program (I used Altera as an example since that's where you would make PCBs). 

### Conclusions

This should all be housed inside programs that have a form of revision control so that you can maintain and control projects. Ideally you would have an *organization* (in Modulr) responsible for creating these projects that way you can define roles and positions that you need. *Tip: never skip out on Documentation or Quality Control as it is critical for any successful project...*

---
# Technical Documentation / Roadmap


## Code Guidelines

Any submitted code should have type definitions as well as doc strings to accompany any new methods.

## Roadmap

Follow this link to see the internal roadmap for Modulr to get more in depth knowledge on how the technology works [Internal Modulr Roadmap](docs/Internal_UndChain_Roadmap.md)

We are currently in [Phase 1](docs/Phase_1.md)
