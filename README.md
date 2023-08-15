# Michel Moriniaux 
#### michel.moriniaux@gmail.com +1 650 381 4968

## Experienced SRE leader

## Profile
Experienced manager with 24 years of experience in tech and 8 years in people management. I have held positions leading network engineering to supporting product development teams at leading corporations.

## Work Experience
### [LinkedIn](https://www.linkedin.com "LinkedIn Homepage"), Professional Social Network, Microsoft Corporation, 2020 to present 
#### SRE Senior Manager, LinkedIn Talent Solutions, Jan 2023 to Present
After 2 years managing the Hire SRE team my role was expanded to lead all of LinkedIn's Talent Solutions SRE teams ( Hire, Seekers and Jobs, Learning ) supporting the 3 Talent pillars.
In this role I've:
* managed up to 25 engineers and managers, currently 3 managers and 2 IC directs.
* Successfully expanded the learnings and methods devised in the Hire team to the 2 other teams
* In the space of 3 months, accelerated the transition of SREs to SWE roles as we move SREs out of the firefighting path and concentrating in providing the tools for reliable, transparent service ownership. focusing on regression prevention through the SDLC.

#### SRE Manager, LinkedIn Hiring Solutions, 2020 to Jan 2023
After 20 years in the networking and datacenter business it was time for a change. I decided to expand on the side job I had at Criteo managing a PRE team and dive fully into management. I joined LinkedIn on the first day of Covid shutdown to manage the team in charge of reliability of the Hiring product. This product generated most of LinkedIn's revenue. Unfortunately, reliability was not at the right level and SREs spent their time chasing fires. During my 2 years in this team I:
* managed up to 12 engineers
* raised the availability of the product from 98.9% to 99.97%
  * brought reliability to the heart of SWE preoccupations
  * Pushed SWE management to start the Major product redesign process that modularized the product monolith, culminating in a 3 year project to phase out the original LinkedIn hiring product
  * executed on the project providing my team's support to build the right accountability
* initiated a transformation initiative to bring more responsibility from SWEs and less gatekeeping from SREs.
  * initial successes pushed the SRE org to accelerate their larger SRE3.0 plan that proposed similar principles.
  * significantly reduced stress levels and fear of on-call and stopped on-call burn-out related attrition.
* brought structure to project management by enforcing lightweight Agile methods. The team welcomed the change as it gave them goals with increased autonomy

### [Criteo](http://www.criteo.com "Criteo's Homepage"), AdTech global leader in retargeting solutions, 2014 to 2020
2.5B revenue, 2.7K employees, 8 datacenters around the world 2MW minimum footprint, Global nx100G WAN, 5M QPS
#### Start of the US adventure, 2017 to 2020, Sr Staff Ops Lead
I built a project to move to our US office to create a set of teams that leverage the talent pool of the Valley and be as close as possible to where innovation is happening.
Over 3 years I built 3 teams from scratch two of which where totally outside of my comfort zone and areas of expertise. I groomed managers to lead these teams.
* An integrated infrastructure team (4): Leveraging Valley innovation I built a team of multidisciplinary experts that streamlined the way we build-out capacity while bringing-in the latest and best practices. we delivered the following projects:
  * Procedural datacenter layouts: where historically we were planning out floorplans by hand we now had a set of scripts to layout everything in 3D
  * Automated the rack and roll validation process by creating a Raspberry pi based appliance to do the job.
  * Criteo's quickest capacity build-out to date
  * Brought to Criteo a complete line of Whitebox alternative switches for our Clos fabrics
  * Became contributors to the SONiC OSS Network Operating System and were recognized at the OCP keynote for our efforts
  * Rolled out SONiC to our greenfield builds
  * Designed the future of our disaggregated datacenters and the DCI OLS solution it would be built upon
  * Launched a set of machine learning projects to leverage the monitoring data that we had been storing. The goal was to be able to predict rather than react to failures in the network
* a PRE team (4): PRE stands for Product Reliability Engineering, it consists in bringing the SRE method to Product Engineering. PREs sit with the product developers and clear all non-business-logic dependencies by integrating or coding the necessary connectors, they are responsible for the reliability of the product and are the first line of support when things go wrong.
* A DBA team (3): The Palo Alto office needed to have a set of resident Database Administrators to help them with our SQL stack, I worked with our Paris HQ DBA teams to recruit local talent and managed to secure an experienced internal mobility to lead the team.

This is a very interesting hybrid role as I have to technically contribute but I also have to hold an engineering manager position. I report directly to my VP of infrastructure on one side and through dotted lines to the VP of SRE and the local SVP of Product Engineering.

Employment at Criteo stopped when the company decided to close the Palo Alto Office. Thanks to my influence in the office's day to day, I was part of a 4 person team tasked to facilitate the transition or termination of 150 employees and the clean shutdown of the office's operations.

