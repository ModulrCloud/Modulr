# Modulr.Store

Below is what was taken from the core whitepaper as a means of consolidation. Please use this as a starting point for the actual whitepaper for Store

---


Modulr.Store (formally Auction House) is Modulr’s decentralized marketplace for minting, trading, and protecting digital assets on the network. It uses **MDR** as the default transaction token. Users can seamlessly swap other digital assets such as robotics routines, AI models, co-chains themselves and yes monkey pictures.

#### Key Features

1. **Digital Asset Contracts**:
    
    - Assets are minted using Modulr’s **standard Digital Asset Contracts** as defined by the main chain. Those assets are as follows:
        - **Gray (Unregistered)**: Default for unprotected assets.
        - **Green (Rental)**: Allows limited-use rentals with royalties sent to the creator.
        - **Blue (Single Use + Sharing)**: Enables personal use and sharing, with a kickback for creators when shared content generates value.
        - **Purple (Ownership)**: Allows reselling and distribution but restricts modifications.
        - **Gold (Full Use)**: Complete ownership, including rights to resell, modify, and monetize.
    - Certain categories of assets, like **music, videos, or games**, automatically integrate **royalty payments** for creators.
    - Asset metadata includes ratings, version history, and licensing terms to help buyers make informed decisions.
2. **Fraud Detection and Claims**:
    
    - The Auction House connects users to **Digital Asset Protection Providers (DAPPs)**, who handle protection, disputes, and enforcement actions.
    - Filing a claim requires a **fee**, with the amount determined by the **Reliability score** of the claimant. Users with lower scores pay higher fees to discourage abuse.
    - Winning claims result in asset ownership being transferred to the rightful owner, along with the claim fee. False claims reduce the claimant’s Reliability score and reward the accused with the fee.
    - **RWA Protection**: Digital assets proven to infringe on real-world copyrights (RWAs) are transferred to rightful owners or destroyed.
3. **Trust and Transparency**:
    
    - Sellers are classified visually on the Auction House based on their **Reliability score**:
        - High-trust sellers are marked with a **verified badge** or highlighted visually for buyers.
        - Low-trust sellers have clear **warnings or indicators** near their listings.
    - Listings display whether the seller is the **original creator** or a **reseller** of the asset, helping buyers identify primary sources.
    - All transactions, bids, and claims are stored **on-chain** for full transparency.
4. **Resale Royalties and Sharing Incentives**:
    
    - **Green and Blue Contracts** integrate royalty systems:
        - **Green Contracts**: Suitable for rentals (e.g., short-term music, video, or asset licensing). Creators receive royalties on repeated rentals.
        - **Blue Contracts**: Allow creators to benefit from content sharing (e.g., reaction videos or embedded content), receiving a share of generated revenue.
    - Creators can automate royalty payments through smart enforcement using DAPPs.
5. **Fraud Prevention and AI Support**:
    
    - The Auction House leverages **Mimic AI** to scan for duplicates, unauthorized content, or stolen RWAs. This is used as a warning system to the creator to let them know they *MAY* have created a copyright work. The creator will then respond to that as to why it's not which can be used if the asset is challenged in the future. 
        - *Note: This does not apply to gray assets as they do not hold any protections on the network*
    - Buyers receive warnings if flagged assets are listed for sale, ensuring informed purchases.
6. **Buyer Protections**:
    
    - Buyers are encouraged to research sellers’ **Reliability scores** and **transaction histories**.
    - If a purchased asset is later proven to infringe an RWA, buyers can **file claims** for compensation against sellers through the DAPP system.
7. **Subscription Features**:
    
    - Sellers can opt for premium subscriptions to gain tools such as featured listings, detailed analytics, and automated pricing suggestions.
    
8. **Monetization Features**

    - The Auction house introduces referral links as well as a coupon code system which gives sellers the ability to provide discounts or incentivize influencer the ability to receive a commission from a sale.

#### How It Works

The Auction House offers a fair, transparent, and decentralized experience for creators, buyers, and sellers:

1. **Creators** mint assets using standard contracts, protecting ownership and enabling monetization.

2. **Buyers** purchase or bid on verified assets, with tools to check seller trust levels and asset legitimacy.

3. **Resellers** can list assets while ensuring creators receive royalties if applicable.

4. **DAPPs** ensure claims, enforcement, and disputes are handled without Modulr involvement, preserving decentralization.

#### Visual Seller Classification

To improve trust and clarity, sellers will be visually classified:

- **Verified Sellers**: Creators or trusted resellers with high Reliability scores receive a **verified badge** and enhanced listing visibility.
- **Warning Sellers**: Sellers with low Reliability scores or flagged histories have **warnings** displayed near their listings.

**Reliability scores** are dynamic and affected by seller behavior, claims, and buyer feedback.

#### Final Notes

The Auction House ensures that digital assets remain protected, accessible, and monetize through a robust and decentralized system. It empowers creators with tools to enforce ownership, buyers with transparency, and the network with fraud prevention mechanisms.