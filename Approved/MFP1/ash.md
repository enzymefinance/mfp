# MFP #1 #


# *Proposal Update Nr. 1* # 


## 1 Funding Schedule & Milestones ##

**Phase 1: Apr- Jul 2019; CHF 364,000**

*Main Milestones:* 

###### Public Beta on Kovan ######

- conduct Alpha user interviews
- iterate over features based on user feedback and usage data
- complete Alpha backlog tasks
- release in App Store & Google Play Store

*General Development:*

- Melon/Giveth Module R&D
- Legal groundwork in preparation for main-net launch: fiat payment integration
- Legal groundwork in preparation for main-net launch: KYC/AML framework
- Alpha maintenance

**Phase 2: Aug - Nov 2019; CHF 363,000**

*Main Milestones:* 

###### Development & open sourcing of mobile & desktop interface ######

- remodel Ash interface as generic version for mobile
- develop generic Ash interface version for desktop
- set up a design system 
- documentation
- published on Github

###### Development & open sourcing of Giveth module #######

- module to invest in the Giveth DAC
- documentation
- published on Github

###### Ash Hackathon ######

- topics: interface integration & module development 

*General Development:*

- Copy-trading module R&D
- Multi-Manager Funds module R&D
- Challenge module & XP token R&D
- Development of fiat payment integration
- Legal groundwork in preparation for main-net launch: social trading license Lichtenstein/United Kingdom
- Beta maintenance


**Phase 3: Dec 2019 - Mar 2020; CHF 363,000**

*Main Milestones:* 

###### Development & open sourcing of Copy-trading module ######

- module to enable Melon funds to invest in other Melon funds
- documentation
- published on Github
- security audit

###### Development & open sourcing of Multi-Manager funds module ######

- module to enable multiple managers per Melon fund
- documentation 
- published on Github
- security audit

###### “Beta Season” Tournament ######
 
- running on Kovan 
- fiat payments for challenge fees

###### Report on legal situation of Melon-based apps ######

- licenses, jurisdictions, categorization

*General Development:*

- XP token & challenge module testing
- R&D for technical implementation of KYC/AML integration
- Prediction market feasibility study:
- integration tests 
- result documentation 
- Beta maintenance



## 2 Treasury Management ## 

The sell schedule for the granted MLN is aligned with the funding and milestones schedule. To secure our round one funding needs, we have started to think about how to place an OTC trade for the entire first slice (CHF 364,000) of MLN with interested parties. We believe that with the help of our advisor (Mona El Isa) we will be able to place these at a discount to OTC market with 2-3 protocol-based hedge funds who are long term holders. In accordance with the start of the second part of the funding schedule, we will start selling MLN from August on exchanges in order to cover our monthly burn rate as well as additional costs. Depending on the market situation at that point, we will consider further OTC negotiations in a timely manner. 

- April 2019: **CHF 364,000 one time via OTC** 
- Aug. - Nov. 2019: **CHF 90,750/month** via exchanges or OTC
- Dec. 2019 - Mar. 2020:  **CHF 90,750/month** via exchanges or OTC

In the case that the MLN price decreases heavily by mid of 2019, we will decrease costs to a minimum that allows the maintenance of the Beta. Further, we will try to ensure the conduction of the necessary sales via OTC.



## 3 Contributions to the Melon Protocol & Ecosystem ##

### a. Usage & Deflation ###

By providing a new innovative use-case to Melon, our goal is to expand the user base and actively increase the MLN engine burn rate. With retail investors as our target group, the Ash prize pool works as an incentive mechanism to drive broader adoption. The more users play challenges, the more challenge fees are paid to an increasing prize pool that again attracts new users. Each fee function called changes “Melon gas”. Midas Technologies AG will provide an initial amount for the prize pool kick-off and foresees the Beta Season Tournament on Kovan in Q1 2020, with at least 1,000 Beta testers (of which ca. 500 already have signed up - documentation on request). With user recommendations and marketing & community initiatives during the tournament we deem it realistic to gain another 2,000 users for the main-net launch, making a total of 3,000 signups on main-net in year two. Our assumption is that every user joining Ash will use the Melon smart contract functions *setupFund*, *requestInvestment* & *executeRequest*, at least once to open a fund and make an initial investment. In addition to that there is a reasonable amount of follow-up investments included. This is a conservative calculation taken from Melonomics 2,  depending on the crypto market situation, user numbers/actions can increase significantly faster. 
Based on the Melonomics 2 calculation for Melon smart contract functions and the current amgu price, we calculated the potential amgu consumption rate per user for three years as follows:

