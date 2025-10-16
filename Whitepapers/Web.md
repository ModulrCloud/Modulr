# Modulr.Web

This whitepaper is still being written as a means of reducing clutter in the core whitepaper. Below is what was in the core section previously so I have a starting point. Also as a note Live will be incorporated into Web as it makes sense to have live streaming working with the decentralized web so I added the notes on live at the bottom here.

---


Modulr.Web (formally Pages) is Modulr’s decentralized Web system, offering a modern alternative to traditional web technologies. Replacing HTML and CSS with **M3L** (Multi-Media Markup Language) and **GSS** (Global Style Sheets), Modulr>Web provides a scalable, efficient, and privacy-centric experience for both creators and users.

**Legacy Domain Protection**

Modulr respects legacy (HTTP) domain names ending in **.com**, **.org**, **.gov**, **.edu**, and **.net**. These domains are reserved exclusively for their rightful owners as registered on the traditional internet to prevent impersonation and fraud. This ensures that trusted brands and institutions retain their identity in the transition to decentralized web technologies.

All other domain types (e.g., **.io**, **.xyz**) are not automatically recognized or reserved within the Modulr ecosystem. This boundary is established to maintain clarity and fairness while minimizing complexity.

#### Key Features:

1. **Efficient Content Delivery**
    
    - **M3L** and **GSS** revolutionize how content is served by allowing updates to individual components rather than entire documents, significantly reducing network load.
    - Dynamic scaling ensures that popular pages are hosted across multiple partners based on demand and region, maintaining uptime and low latency even during high traffic.
    - To learn more about M3L and GSS: [M3L and GSS Documentation](M3L_GSS.md)
2. **Advanced Content Types**
    
    - Unlike HTML, **M3L** supports more advanced content types, such as **video**, **chat**, and **canvas**, enabling developers to build richer, more interactive applications directly on the Pages co-chain.
    - M3L is designed for modularity and efficiency, referencing content locations dynamically rather than embedding them, reducing redundancy and improving scalability.
3. **Tailored User Experience**
    
    - Pages includes a **featured content section** personalized to each user’s interests. This section is fully editable, giving users control over the recommendations they see.
    - Content is also **classified and rated** to ensure users know what to expect from a site. Ratings are especially useful for identifying mature content or categorizing pages by their intended audience.
4. **Page Rating System**
    
    - Users can **rate pages**, helping to maintain honesty and accountability. If creators falsely claim their pages are safer than they are, they receive a penalty to their Reliability score. Similarly, users who submit false negative claims about a page’s rating will also experience a decrease in their Reliability score.
    - Only ratings from users with **reputable Reliability scores** are taken seriously, ensuring the system rewards fairness and transparency.
5. **Privacy by Design**
    
    - By eliminating cookies and intrusive tracking methods, Pages protects user privacy while still providing a seamless browsing experience.
    - The platform leverages decentralized systems to ensure user data remains secure and under their control.
6. **AdCoin: The Native Token**
    
    - AdCoin is the native utility token for Pages, enabling a frictionless user experience. Users can choose to earn AdCoin by interacting with ads, assisting in **Mimic AI model training** (e.g., teaching AI how to draw or solve logical problems), or swap with other in network tokens to support an ad-free browsing experience.
    - AdCoin integration across the network ensures seamless monetization options for creators and users alike.
7. **Age Verification and Content Control**
    
    - The **Adult_Swim Protocol** introduces a decentralized age verification system. Instead of storing user data, it uses markers to verify whether an account holder meets age requirements.
    - Verified entities can grant age status, but any organization providing false records loses its ability to verify accounts, and all associated accounts lose their status. The Modulr organization can act as the default age verifier but primarily delegates this function to trusted entities.
8. **Seamless Integration with Web4**
    
    - Pages works seamlessly with other Modulr co-chains, leveraging **M3L** and **GSS** to enable powerful tools like Mimic-powered assistants. These assistants can guide users through the network, troubleshoot issues, and provide real-time help for specific features in the apps they support.
9. **Content Reaction System**
    
    - Pages includes built-in tools for users to react to and interact with content. This feedback helps site owners gauge audience sentiment and improve their offerings. For example, news articles and videos can be rated positively or negatively, providing valuable insights.

10. **Integrated A / B Testing**

    - Pages provides users the ability to do A / B testing, allowing developers the ability to run two different sites to see which gets the most interaction.


---

### Live - Decentralized Real Time Streaming

The Live co-chain is Modulr’s dedicated decentralized audio/video streaming co-chain, built to deliver **low-latency**, **interactive streaming**, and enhanced accessibility while empowering creators to retain ownership and monetization of their content. Its modular design integrates directly into other co-chains like **Pages** and **Smack**, with advanced tools for user interaction, adaptive scaling, and intelligent AI integration through **Mimic**.

#### Key Features

1. **Decentralized Streaming with Low Latency**
    
    - Live targets **AV1 encoding**, a royalty-free, bandwidth-efficient codec, enabling smooth, low-latency streaming with minimal resource consumption.
    - Designed for interactive experiences, Live powers **real-time events**, including live chat, reactions, and audience engagement (reactions or polling).
