---
author: biguru
comments: true
date: 2009-11-13 08:12:30+00:00
layout: post
link: https://biguru.wordpress.com/2009/11/13/review-of-the-bt-summit-%e2%80%93-cloud-computing-soa-and-bi-tracks/
slug: review-of-the-bt-summit-%e2%80%93-cloud-computing-soa-and-bi-tracks
title: Review of the BT Summit – Cloud computing, SOA and BI tracks
wordpress_id: 54
categories:
- Strategy
tags:
- AWS
- cloud computing
- Hadoop
- REST
- SaaS
---

I attended the [Business Technology Summit in Bangalore](http://www.btmarch.com/btsummit/) last week – 3rd and 4th November. There were 3 tracks on cloud computing, Service Oriented Architecture and Business Intelligence, and I chose a mix of sessions across each.

**Overall impression:**The BT Summit was heavily focused on cloud computing with half of second day having a deep dive into Amazon’s EC2 cloud offering, and several keynotes. SOA and web services, REST and similar architectural sessions were interspersed but definitely not a first-class citizen. BI came a poor third with a poor choice of sessions, and more of a rehash of what is out there for everyone, rather than something on the cutting-edge including use of appliances and columnar databases, as also in-memory databases and use of Flash and AJAX for interactive BI front-ends.

**Session-wise review:** (Speaker profiles available [here](http://www.btmarch.com/btsummit/speakers.html)). I was able to speak to and ask questions of Vinod Kumar, Vijay Doddavaram, Abhinav Agarwal and Dr. Bob Marcus.

**Keynotes:**




  * **Smart services, bright future** by [Howard Charney](http://www.btmarch.com/btsummit/speakers.html)


Probably the highlight of the keynotes, this was a pep-talk about the inevitable interconnected future with smart products and services and for good measure Charney threw out some statistics on broadband growth and bandwidth usage and India’s readiness and potential in the scheme of things.


  * **Give cloud a chance** by [Ramkumar Kothandaraman](http://www.btmarch.com/btsummit/speakers.html)


The worst of the lot – this started by comparing the spectrum of offerings in the cloud from [Amazon’s DIY EC2 and AWS](http://aws.amazon.com/ec2/), [Google appengine and apps](http://code.google.com/appengine/) to [Microsoft’s Azure](http://www.microsoft.com/windowsazure/) and ended up as a promo touting Azure as the best buy among all.




  * **C****loud computing: State of the union address** by [Shouvick Mukherjee](http://www.btmarch.com/btsummit/speakers.html)


A very good keynote, focusing on what makes sense to migrate to the cloud and what doesn’t, what are the hidden costs, the myth of unlimited elasticity in the cloud and what Yahoo is doing to use open source software like [Hadoop](http://hadoop.apache.org/) and [Hive](http://wiki.apache.org/hadoop/Hive) for cloud computing. In the short time span, Shouvick also tried to address some of the other considerations – including re-architecting existing applications, availability, data storage and movement considerations.




  * **Managing IT in turbulent times** by [Som Sharma](http://www.btmarch.com/btsummit/speakers.html)


This post-lunch keynote by Sharma was a rambling talk on how technology keeps redefining our lives, and why it is important to think outside-the-box. He used the example of the iPhone to illustrate how such thinking has the potential to alter the established rules of the industry and redefine it as we know it.


  * **A New world to protect** by [Nils Puhlmann](http://www.btmarch.com/btsummit/speakers.html)


Puhlmann provided the security perspective on how easy it to break/hack enterprise systems and how anti-virus and anti-spyware are always playing catch-up, the entire economy that is spawned by the “bad-guys” in technology and why our systems need to be smart and be built from the ground-up for security rather than as an afterthought. He provided valuable insights into what questions we should ask ourselves as we embrace cloud computing, the changing technology landscape making it easy for consuming information but easier still for the security breachers. Puhlmann concluded by suggesting it may be worthwhile including a level of risk assessment and mitigation, and collaboration with ethical hackers, rather than trying to do the impossible of removing all security threats.


  * **Moving towards a virtual enterprise** by [Srinivas Varadarajan](http://www.btmarch.com/btsummit/speakers.html)


Barely managed to sleep through it – this one talked about moving towards a virtual enterprise – with a focus on virtualized architecture, including cloud computing. As boring as they can get.

**Other sessions:**




  * **SOA, Composite Applications, and Cloud Computing:** **Three pillars of a modern technology solution** by [Robert Schneider](http://www.btmarch.com/btsummit/speakers.html)


Robert  Schneider presented the different facets of SOA, Composite applications (superset of mash-ups) and Cloud computing and contrasted them regarding the time to yield benefits, the maturity of the vision, involvement and buy-in from business and where they lie in the tactical-strategic plane. There wasn’t anything regarding why we are stuck with these three for a modern technology solution, or what other paradigms are out there beyond the old-world enterprise computing framework, possibly due to time constraints.


  * **Self-service analysis and the future of Business Intelligence** by [Vinod Kumar](http://www.btmarch.com/btsummit/speakers.html)


A lot of the BI folks were waiting for this, as Vinod performed the [Project Gemini (Office 2010 Excel and PowerPivot)](http://blogs.msdn.com/excel/archive/2009/07/14/sneak-preview-of-project-gemini.aspx) demo live for the first time in India, with several folks, including yours truly, sitting on the stairs. [We have had to rely on [Youtube videos and MS Office 2010 preview videos](http://www.youtube.com/geminute) earlier]. The demo was impressive fetching over 13 million records into Excel using a standard DDR laptop, using compression and in-memory technologies. The bigger question around unleashing another round of Excel hell went unanswered due to time constraints, however the presentation probably hinted at Microsoft’s vision of “self-service BI” or so-called “underground-BI” as the power-users of Excel (estimated at 2M worldwide, at 4% of the Excel user base) have been doing. Microsoft’s strategy around pushing SharePoint adoption in the Enterprise was made clear tacitly with SharePoint being the only “portal” to publish and share BI analysis (typical size of these Excel spreadsheets is upwards of 200MB) with other users in the enterprise.




  * **Designing and Implementing RESTful web services** by [Eben Hewitt](http://www.btmarch.com/btsummit/speakers.html)


Eben Hewitt started off with a very brief comparison between SOAP (Simple Object Access Protocol) modeled more on the lines of RPC (Remote Procedure Call) and REST (Representational State Transfer) and clarified that REST is more an architectural style rather than specifications. The remainder of the talk delved into details of implementation of REST – usage of simple ‘verbs’ and complexity in ‘nouns’, uniform interface, using named resources, java REST frameworks like Jersey, MIME types – JSON, XML, YAML and HTTP operations supported – POST, GET, PUT and DELETE.


  * **Business Intelligence project execution on a shoestring** by [Rajesh Ramaswamy](http://www.btmarch.com/btsummit/speakers.html)


I attended with some expectations on how a BI project can be executed possibly with open-source or free software like MySQL/Postgres, Pentaho/Talend, Jaspersoft/MicroStrategy reporting suite etc., but was highly disappointed by the presentation. Ramaswamy spoke on BI usage, barriers to BI adoption, costs of BI implementation and spewed statistics like m&m’s with cursory references to Forrester, Gartner and “research studies”, but there wasn’t anything tangible on how to go about a project execution except for some common-sense talk on “evaluating options” between open-source and licensing costs, offshoring and outsourcing, RDBMS vs. analytical databases and appliances etc.


  * **Business Intelligence – Leveraging and Navigating during current challenging times** by [Vijay Doddavaram](http://www.btmarch.com/btsummit/speakers.html)


Vijay spoke of the current global economic downturn and how it had taken everyone unawares during the downturn as well as when the current quarter the tide seems to have returned. With the example of a fictitious company in China, he illustrated the importance of trade-off between tactical and strategic decision making and whether and how business intelligence can make a difference in either a downturn and the upswing (whether it is a U, V, or a W curve). Thought-provoking, one couldn’t help feel that BI software has not yet eliminated the “intelligence” that people bring to the table, and made a distinct point about the “human analysis/intelligence” against the out-of-the-box actionable-intelligence marketed by the BI vendors. It would have been interesting to prolong the discussion, with a focus on the “[predictive-analytics](http://en.wikipedia.org/wiki/Predictive_analytics)” offerings in the market (from SAP, WPC, SPSS and the open-source R etc.), we had once again run out of time, and it was the last session of the day as well.




  * **Towards a unified Business Intelligence and Enterprise Performance Management Strategy** by [Abhinav Agarwal](http://www.btmarch.com/btsummit/speakers.html)


Abhinav is from Oracle and he used this session to basically present the BI and EPM strategy of Oracle. Refreshing when contrasted with the usual Oracle marketing hype, Abhinav made it a point to stress the difficulty of delivering best-in-breed products due to numerous acquisitions and the inevitable integrations compared to the disruptive start-ups which could be one-trick ponies but nevertheless manage to push the technology envelope. Most of the session focused on [Oracle BI server offering](http://www.oracle.com/technology/products/bi/enterprise-edition-platform-components.html) and the roadmap of integrating with the [Fusion middleware](http://www.oracle.com/technology/products/middleware/index.html), and brief touchpoints on the capabilities of the Oracle BI server: federated queries (acquired from nQuire, which Siebel systems had acquired, prior to being bought by Oracle), and real-time updates, including [Oracle RTD](http://www.oracle.com/appserver/business-intelligence/docs/oracle-rtd-product-brief.pdf) (Real-time Decisions) and the segregation of the BI and EPM software offerings.




  * **10 Things software architects should know** by [Eben Hewitt](http://www.btmarch.com/btsummit/speakers.html)


I was able to attend part of it, but for the most part- the bottomline of this talk was the trade-offs architects need to make and understanding there may not be a “solution” to a problem, it may just be “moving the problem” – the idea that each “solution” brings its own issues and tradeoffs into the picture. Being more focused on java APIs and cloud computing frameworks, it could have done better with something related to networks and database architecture in general for audience to relate better (for most of my time, I couldn’t relate to a BI applications and data-warehousing infrastructure).


  * **Cloud initiatives and standards roadmaps** by [Dr. Bob Marcus](http://www.btmarch.com/btsummit/speakers.html)


Being late from an overcrowded dining hall, I was able to attend part of this. Bob spoke of the various public and private initiatives including those from the federal government, NASA [Nebula ](http://nebula.nasa.gov/)and made the distinction early on between the types of offerings on the cloud: [SaaS ](http://en.wikipedia.org/wiki/Software_as_a_Service)(Software as a service), [IaaS ](http://en.wikipedia.org/wiki/Infrastructure_as_a_service)(Infrastructure as a service) and [PaaS](http://en.wikipedia.org/wiki/Platform_as_a_service) (Platform as a Service). He mentioned in passing the [data.gov](http://www.data.gov/) and [apps.gov](https://apps.gov/cloud/advantage/main/start_page.do) initiatives of the Obama administration as also about [RACE ](http://www.disa.mil/race/)(Rapid Access Computing Environment) from the Dept. of Defense - Defense Information Systems Agency.




  * **Building Enterprise Dashboards** by [Vivek Khurana](http://www.btmarch.com/btsummit/speakers.html)


Vivek Khurana did a very short presentation to an overflowing hall on clichéd but nevertheless important aspects of [information visualization](http://www.perceptualedge.com/examples.php) while designing dashboards: clutter vs. simplicity, proper designing of KPIs, importance of delivery to mobile devices, and learning from news aggregation sites and portals on presentation.




  * **Implementing Enterprise 2.0 using Open Source products** by [Udayan Banerjee](http://www.btmarch.com/btsummit/speakers.html)


Banerjee did a great job of presenting what his vision of implementing Enterprise 2.0 in NIIT was – implementing [SLATES ](http://blogs.zdnet.com/Hinchcliffe/?p=71)(coined by Andrew McAfee) – Search, Links, Authoring, Tags, Extensions and Signals. Within half-an-hour he navigated us through using open-source products for collaboration using blogs and wiki (MediaWiki), using single-sign-on with enterprise databases, using links and tag clouds and integrating Search as well as implementing a text-based instant messenger.




  * **ECM-CMIS and the emergence of standards** by [Alan Pelz-Sharpe](http://www.btmarch.com/btsummit/speakers.html)


I had missed the earlier session of Alan on lessons learnt using SharePoint, so I made it a point to attend the last of this at the summit – even though it meant I had no clue sometimes of what was being talked about! Alan spoke of the emergence of the multi-vendor [CMIS ](http://blogs.the451group.com/information_management/2008/09/10/cmis-and-industry-standards-in-ecm/)standard for Enterprise Content Management – the various facets of ECM – from digital and media assets, email archiving, Internet content, web analytics, document types, rich media and the problems with the earlier Java standards like JSR 170 – most notably the absence of support from Microsoft. He also spoke about the vendor landscape and a 9-block rating similar to Gartner’s magic quadrant, plus various other important standards, including [XAM ](http://en.wikipedia.org/wiki/Xam)– eXtensible Access Method – a storage standard developed by SNIA (Storage and Networking Industry Association)

**Presentation files:** Most presentation files are available [here](http://www.btmarch.com/btsummit/2009/presentationFiles.html). You'll need to register though to download.

-Maloy