*Costs of Melon smart contract functions:* 

*setupFund* requires approx. 3,490,520 amgu (1x/year)
*requestInvestment* requires approx. 202,196 amgu (10x/year)
*executeRequest* requires approx. 281,133 amgu (10x/year)
*redeemAllOwnedAssets* requires approx 38,547 amgu (3x/year)
 
*Calculation per Melon fund/user:*
3,490,520 + (10 * 202,196) + (10 * 281,133) + (3 * 38, 547) = 8,439,451 

In year 3 there is an additional amount of amgu generated by the 3000 users that signed up in year 2 which are not setting up a new fund but keep performing basic actions like invest and redeem:
(10 * 202,196) + (10 * 281,133) + (3 * 38, 547) = 4,948,931

*calculation from Melonomics 2, applied to projected Ash user numbers

Please follow [this link](https://docs.google.com/document/d/1neEH-jekoz1NzCINVdH2v8Ze3ud1tHKQCH0rfIVKdkI/edit?usp=sharing) to see calculation table A


An additional driver for the Melon engine can be the transition of the challenge functionality from our back-end to a module which manages challenges on-chain. Through this module, a slice X can be taken from every challenge fee and forwarded to the Melon engine. In our first two weeks of Alpha testing we had 25 people invited ie. 25 Melon funds were created on Kovan. Despite very low liquidity on Kovan and some initial bugs and downtimes, an average of three challenges were played per person, per day. 
According to this average and an assumed price of **50,000 amgu/challenge** we calculated the potential amgu consumption rate for challenges in three years as follows:

Please follow [this link](https://docs.google.com/document/d/1neEH-jekoz1NzCINVdH2v8Ze3ud1tHKQCH0rfIVKdkI/edit?usp=sharing) to see calculation table B


We expect to be able to continue running the competitions for a minimal fee for maintenance and marketing which should help expand these numbers further from year 3 onwards.


### b. Open Source Development & Legal Research ###

Apart from bringing usage to the Melon protocol and thereby trigger the MLN deflation mechanism, we contribute to the ecosystem by open sourcing our development milestones, namely: 

- Copy-trading module: enables users to invest in other Melon funds. This protocol-level  feature is an elementary building block of financial instruments/fund management and will add one further key function to the protocol. 

- Multi-Manager module: enables users to manage Melon funds as a group. This feature can mitigate key-person risk, and enables the integration of policies, procedures, roles and responsibilities into the protocol. Further, retail investor groups like families get the chance to share the management responsibilities of their funds. 

- Generic Melon interface for mobile and desktop: thrives adoption and development of new apps on top of the protocol by making it trivial to modify existing modules or add new modules to the interface system to fit the apps domain logic.

- Giveth module: enables users to invest in DACs on Giveth and allows to turn mixes into impact investment funds by investing in NGOs or charity projects. 

We further invest in the legal research and strategy to offer Melon protocol functionalities to retail investors. Our approach is to embed Melon protocol functionalities into the legal framework of social trading (at the moment we focus on Lichtenstein in that matter).






*to see this proposal with all included graphics please visit:
https://medium.com/ash-blog/proposal-for-a-token-application-event-to-the-melon-council-5ed2cc4eefd5

## 1 What this Proposal is about ##

With Melonport having introduced the concept of Melonomics, projects building on top of the Melon protocol receive the possibility to apply for Melon tokens or conduct a token swap for project funding. The purpose of this is to improve network effects and align interests across asset management 3.0. The Ash team sees extensive benefits in this approach and decided in July 2018 to renounce its Token Generation Event plans in favour of proposing a Token Application Event (TAE) to the Melon Council.

In Melonomics I, II and III, the former Melonport team has laid out the necessity of aligning interests, while simultaneously rethinking tokenomics in order to create long-term value which is directly linked to the usage on the Melon network. The concept enables projects to get funded by the Melon inflation pool. Ash is hereby applying to the Melon Technical Council for this process in order to receive funding for one year of product development.




## 2 Who We are and What We do ##

The company behind this proposal is Midas Technologies AG, software developer based in the Crypto Valley Zug, Switzerland. We are currently 8 people working full-time on the development of our main product: Ash. Ash is an investment app for retail investors that gamifies investing. We use the Melon protocol to provide our users with a decentralized investment fund. This cuts out middlemen in asset management and grants full control to the end users. Building on the Melon protocol, Ash takes a playful approach to investing and focuses on maximum usability, two of the so far neglected elements in the crypto and investment space. 

On Ash, every user creates an asset mix (Melon fund) on the blockchain that can be used to invest in all sorts of crypto assets as well as in other users‘ asset mixes on the plattform. Ash allows users to mix different asset classes and freely create portfolios of their individual liking. All this can be done in the simplest way: tap, set the amount, done. 


New users can pick profitable asset mixes to invest in directly from our ranking. This way, skilled users get the chance to monetize their fund management talent even if they run a mix with little AUM. To achieve this, we use gamification and competition and rank users according to their performance. Every user is assigned to a level that can be increased by engaging in challenges in the VS mode and comparing asset mix performances over a period of time. To play challenges users have to pay a small fee (the only fee on Ash apart from gas and amgu) that gets collected in the rewards pool. Users with the highest levels and best mix performances are entitled to payouts from this rewards pool. In order to stay on top of the ranking and receive rewards, users have to constantly engage in challenges and show their asset management skills by running a profitable mix. 



## 3 The Team ## 

<dl>
  <dt>Adrian Gallo, Co-founder & CEO</dt>
</dl>
Passionate entrepreneur and investor with broad academic and practical background in International Management and Finance. Has been working as professional stock day-trader for over ten years and acquired proficient knowledge of market functionalities and risk management.

<dl>
  <dt>Konstantin Trott, Co-founder & COO</dt>
</dl>
Studied Cultural Anthropology and has a communication agency background. Has gathered experiences in communications and project management at Edelman, FleishmanHillard, Continental and most recently Bosen AG, where he was also the research lead for blockchain technology business models.

<dl>
  <dt>Philipp Doğan, Co-founder & Product Lead</dt>
</dl>
Was the Chief Strategy Officer at security startup Bosen AG, building and managing industrial counterintelligence solutions. Also at Bosen he was in charge of the R&D for financial services on the blockchain.

<dl>
  <dt>Lukasz Wolniak, Product Designer</dt>
</dl>
Gifted UI designer with an outstanding feeling for visual experience. Has been working on award-winning UI concepts for Ericsson and was responsible for app design at banking app Numbrs.

<dl>
  <dt>Moritz von Below, UX Architect</dt>
</dl>
Gathered extensive experience as technical project manager and team lead working for international brands like Hyundai, Kia, Maserati and Bose. Responsible for UX-driven concept development and creation of convincing and authentic digital brand experiences.

<dl>
  <dt>Kunal Sachdeva, Front-end Developer</dt>
</dl>
Enthusiastic technologist from India with expertise in cross-platform application development. Ex-ThoughtWorker and has worked with startups from all over the world. 

<dl>
  <dt>Thomas Bach, Back-end Developer</dt>
</dl>
Academic background in IT and Physics and has been working as full stack developer with skills in Java, Javascript, C++, Scala, Haskell and Pascal. Thomas managed several ERP projects and was responsible for back ends of multiple network and cluster systems. 

<dl>
  <dt>Timon Kritenbrink, Information Security Engineer</dt>
</dl>
Long-lasting expertise in automation and security for industrial IT, always striving for top-notch security solutions. 




## 4 Our Advisors ##

<dl>
  <dt>Mona El Isa, Melonport AG</dt>
</dl>
Former star-trader at Goldman Sachs, promoted to Vice President by the age of 26 and made the “top 30 under  30” list in Trader Magazine in 2008 and Forbes Magazine in 2011 after profitably trading the 2008 and 2011 crashes. Moved to Geneva-based macro fund Jabre Capital in 2011, before deciding in 2014 that the future of finance lay in blockchain technology. She studied Economics & Statistics at the University College London.

<dl>
  <dt>Reto Trinkler, Trinkler Software AG</dt>
</dl>
Blockchain developer with extensive background in mathematics from ETH Zurich. He started developing Ethereum smart contracts immediately after their launch in 2015. He worked as a smart-contract developer at Brainbot Technologies (which is building the high-speed Raiden Network) and is host of Zurich's Blockchain Hacklab. Reto is co-founder of Melonport AG as well as Trinkler Software AG where he is currently building Agora, a cross-chain, non-custodial, cryptocurrency exchange. He was appointed one of the “Top 30 under 30” by Forbes Magazine in 2018.


<dl>
  <dt>Thomas Linder, MME Legal | Tax | Compliance</dt>
</dl>
Thomas Linder joined MME in 2015. He is particularly specialized in leading interdisciplinary projects and has in-depth knowledge in cross-border transactions and tax accounting. At present, he mainly provides assistance to companies in the technology sector, with a focus on blockchain technology and international projects.




## 5 The Mission ##

In order to provide a low barrier entry point and ensure a fast and secure product we need a stable protocol as basis. At the same time the Melon protocol needs users and popular applications running on top of it, to maintain traffic and incentivize people to its development and optimization. 

While the Melonport team worked out complex technical challenges of setting up a decentralized fund management infrastructure, our team set off to build an interface that provides users with easy access to this infrastructure. On one side this means guaranteeing maximum usability (also for users unrelated to the fund management industry) and adding attractive functionalities. On the other side it means providing a safe legal framework for our users.




### 5.1 How we bring Value to the Melon Ecosystem ###

After the development and security auditing of the Melon protocol is completed, the Melon ecosystem is depending on one key element: usage. Our mission is to create a captivating mobile UX and gamification mechanics around Melon in order to drive user adoption. 
<dl><dt>All asset mixes on the Ash app are actually Melon funds on Ethereum.</dt></dl>
This creates a direct link between the app’s usage and the Melon Engine. Usage of Ash will automatically increase MLN deflation and thereby contribute to the MLN price (detailed information about the Melon Engine and MLN deflation in Melonomics II).

The key elements of Ash that enhance Melon are namely: 

<dl>
  <dt>Mobile Interface</dt>
</dl>
To lower the entry barrier to the Melon protocol we created an easy to use mobile interface on top of the protocol, which includes a service layer for a seamless user experience.
Tracking and Notifications
When a user invests in a mix, Ash automatically tracks actions of that mix and notifies the user when trades are conducted. This way, users always stay on top of what’s happening on the market and with their money.

<dl>
  <dt>Competition</dt>
</dl>
Competition between managers weed out bad funds and highlight the best performing funds. This way, inexperienced users can rely on top-ranked funds and profit from their strategy.

<dl>
  <dt>Rewards pool</dt>
</dl>
The rewards pool incentivizes users to steadily improve their performances. The competition and level system auto-pays the best fund managers on the platform with the collected fees from the rewards pool. 

<dl>
  <dt>Fiat payment integration</dt>
</dl>
A key point is lowering entry barriers for new users by providing simple ways to stack a fund with fiat. This eliminates the need to operate a wallet, own crypto or even know much about it before creating  an asset mix on Ash. 

<dl>
  <dt>Impact investing</dt>
</dl>
Giveth is re-engineering charitable giving, by creating a free, open-source platform, built on Ethereum. Integrating Giveth into Ash enables every user to connect their fund to a charity or NGO and transform it into an impact investment fund.

<dl>
  <dt>Prediction Markets</dt>
</dl>
Providing users with the possibility to create prediction markets through Ash and hold PM positions in their mixes, we give users the power to create their very own asset classes. Apart from markets on politics, economy or sports, users can create predictions on challenges between Ash users and thereby intensify the app’s gamification experience.




### 5.2 What we did so far ###

#### 5.2.1 Incorporation and Funding ####

The concept development of Ash started back in February 2017. We incorporated in Switzerland and hired renowned law firm MME to help us being compliant with Swiss regulations. We participated in the M-0 Conference in Zug in October 2017 where our CEO Adrian presented our vision for Melon on mobile for the first time.
 
Finally in early 2018, our team was joined by advisors Mona El Isa (Melonport AG), Reto Trinkler (Trinkler Software AG) and Thomas Linder (MME). We began to foster collaborations with other projects like Gnosis and Giveth and built “eazyX”, an interface to the DutchX decentralized exchange. 

We have always been critical about means to an end token models which result in unnecessary utilities. Especially when we saw how the ICO market took off and projects raised millions without any due diligence or serious attempt to actually deliver. Due to regulatory uncertainty we postponed our ICO/TGE for a revenue-sharing security token multiple times and are privately funded since day one.

With the introduction of Melonomics we can apply for a reasonable funding opportunity that will hopefully be surpassed by the value that we contribute to the overall Melon network. Our proposal for a TAE thus is the next logical step in the creation of a product to push the Melon ecosystem forward. 




#### 5.2.2 Completed Development ####

The following overview shows the positions we have committed since November 2017￼ (time of incorporation) to realizing the first app on Melon. The technical development started during spring 2018 when the team was joined by our product designer and front-end developer. Apart from the core team, we worked with several freelancers during 2018.

- Gross Salaries & Infrastructure: 431'273.30 CHF -  66.51%
- Fees for recruiting developers:   55'924.31 CHF -   8.62%
- Legal assistance & maintenance:   58'645.45 CHF -   9.04%
- Travel costs: 	            31'032.73 CHF -   4.79%
- Marketing & Branding:             15'083.65 CHF -   2.33%
- Banking & Accounting:             23'336.44 CHF -   3.60%
- Office costs & Supplies:          33'111.80 CHF -   5.11%

- TOTAL:                           648'407.68 CHF-  100.00%

By the time of this proposal the following elements have been completed:


<dl>
  <dt>Back end</dt>
</dl>

- Continuous integration and deployment pipelines
- Distributed microservices system 
- Fanout system
- Persistence layer
- In-memory data store
- Ethereum logging and caching service
- Infrastructure-as-code framework

<dl>
  <dt>Front end</dt>
</dl>

- UX architecture 
- Design and development of the front end codebase
- News feed 
- Asset mix management interface
- Tinder-style swipe interaction to buy/sell assets
- User/user challenges to compare fund performances
- Challenge status pages
- User profile
- Asset mix profiles
- Asset info pages
- Gamified level system
- Aggregated search for the decentralized exchange modules in Melon funds 
- User avatar qr code system for scan-to-challenge interaction
- Wallet integration
- Melon js integration to connect to Melon protocol on Kovan testnet 

<dl>
  <dt>Preparation of Alpha Testing</dt>
</dl>

- A running test app on mobile that is connected to Melon on the Kovan testnet and allows testers to buy and sell assets and compete in challenges (Ash Alpha will be released shortly after the submission of this proposal)
- Tester invitation list of around 150 individuals and reputable projects 

<dl>
  <dt>Preparation of Open Beta</dt>
</dl>

- Running on Kovan: you can sign up already! Please feel free to join and give us some feedback :) Beta signup via -> https://ash.finance




### 5.3 Next Steps ###

#### 5.3.1 Development ####

<dl>
  <dt>Beta Tournament</dt>
</dl>
Running the Beta and performing ongoing iterations on the interface and service layer based on user feedback.

<dl>
  <dt>Fund-of-funds interface</dt>
</dl>
A fund-of-funds structure allows a user to invest with her Melon fund in another user’s Melon fund, which again can invest in another Melon fund and so on. To provide this feature, a Melon fund needs to integrate a module that enables this kind of transaction. 

<dl>
  <dt>Multi-Manager-Funds module</dt>
</dl>
This module allows users to get together in groups to manage funds and invest in a joint endeavour. Depending on the settings of a MMF, decisions about investments are made via voting.

<dl>
  <dt>Fiat payments integration</dt>
</dl>
To lower the entry barrier, for everyone with a smartphone to be able to operate their own investment fund on the blockchain we need to integrate fiat payment options. Connect a fiat payment method and create your asset mix. This will eliminate the need to set up an external wallet, buy crypto and send it to your mix.

<dl>
  <dt>Challenge module</dt>
</dl>
In the Alpha, challenges between users’ asset mixes are handled completely in our back end. The next step is to create a module that handles challenges on-chain and sends a small fee to the rewards pool every time two users engage in a challenge.

<dl>
  <dt>XP Token</dt>
</dl>
Since we will move our challenge system on-chain, we will also migrate the XP points for the level system on-chain in the form of an XP token. There will be no ICO for this token and we will airdrop it for free to every new signed-up user on our platform. We will not engage in any efforts to list this token on any exchange because it is purely to track the XP points of each user on-chain. The XP token will not have any functionality except that users stake it in challenges and keep track of their individual levels. All of this is automated and happens behind the scenes without the need for any user interaction. For the user this is simply her XP, it increases with won challenges and decreases with lost challenges.

<dl>
  <dt>Security audits</dt>
</dl>
We cannot stress this enough: security is key! External security audits are the way to go.

<dl>
  <dt>Giveth Integration</dt>
</dl>
To provide users with a simple way to transform their mix into an impact investment fund we need to integrate a module that enables connections of a Melon fund to the Giveth smart contracts, so users can browse through NGOs and charity projects, connect them to their mix and setup a one time donation or a standing order to create a true impact investment.

<dl>
  <dt>Research on Prediction Markets module</dt>
</dl>
In order to provide our users with the possibility to create or engage in PMs we need to build a module that connects to a decentralized PM platform like Gnosis or Augur. 




#### 5.3.2 Legal #### 

<dl>
  <dt>License and compliance</dt>
</dl>
Melon is bleeding-edge technology. Existing regulations for the global asset management industry have difficulties to categorize technology-regulated solutions like Melon or applications running on top, like Ash. Due to the international fragmentation of regulations, we move forward in several steps, starting in one jurisdiction, to then expand from there.

- Set up Ash with a social trading license in Liechtenstein which applies to all users within the European Union
- Set up Ash with a social trading license in the UK that applies to all users within the United Kingdom

<dl>
  <dt>KYC/AML</dt>
</dl>
In order to comply with Know-Your-Customer and Anti-Money-Laundering regulations we will integrate a KYC procedure that identifies every user before using Ash with real funds. 




#### 5.3.3 Community & Marketing ####

<dl>
  <dt>Events & Networking</dt>
</dl>
Organizing workshops/hackathons and tournaments for the Ash community.

<dl>
  <dt>Rewards</dt>
</dl>
MLN rewards for the first Beta sign-ups to secure a solid user number by time of the Beta launch.

<dl>
  <dt>Communications</dt>
</dl>
Maintenance of social media channels like Twitter and Telegram, to inform users and create an appealing digital brand experience for the community. Ash Medium blog about development progress, important partnerships as well as open source activities. 




## 6 Timeline ##

<dl>
  <dt>Q1 - Q2 2019</dt>
</dl>

- Token Application Event Proposal
- Start of the closed Alpha 
- Iterations on back and front end with feedback from Alpha testing
- Adding new features for Beta
- Start of the open Beta 

<dl>
  <dt>Q3 2019 - Q1 2020</dt>
</dl>

- Setting up licenses for EU and UK regulatory compliance
- Preparation of marketing campaigns
- Host hackathons and workshops for asset management on Melon protocol
- Organize tournaments for Beta testers to grow the community
- Continuous feedback and iterations during the Beta to refine and add features (listed in 5.3.1)




## 7 What we need from the Community ##

The following numbers cover project funding until Q1 2020.

<dl>
  <dt>CHF 650.000 Product Development (59,6%)</dt>
</dl>

- 6 full-time product developers (already hired): front-end, back-end, product design, UX design, prototyping, user research
- 1 additional full-time developer for front end (needs to be hired)
- 2 management full-time positions for communications, finance, compliance, regulation & licensing and investor relations (already hired)
- security audits 

<dl>
  <dt>CHF 250.000 Legal (22,9%)</dt>
</dl>

- legal consulting for trading/investing/operating licenses
- set up of legal entities related to trading/investing/operating licenses
- application for and acquisition of trading/investing/operating licenses 
- ongoing legal consulting 

<dl>
  <dt>CHF 90.000 Community & Marketing (8,3%)</dt>
</dl>

- distribution of MLN rewards to the first 1000 Beta testers (CHF 40.000)
- organization of Ash hackathon
- Ash beta tournament
- travels & events
- marketing campaigns

<dl>
  <dt>CHF 50.000 Administration & Maintenance (4,6%)</dt>
</dl>

- office costs & rent
- book keeping & banking
- work related materials 

<dl>
  <dt>CHF 50.000 Contingency (4,6%)</dt>
</dl>

- any unforeseen costs

<dl>
  <dt>TOTAL: CHF 1.090.000</dt>
</dl>




## 8 Additional Sources of Information ##

Website: https://ash.finance

Github: https://github.com/Midas-Technologies-AG 

Medium: https://medium.com/ash-blog

Twitter: https://twitter.com/ash_app

Telegram: https://t.me/ash_app

Email us: hi@Ash.finance