2. **Dynamic Content Distribution**
    
    - Live leverages a **spread protocol** that dynamically scales streams based on **popularity** and **regional demand**, ensuring high-traffic content is delivered efficiently.
    - Content distribution happens organically as partners prioritize high-demand streams, enhancing availability and reducing latency for end users.
3. **Interactive Streaming Applications**
    
    - Live supports **advanced user interactivity**, allowing content to respond to viewer actions within the stream. Examples include:
        - **Clickable Video Interactions**: Users can click specific areas of the video to trigger events (e.g., playing different videos or navigating a decision tree). This system allows developers to create interactive video-based applications like **choose-your-path games** or **interactive learning tools**—serving as a precursor to **Player2**.
        - **Dynamic Polls**: Streamers can integrate real-time polls and feedback mechanisms to gauge audience sentiment and preferences.
    - **Audience-Driven Content**: Viewers’ actions and interactions can influence the flow or content of the stream, creating a uniquely immersive experience.
4. **Intelligent AI Integration with Mimic**
    
    - Live incorporates **Mimic**, Modulr’s AI co-chain, to enhance content accessibility and usability:
        - **Screen Reading**: When users pause a stream, Mimic analyzes the screen to enable text recognition. Users can copy and paste relevant text, such as captions, notes, or displayed information.
        - **Closed Captioning**: Mimic automatically generates real-time captions, making streams accessible to a broader audience, including those with hearing impairments.
        - **Intelligent Insights**: Mimic can assist streamers by analyzing viewer behaviors and content interactions, helping optimize future broadcasts.
5. **Screen Sharing with M3L Efficiency**
    
    - Live introduces a **screen share system** designed for bandwidth optimization and seamless interactivity:
        - Instead of streaming raw video, Live transmits the **M3L (Multi-Media Markup Language)** structure of the shared screen to recipients. This significantly reduces bandwidth usage while ensuring clarity.
        - **Audio Support**: While M3L handles visual elements, audio streams separately to maintain synchronization.
        - **Content Sharing**: If the shared screen plays a video, Live ensures all users pull the video from the same source, eliminating redundancy and maintaining efficiency.
    - This feature is ideal for **tutorials**, **collaborative workflows**, and **interactive presentations**, where precise, low-bandwidth screen sharing is essential.
6. **Full Ownership and Monetization**
    
    - Streams and recorded broadcasts are tokenized as **digital assets**, enabling creators to maintain ownership, set pricing models, and monetize their content.
	    - This will be done with the assistance of the Auction House co-chain.
    - Creators can define **royalty structures** for specific content types like music, video, or interactive streams, ensuring they earn revenue whenever their assets are reused or resold.
    - Revenue-sharing mechanisms allow creators and collaborators to split earnings transparently.
7. **Integration with Pages and Smack**
    
    - **Pages**: Streamers can embed Live broadcasts directly into M3L-based web pages for seamless Web4 integration.
    - **Smack**: Live supports video uploads and sharing within decentralized social media applications.
8. **Regional and Adaptive Scaling**
    
    - Popular content is redistributed to local partners dynamically, enhancing performance and reducing latency.
    - Partners are incentivized to prioritize streams with high demand, aligning with Modulr’s decentralized resource-sharing model.
9. **Monetization with USP and AdCoin**
    
    - Live content can be monetized using:
        - **USP**: The native utility token for Live transactions.
        - **AdCoin**: Can be swapped for USP or earned through network 'ad hubs'.
    - Users benefit from flexible payment options, while streamers enjoy consistent monetization streams.
10. **Content Ratings and User Safety**
    
	- Live adheres to Modulr’s **content rating system**, ensuring streams are appropriately classified.
	- Stream creators can implement **age restrictions** for sensitive content using the Adult_Swim protocol, which verifies users’ eligibility without exposing personal data.

#### Use Cases

- **Interactive Streaming Platforms**: Live alternatives to Twitch, YouTube Live broadcasts, or webinar services with enhanced interactivity.
- **Choose-Your-Path Applications**: Interactive games, training tools, or learning modules where viewers’ choices guide the video content.
- **Tutorial and Collaborative Workflows**: Efficient, low-bandwidth screen sharing for educational and professional use.
- **Content Accessibility**: Closed captioning, screen text recognition, and content optimization with Mimic integration.
- **Content Monetization**: Pay-per-view, subscription models, and royalty-based earnings for creators.

#### Why Live Stands Out

Live combines decentralized streaming, low latency, interactive features, and AI-driven enhancements to deliver a streaming platform unlike any other. It empowers creators, enriches viewer experiences, and integrates seamlessly into Modulr’s broader Web4 ecosystem. Whether embedded in Pages, used on Smack, or powering standalone applications, Live provides the tools to build the next generation of interactive, decentralized streaming solutions.

#### Developer Focus: Building with Live

Live demonstrates how Modulr’s co-chains work together to create powerful, interconnected systems. By integrating components like **Mimic’s AI tools**, **Pages’ content distribution**, and **Smack’s social sharing features**, Live showcases the flexibility and modularity developers can leverage when building their own co-chains.

With Modulr, developers are encouraged to think beyond isolated systems—creating dynamic, interoperable applications that scale effortlessly and provide unmatched user experiences.

---