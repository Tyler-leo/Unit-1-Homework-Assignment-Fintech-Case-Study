# Unit-1-Homework-Assignment-Fintech-Case-Study WealthSimple
## Overview and Origin

  * Name of Company
    * Wealthsimple 
  * Incorporated
    *  September 2014, in Toronto
* Who are  founders of the company?
  *  Michael Katchen - [linkedIn profile](https://www.linkedin.com/in/mkatchen/?originalSubdomain=ca) - was the original founder, however in 2015 Wealthsimpe merged with _Canadian ShareOwner INvestments inc._ Making wealth simple one of Canada's 14 larges discount brokerages across Canada.
* How did the idea for the company (or project) come about? the "flash of genius"
  * Before the founder, Michael Katchen, started Wealthsimple he worked in silicon valley at a company called 1000Memories.  In 2012 1000Memories was purchased by Ancestry.com, subsequently Mr. Katchen created a spreadsheet with tips (essentially a Robo-Advisor) to help his fellow workers invest there profits and create portfolios for them.
* How is the company funded? How much funding have they received?
  * Currently the company completed its last funding round as of May 2021. For the funding round the valuation was set at $ 5 billion dollars, the total collection of funding during tha round was _$610.4 million_.  To do date a total of _$830.9 million_ has been procured during funding rounds. [Source: Craft](https://craft.co/wealthsimple/funding-rounds#:~:text=Wealthsimple%27s%20latest%20funding%20round%20in%20May%202021%20was,latest%20valuation%20is%20reported%20to%20be%20C%245%20b.)

    ### Total Funds colllected to date as follows
      * Series A -     April 2015 - $24.2 million
      * Series B -     April 2017 - $20 million
      * Unattributed - May 20117 - $37 million
      * Unattributed - Feb 2018 - $86.8 million
      * Unattributed - Oct 2020 - $86.8 million
      * Unattributed - May 2021 - $610.4 million 


## Business Activities

* What specific financial problem is the company or project trying to solve?
  
  
   The main financial problem they are trying to solve is the barrier to entry for begining or occational investors. Most first time investors are either intimidated by the market, or dont have enough capital to even get a reputable fund manager to consider taking on their portfolio.  _WealthSimple_ address both of these barriers to entry.  
   
   The first paragragh of their mission statment is as follows. "Wealthsimple is on a mission to help everyone achieve financial freedom by providing products and advice that are accessible and affordable. We take financial services that are often confusing, opaque, and expensive and make them simple, transparent, and low-cost."
   
    The company has intnetionally incldued their main goall in their Name "_Wealthsimple_". The main target of the company is to make investing, and managing wealth easier for everyone, not just for the select few.  _WealthSimple_ is striving to remove real and percievded barriers of entry into the markets, by providing intuitive financial products with as little as $1.00 to start an account.   

   The main reason Michael Katchen founded the company was to help his collegues, at the time , with a simple but smart spreadsheet to help them increase their returns without the burden of financial managment fees.   The companies vision has not changed since its inception, however the scale of dollars under management, and Robo-advisor technology has advanced significally.  

* Who is the company's intended customer? Is there any information about the market size of this set of customers?

The intended target martket would be Millennial focused ("people born between 1981 to 1996"[Source millennials](https://en.wikipedia.org/wiki/Millennials)), more specifially professional miillaenn types with a passive investment style.  They have created a sleek, clean modern desing that has attacted this segmant of the market, who want to "park" their money into a well reasearced investment product that will bring them steady returns.  

_WealthSimple_ is targeting passive investors who are looking for reasonable and consistant returs.  Most of their products are based on index funds or ETF's that reduce the overall rik by spreading their capital across mutiple comapnines. They have a focus of managing cusotmers RRSP's, RESP'S and TFSA's - with most companies switching their pension funds to self directed, this opens up a large market for _WealthSimple_ to aquire. They have eliminated fees for the the first $5,000.00 invested, hoping to attract Millinial Canadians who havent started their investiment journey yet.

Millennnials in Canada make up 1/4 of the population, and are the largest segment in the labour force.  The currently hold over $824 billiion in assets.  With 4 in 5 saving and only 1 in 2 investing - the potentially for growth in our market it substantial.

*  What solution does this company offer that their competitors do not or cannot offer? (what is the unfair advantage they utilize?)

There main competitor's in Canada are larger banks and smaller discount brokerages.  The main competitive advantage is how simple the platform is to use.  The stigma behind banks, and discount brokerages, is how difficult or how much knowledge you need to start an account and handle it basically on your own. _WealthSimple_ has postitioned itself as an easy to use, if not fun platform for people to start using with little or no knowledge to start out. They also mutilple teaching tools to help people educate themselves on the platform with regards to inviesting.  They have numerous article, and a helpful customer service team that quickly can help and implement thier financial products.  Not only does the service team help you set everything up, they are willing to take the time to explain what the products are and why you would want to use them specifically.  The website and mobile app have been purposely designed for a "simple" and easy user experience.  The big banks, and majority of discount banks currently don't have this advantage. The banking apps are getting better, however they are still more and complex then the user friendly system set up currently with _WealthSimple_.

* Which technologies are they currently ussing, and how are they implementing them? 
  * WealthSImple uses 30 Technology products ([Source: Crunchbase](https://www.crunchbase.com/organization/wealthsimple/technology)) an example of some of the porducts include:
   
    * **Rails Engines** - previous system used for depositing funds and moving assets was the *Ruby on Rails* service.  "This system was developed and piecemeal over several years with mutiple major feathers added in close succession.  For our Rapidly growing number of clents, everything was running smoothyl.  Under the hood, however, we sensed things were starting to get a little complicated." ([Source:Tidiying up with Wealthsimple](https://medium.com/wealthsimple/tidying-up-with-wealthsimple-355d006ea70c))  The solution was "Rails Engines", the application acted like a "supercharged" engine, simplifying the complications "under the hood".  Allowing customer transactions to not be interupted as the company scaled and grew at a fast pace.
    * **Kafka** - This is a distrubuted streaming platform used to publish and subscribe streams of records.  They old platform "environment was a mulit-tenant cluster and had limits on partitions and throughput that we knew wouldn't scale with our needs." with higher  customer demands they had to upgrade their platfomr to scale the system to meet these needs.  Kafka was migration took place 2021. ([Source: New Kafka Tier, No Kafka Tears
    ](https://medium.com/wealthsimple/new-kafka-tier-no-kafka-tears-95b1cbe7d15c))
    * **Typescript** - is programming language used to develop Javascript. _WealthSimple_ switched from the flow program language.  "Painpoints with grew with Flow, it became clear that we would need to migrate."  *Typescript* provided more third party libraries, and is more user friendly. "*Typscript*, it seemed like fixing these errors manually, all 3,000 of them in just one of our services." ([Source: Migratign to TypeSCript without Migraines](https://medium.com/wealthsimple/migrating-to-typescript-without-migraines-845613cd7ded))
    * **Security Tech: 256-bit SSL Certificate** -this is a technology that encrypts and decrypts a 256 bit key that is transferred between the client and the server. _WealthSimple_ uses this technology on their web servers between their customers web browesers to encrypt and safely transfer importatnt data ([Source: How does Wealth simple handle security and encryption?](https://www.wealthsimple.com/en-ca/learn/security-encryption#:~:text=Encryption%3A%20We%20use%20state%20of,including%20passwords%20and%20personal%20information.))
    * **Jquerry** - " A well-written Javascript code", used for the webpage for easy front end development. ([Source: Educba](https://www.educba.com/what-is-jquery/))
 

## Landscapes

* What domain of the financial industry is the company in?

_WealthSimple_ as a companie crosses many domains e.g open bnaking, wealth managment ect.. however the main domain the company in in **Robo-Advising**, which was what the company was originally founded to do. 

* What have been the major trends and innovations of this domain over the last 5-10 years?

Over the last 10 years there has been a cultural shift with customers not wanting to interact with people at business's.  Rather than calling directly and talking with someone at a buisness, customers would rather ask on the website, send in a ticket or email to get their answers for their inquiries.  This has been a major advantage in progression for the domain of Robo-Advising.  People are gettting more and more comfortable allwoing their investments for retirement, schooling, homes ect.. to be handled by 

In the last 5-10 years more and more companies have switched thier pensions to a "self directed pension plan".  Essentially these pension funds puts you in control of your investments for retirement.  Most people that invest are passive vs active investors - Robo-Adising has been an ideal solutions for passive investors.  This product, as disccussed earlier, allows investors to answer a few simple questions to assess their investment styles and individual risk tolerances.  The product in turn invests and diversifies the cusotmers portfolio, with the overall goal to balance the risk and returns that the clients are comfortable with.

Customers are becoming more aware of how fee's are eating away from their overall returns.  Allot of mutual funds or invesment managers charge front-end , bank-end, and ongoing fees that eat away at a customers returns over the invesments life span.  Robo-Advising reduces this fees substantially, they tend to invest into Index funds and ETF's which subsequently reduces the overall fees.  In basic terms Rob-Advising allows a customer to essentially "cut out the middle man".

The younger demographics that are growing up are becoming more and more comfortable with technology. The majoirty of customers are becoming more savvy with technology, and more willing to try new forms of customers service and experiences.  15-20 years ago customers would be more resistant to technology, and more willing to talk to advisors over the phone or in person.  

*  What are the other major companies in this domain?
   * [M1 Finance](https://m1.com/) - Founded as a Robo-Advisory platform in April 2015 and is located in chicago.  $6 Billion in assets under management.
   * [Robinhood Financial](https://robinhood.com/us/en/) - Founded April 2013 as a way for investors to access the markets with minimal fees.  As of 2021 there are 31 million users.
   * [Ellevest](https://www.ellevest.com/#/) - Founded in 2014 with a focus target market for women in finance.   Assets under management $1 billion 
   * [Personal Capital](https://www.personalcapital.com/?variant=sticky-nav) - Founded in in 2009, but changed its name in 2010.  Headquaters loacted in Reedwood Shores CA, and has an asset under managment of $21.9 billion.
   * [Wealthfront inc.](https://www.wealthfront.com/) - Founded in 2008 in Redwood City, California.  Assets under managment $15.85 billion.
   * [Sofi autmoated Investing](https://partners.sofi.com/gen-invest-robo/?irgwc=1&clickId=T2HzLXV-GxyIUYvSowSpp0KmUkDxq5XUEwzbUA0&adId=844867&adName=SoFi%20Robo%20Advisor&partnerId=102401&partnerName=Linkoffers%20Inc.&adTarget=wealth&partnerType=Affiliate&adDepartment=BD&sharedId=39258) - Investment and online bank founded in 2011 with headquaters in Sanfrancisco, California.  Assets under managment $9.1 billion.
   *  [Betterment](https://www.betterment.com/affiliate-partner-offer?clickid=2pBUZXQVkxyIR5E2d%3A2cd0vRUkDxq%3AQIEwzbUA0&utm_medium=affiliate&utm_source=1955282) - Founded in 2008 by roomates from Columbia business school, Co-founders comprosed of two alumni. One was  lawyer and the other partner a Google softere engineer, they combined their expertise to creat an investment based company. Headquateres are located in New York, New York.  Assets under management $33 billion.
   * [Sigfig Wealth Management](https://www.sigfig.com/site/#/home/am) - Founded in 2007 in Sanfrancisco Californa, with assets under management of $1.4 billion.
   * [Schwab intellegent portfollio](https://www.schwab.com/intelligent-portfolios) - Founded in January of 2020 with headquaters in Westlake Texas. The total company has $8.14 Trillion in assets - no specific numbers found for the intellegent portollio AUM.
   * [Axos](https://www.axos.com/invest/?) - Founded in Jully of 1999, headquarters located in Las Vegas, Nevaded.   Assets under management $14..4 billion.

 ***Source material Company info found*** -  [Assets under managent  and Headquarters Wikipedia](https://en.wikipedia.org/wiki/Main_Page) 

 ## Results

 * What has been the business impact of this company so far?

 _WealthSimple_ has proven itself to be a large competitor in the *Robo-Advising* domain, attracting new investors at a substancial rate. As a result of the pandemic, the industry has seen a rapid growth in customers wanting to exit high priced mutual and managment run funds.  In 2020 alone "Wealth simple already saw an increase in new investors by 24%" ([Source Wealtsimpel Inc Swot & Pestle Analysis](https://www.swotandpestle.com/wealthsimple-inc/#:~:text=The%20mission%20statement%20of%20Wealthsimple%20reads%2C%20%22Our%20mission,financial%20products%20for%20everyone%22.%20Wealthsimple%20Inc.%20Revenue%20%3A)). 2021 saw the company evalued at $5 billion during an investment round, which attracted celebrities like Micheal J Fox, Drake, and Ryan Reynolds.  

In January of 2021 _WealthSimple_ was ranked as the number one app on the Canadaina apple App store, and remained in the top 10 until march 2021([Source Wealthsimple Trade in-depth review](https://www.moneysense.ca/save/investing/wealthsimple-trade-review/)).  Since its initial inception with less than 1,000 users, _WealthSiimple_ has grown to over 1.4 million users.  The impact on the industry, has been substantially in the last 8 years.  In the peroiod of 2020 to 2021 _WealthSimple saw a user growth of 1,000%.  During the first half of 2020, 18% of all brokerage accounts were _WealthSImple_ accounts ([Source: Insider intellegence](https://www.emarketer.com/content/wealthsimple-secures-another-mega-raise-3-7b-valuation))  With monthly app downloads in the last 30 days of **189,867 apps** and **4,937,319 website views**, the company is poised to continue to grow ([Source: Crunchbaase](https://www.crunchbase.com/organization/wealthsimple/technology)).

* What are some of the core metrics that companies in this domain use to measure success?  Howe is you company perfomring, based on these metrics?

The main or core metric the financial *Robo-Advisor* domain would use as a performance tool would be Assets under managment and number of users. Please see table below for metric breakdown of major competitors:


|   Company   |   Assets Under Management   |  Users  
| --- | --- | ----|
WealthSimple   |   $15 billion   | 1.4 Million
M1 Finance   |   $6 billion   |  500 000
Ellevest | $1 billion | 120,000 
Personal Capital | $21.9 billion | 800,000
Robinhood Finanancial | NA | 31 Million
Wealthfront Inc. | $4.6  billion | 100,000

Comparing the metrics _WealthSimple_ has a healthy AUM when compared with competitors, however there is room for growth in the U.S market.  As noted by the amount of users on the Robinhood Financical platform, there are opportunityiers to expand and grab market share towards their platform. [Source: Wikipedia](https://en.wikipedia.org/wiki/Main_Page).

* How is your company performing relative to competitors in the same domain?

When comparing current market allocation with regrads to users and assets under management, _Wealthsimple_ is one of the top performers when comparing the data.  This is promising, there is roof to grow and they have give "proof of concept" that their current buisness model is working.  After analyzing data across competitors in our Canadian market, _WealthSImple_ is competing with U.S companies in a much larger market space.  The competitors in the U.S do have the advantage of larger population and customer base - however in this domain there really are no borders anymore.   _WelathSImple_ has focused on the Canadian market and stilll has been successfully competing with its counterparts in the states.  The future looks bright, there is a hugh opportunity in the U.S and worldwide larger market place, _WelathSimple_ has the right  posittion to expenentially expand its customer base and AUM in the near future.

## Recomendations 

* If you were to advise the company, what prodcuts or services would you suggest they offer? (This could be something that a competitor offers, or  use your imagination!)

If I were to advise on a new product line for _WealthSimpel_, 2 new products come to mind:

1.  Cryptocurrency Exchange - you can buy cryto currency on _WealthSimple_, but with more and more customers who want to swap one Crypto for another striaght across like a currency exchange -they would have to go to a company like [Uniswap](https://en.wikipedia.org/wiki/Uniswap) .  Uniswap faciliates excahnging one Crypto currency for another at todays market rates, they take a fee for the exchange.  This is a largely untapped market, and would be a great way to generate cash flow for the company.  Because the technology is already esssentially in place this woud be the easiest product to implement and expand their product line.

2. Loans and mortgage - [Rocket mortgages](https://www.rocketmortgage.com/?redirect=true&croRedirect=RmSitecoreControl&adobe_mc_sdid=SDID%3D7E2D03A094B2E02F-2B1FBCCA8030782F%7CMCORGID%3D5D60123F5245B13E0A490D45@AdobeOrg%7CTS%3D1653871204&adobe_mc_ref=https:%2F%2Fwww.google.com%2F) from quicken have already proven the concept.  Defi Mortgages have proven to be profitable,  Rocket Mortgages generatedd $12.9 billion in revenue in the period of 2021.  With competitors such as Sofi and Prosper getting into the space, there is an opportunity to get in early and grab "Early Majority" in the Canadian market.  _WealthSImple_ is already a trusted space for Candadians to invest thier money, why not make it one stop shop for all your financial product needs.

*Why do you think that offering this product or service would benefit the company?

I beleive, that in both of the products stated above, you have a exisiting proof of concept. With the trust and customer validatino that _WealthSimple_ has built over the years, they could put this good will to use and help customers with even more financial product.  The main benefit to the company would be the cash flow from these products, the company already has the assets to set up the Defi accounts.  With proper risk managment with regards to customer loans and approvals, the mortgage and loan product would be an instant cash generator.  

The Cryptocurrency excahange would take a large upfront cost\ to build the program and coding neccessary to facilitate the product.  Also you would have to generate a pool of Cryto assets to perform the swaps, but after the initial investment - once the swap and pool is in place you would need a team for maintanance.  From then on your product would be cash flowing and generating profit for your investors.


* What technologies would this additional product or service utilize?

The Crypto Exchange would utilize smart contracts thru Blockchain technology, which would be based on the Solidity object programming language.  Crypto based SSH keys to ensure security would also need to be established.  _WealthSimple_ already utilizes this technology, and is the space of securily storing and transforming data, so this should be easy to implement.

With regards to the loans and mortgage, similar Blockchain based smart contracts would need to be created to ensure contracts are executed properly.  With smart contacts being a form of a "safe vending machine", the customer and _WealthSImple_ would both have the assurance that loans and mortgages would not be executable untill all conditions are met in the contracts.  Once the conditions are met the contracts(loans/titles) are released - this will allow for a more secure and hassle free process for both the customer and the business.  Essentially a "Win WIn".

* Why are these technologies appropriate for your solution?

As previously stated, Smart contract technology delivered thru solidity based programming, would be a trusted and proven method to facilitate the above products for _WealthSimple_.   The bloclkchain technology would gurantee the accuracy of the contracts performed and the documentation would be available to the authorized nodes to scrutinize the and document the transacaitions.  

With the advantage of this technology we can ensure the accuracy, proper execution and cost saving efffeciency of these new products.




























   

  






      