#### From leading network tech to leading the network engineers, 2015 to 2017, Sr Staff Network Engineer, Sr Staff Ops Lead
Having natural leadership in my team it became logical to give me the management of the team. This was a time of consolidation where we took everything we learned in the past 2 years and built:
* A team of 4 engineers: 3 local and 1 remote in Beijing, China.
* Guided 2 engineers through the P&P process to a successful promotion to Staff Operations Engineer level.
* A standardized way of building network fabrics that could scale cost effectively
  * 5 stage clos architectures built out of one generic SKU that could be sourced from multiple vendors ( 32x100G Tomahawk based switches )
* Designed the Edge pod and replaced expensive transit routers with a commodity switch based mini IP fabric + BGP optimizer. We no longer need expensive million route TCAMs but 10000 entries are enough with good route selection.
* Budgeting

#### Scaling Criteo Networks, 2014 to 2015, Staff Network Engineer
I joined Criteo with one project in mind: build Clos Fabrics at scale.
At the time Criteo used proprietary L2 tech from one entrenched vendor. The Premji-Lapukhov Draft had not been made public yet and the only literature available was a Microsoft presentation about using eBGP in large scale datacenters. Nevertheless I was convinced this was the way to go. The first challenge was to convince my new colleagues and with the help of several hyperscale vendors I was able to move my vision through. If we were going to build large vendor agnostic IP fabrics we would not only need new automation but also the support of other teams as we were going to drastically change the way services were provisioned and used. 
We built a v-team with the nascent SRE team and EPMs to kickstart the project. One year later we had built Europe's largest private Hadoop cluster with 5000 nodes and a full eBGP 5-stage Clos IP Fabric with automated network provisioning.

I delivered the following:
* introduced the netDevOps concept and infrastructure as code 
* Introduced IP fabrics
* Created an Ansible based automation system that was vendor agnostic and could generate configurations from an abstraction
* Deployed the largest private Hadoop cluster in EMEA
* Streamlined build processes to move from a boutique operation to a just-in time industrialized builds

### [Prosodie Cap Gemini](http://www.odigo.com), Managed Services Provider, 2009 to 2014
3 datacenters, 250Kw minimum footprint, National dark fiber WAN
#### From WAN to DC
I joined the company as a network engineer and rapidly rose to tech lead on the routing and WAN side of the business. I subsequently got introduced to the datacenter side and what it took to operate a multitenant system with hundreds of custom builds.
during my stay I delivered the following projects:
* WAN redesign: moving from SDH(EuroSonnet) loops to loops riding a DWDM muxponder network.
* Replaced all core routers and edge routers ( cisco6500 to Brocade MLXe )
* Redesigned the complete routing stack twice: first from a full OSPF to a MP-BGP based ISP design then to a BGP-free core design
* Merged Prosodie's and InternetFR networks during the M&A
* Introduced IPv6

### [B3g Telecom](http://www.sfrbusiness.fr), VoIP Service Provider, 2006 to 2008
3 PoPs, 2500+ remote offices in France though DSL backhauls
#### A new challenge
I came on-board when B3G signed it's largest customer: France's largest supermarket chain with more than 2000 locations. My mission was to build a redundant network to all locations to be able to provide the company's VoIP centrex product to the branches.
I solved the following challenges:
* Engineer the infrastructure solution
* The whole network had to be autoconfigured: CPEs, IP phones, ATAs, accounts, centrex configs, LNS
* Create the supply chain to deploy and auto-provision 10 locations per day

### [UUNET / Worldcom / MCI / Verizon](https://en.wikipedia.org/wiki/UUNET), ISP, 2000 to 2005
Global IP network, AS701,AS702,AS703, most connected IP network at the time.
#### The learning years
I Joined the ABN ( Access and Backbone Networks ) team to work on the core of AS702. UUNet was ISP/Carrier networks university, I got to learn from the best in the business the best practices and the most scalable way to design carrier grade IP networks.
During my tenure there I:
* Redesigned the OOB management network and deployed it to the EMEA region
* Day to day Network operations and on-call rotations
* Built the first STM16 network in Paris out of brand new Juniper M40 and M160
* Designed the technical components of the new xDSL based products
* Special Bids technical consultant

## Skills
* Organizational Transitions
* Agile Methodologies
* Technical Leadership
* Inclusive Team Leadership
* Software development
* Network Design
* Data Center
* English, French and Spanish native speaker

## Education
#### [Stevens Institute of Technology](https://www.stevens.edu/schaefer-school-engineering-science/departments/computer-science), Hoboken NJ, MS CS 2000 

#### [EPITA](http://www.epita.fr), Paris France, Specialized school in Computer Science, Engineer degree 1999

## Misc.
Authorized to work in the USA ( green card ) and EU ( French citizen )
