---
layout: default
---

<div class="parallax">
  <section id="landing" class="parallax__layer parallax__layer--base">
    <div class="section-content">
      <h1>{{ site.project_title }}</h1>
      <div class="team">
        <h2>Team Members</h2>
        {% for member in site.team_members %}
        <p>{{ member.name }}</p>
        {% endfor %}
        <h2>Mentor</h2>
        <p>{{ site.mentor_name }}</p>
      </div>
      <div class="links">
        <a href="{{ site.github_link }}" target="_blank">
          <i class="fab fa-github icon"></i>
        </a>
        <a href="{{ site.drive_link }}" target="_blank">
          <i class="fab fa-google-drive icon"></i>
        </a>
      </div>
    </div>
  </section>
  
  <section id="introduction" class="parallax__layer parallax__layer--back">
    <div class="section-content">
      <h2>Introduction</h2>
      <p>
        Real estate transactions are notoriously slow, expensive, and riddled with inefficiencies. From lengthy paperwork to reliance on intermediaries, the process often frustrates buyers, sellers, and agents alike. Enter <strong>PropChain</strong>, a blockchain-based platform designed to streamline and secure property transactions using smart contracts.
      </p>
      <p>
        At its core, PropChain leverages the power of blockchain to automate processes like escrow, title transfers, and payments, reducing costs and eliminating delays. By recording transactions on an immutable, distributed ledger, we ensure transparency and trust for all parties involved. But PropChain doesn’t stop there – it also introduces a unique incentive system where users earn tokens for verifying property details, creating a community-driven approach to real estate.
      </p>
      <p>
        Our goal is simple: to make real estate transactions faster, cheaper, and more transparent, empowering users to take control of their property dealings. Whether you’re a buyer, seller, or agent, PropChain is here to transform the way you think about real estate.
      </p>
    </div>
  </section>
  <section id="methodology" class="parallax__layer parallax__layer--base">
    <div class="section-content">
      <h2>Methodology</h2>
      <p>
        PropChain is built on a foundation of cutting-edge technologies and innovative approaches. Here’s how we did it:
      </p>
      <ul>
        <li>
          <strong>Blockchain Technology</strong>: 
          At the heart of PropChain is blockchain, a decentralized and distributed ledger technology. Blockchain ensures that all transactions are:
          <ul>
            <li><strong>Immutable</strong>: Once recorded, data cannot be altered or deleted, ensuring trust and security.</li>
            <li><strong>Transparent</strong>: Every transaction is publicly visible and verifiable by all participants.</li>
            <li><strong>Decentralized</strong>: No single entity controls the network, reducing the risk of fraud and manipulation.</li>
          </ul>
          We used <strong>Ethereum</strong>, a leading blockchain platform, to build PropChain. Ethereum supports smart contracts, which are essential for automating real estate transactions.
        </li>
        <li>
          <strong>Smart Contracts</strong>: 
          Smart contracts are self-executing programs that run on the blockchain. They automatically enforce the terms of an agreement when predefined conditions are met. Here’s how they work in PropChain:
          <ul>
            <li><strong>Automation</strong>: Smart contracts automate processes like escrow, title transfers, and payments. For example, when a buyer and seller agree on terms, the smart contract holds the funds in escrow and releases them only when all conditions (e.g., title transfer, inspection) are satisfied.</li>
            <li><strong>Transparency</strong>: The code of the smart contract is publicly visible on the blockchain, ensuring that all parties can verify its logic and fairness.</li>
            <li><strong>Security</strong>: Once deployed, the smart contract cannot be altered, eliminating the risk of tampering or fraud.</li>
          </ul>
          Smart contracts are written in <strong>Solidity</strong>, a programming language specifically designed for Ethereum. They are deployed on the Ethereum Virtual Machine (EVM), which executes the code in a secure and decentralized manner.
        </li>
        <li>
          <strong>Front-End Interface</strong>: 
          Our user-friendly interface allows buyers and sellers to easily search for properties, initiate transactions, and track progress in real time. The design prioritizes simplicity and accessibility, making it easy for anyone to use. The front-end is built using modern web technologies like <strong>React.js</strong> and connects to the blockchain via <strong>Web3.js</strong>, a library that enables interaction with Ethereum-based applications.
        </li>
        <li>
          <strong>Property Verification</strong>: 
          To ensure the accuracy of property listings, we implemented a verification system that uses geolocation data and EXIF tags from uploaded photos. In the future, we plan to integrate AI to further enhance this process by analyzing photos for consistency with the property’s location.
        </li>
        <li>
          <strong>ERC-20 Token System</strong>: 
          Users earn <strong>ERC-20 tokens</strong> for verifying properties, creating a community-driven approach to maintaining accurate listings. These tokens can be used within the PropChain ecosystem. This incentivizes participation and reduces the need for costly third-party verification services.
        </li>
      </ul>
    </div>
  </section>
  
  <section id="workflow" class="parallax__layer parallax__layer--back">
    <div class="section-content">
      <h2>Workflow and Discussion</h2>
      <p>
        PropChain has already demonstrated its potential to transform real estate transactions. Here’s a look at our workflow, results, and future plans:
      </p>
      <ul>
        <li><strong>Project Timeline</strong>:
          <ul>
            <li><strong>Phase 1</strong>: Research and planning – identifying pain points in real estate transactions and designing a blockchain-based solution.</li>
            <li><strong>Phase 2</strong>: Development – building the platform’s core features, including smart contracts, property search, and verification.</li>
            <li><strong>Phase 3</strong>: Testing – conducting internal tests and refining the platform based on results.</li>
            <li><strong>Phase 4</strong>: Launch – making PropChain available to the public and gathering real-world data.</li>
          </ul>
        </li>
        <li><strong>Key Results</strong>:
          <ul>
            <li><strong>Faster Transactions</strong>: By automating processes, PropChain reduces transaction times from weeks to days.</li>
            <li><strong>Lower Costs</strong>: Eliminating intermediaries cuts costs for buyers, sellers, and agents.</li>
            <li><strong>Enhanced Transparency</strong>: All transactions are recorded on the blockchain, ensuring trust and accountability.</li>
            <li><strong>User Engagement</strong>: The token incentive system encourages active participation, creating a community of users.</li>
          </ul>
        </li>
        <li><strong>Challenges and Solutions</strong>:
          <ul>
            <li><strong>Challenge</strong>: Ensuring the accuracy of property listings.</li>
            <li><strong>Solution</strong>: Implementing geolocation and EXIF-based verification, with plans to integrate AI for further improvements.</li>
            <li><strong>Challenge</strong>: Making the platform accessible to non-technical users, and those who dont necessarily want to buy properties.</li>
            <li><strong>Solution</strong>: Designing an intuitive interface, multiple account creation methods, and removing the necessity to set-up a wallet to use other features, such as title search.</li>
          </ul>
        </li>
        <li><strong>Future Improvements</strong>:
          <ul>
            <li><strong>Government Integration</strong>: Collaborating with land registry systems to streamline title transfers.</li>
            <li><strong>Cross-Border Transactions</strong>: Expanding the platform to support international real estate deals.</li>
            <li><strong>AI-Powered Verification</strong>: Using AI to analyze uploaded photos and ensure they match the property’s location.</li>
            <li><strong>Token Ecosystem</strong>: Expanding the use of tokens to incentivize more user actions, such as property listings and reviews.</li>
          </ul>
        </li>
      </ul>
    </div>
  </section>

  <section id="conclusion" class="parallax__layer parallax__layer--base">
    <div class="section-content">
      <h2>Conclusion</h2>
      <p>
        PropChain represents a significant step forward in the real estate industry, addressing long-standing inefficiencies with innovative blockchain technology. By automating processes like escrow, title transfers, and payments through smart contracts, we’ve created a platform that is faster, cheaper, and more transparent than traditional methods.
      </p>
      <p>
        Our results speak for themselves:
        <ul>
          <li><strong>Faster Transactions</strong>: Reduced from weeks to days.</li>
          <li><strong>Lower Costs</strong>: Eliminated intermediaries, saving users thousands.</li>
          <li><strong>Enhanced Transparency</strong>: Immutable blockchain records build trust.</li>
          <li><strong>User Engagement</strong>: Token rewards incentivize participation and accuracy.</li>
        </ul>
      </p>
      <p>
        Looking ahead, PropChain has the potential to revolutionize not just real estate but also other industries reliant on intermediaries and manual processes. By continuing to innovate and expand, we aim to make PropChain the go-to platform for secure, efficient, and user-friendly transactions.
      </p>
      <p>
        Join us in reshaping the future of real estate – one blockchain transaction at a time.
      </p>
    </div>
  </section>
</div>
