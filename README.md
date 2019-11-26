# Experienced SRE leader

# Abstract
20 years of experience in major Telecom, ISP and datacenter engineering.
My job is to manage and contribute to a team that designs and operates a world-class web-scale network of datacenters that provides computational power and connectivity to our Performance Marketing product.
I believe in automating myself out of my job and creating the next generation of open datacenter technologies.

I have extensive experience in web scale systems operations, from design to building and managing the teams and their systems. 

For the past 10 years I have soft managed engineering and production teams

For the past 5 years I have successfully held positions of tech-lead, team lead and engineering manager for global teams ( Europe/US/China ).

I have diversified my leadership and helping the organization at large by building teams outside of my scope ( Database Administrators, Product Reliability Engineering ) in locations where they were needed.

I am highly adaptable and a fast learner, I believe that if by the time your infrastructure reaches 50,000 servers you are not operating them like they were one million then you have lost the game and will always be playing catch-up.

My pet projects are datacenter networks with a focus on Open Source Network Operating Systems.

In my current scope I’m working on pushing the company's worldwide organization and tech stack to the next step in distributed architectures to allow the company to sustain its growth.

# Skills
## Management
Accomplished manager
- I consistently score in the top 1% of the company's manager surveys.
- I have a very hands-off style, I trust the people I manage to do their best and they reciprocate that trust by going above and beyond.
- I use adapted Agile methods ( Scrum or Kanban ) and OKRs to keep my teams on track
- Quarterly team health checks allow us to correct course.

## Technology
I am an avid technologist curious of everything
#### Large breath of knowledge in systems and networks
- Linux administration
- Webscale Systems design
- Operating system internals
- Automation frameworks ( homegrown, Ansible, Chef )
- Container tech
- Datacenter IP network fabric underlays
- Network protocols
- WAN design
- ISP operations
- BGP
- Networking and compute hardware
- SONiC
- Optical Line Systems ( basic )
- P4 ( introductory )

#### Datacenter:
- Cooling systems
- Electrical onelines
- DataCenter management
- DataCenter selection and due process
- Supply chain management
- RFP RFQ RFO processes
- Open Compute Project

#### Software:
- I can code to save my life
- Preferred languages are Python and C
- I am highly adaptable and can learn the language of the day ( not a fan of ruby, lisp or other exercise in style )
- CI/CD git gerrit jenkins

and a bunch of other stuff

## SkillPoint Build
### Stabilizing ( Marston Behavioral DISC model )
- Very inclusive of others in the team. No one feels left out.
- Good organizational skills in building complex processes and following through completion while maintaining positive climate
- Ready, willing and able to help others to grow and become more effective and successful
- Persuades others by offering empathy, understanding, and friendship
- Will not show hostility towards others, even if its present. no good can come from creating hostility or dissent
- An ability to get along with a wide variety of different people
- Handles both the human side and the task side of many projects with equal skill
- Excellent team player and supportive of team efforts

### Gallup top 5 CliftonStrengths
- Futuristic
- Ideation
- Relator
- Adaptability
- Empathy

### Languages:
fluent in English, Français y Español ( all three are native languages )

C, shell, python to various levels

### hobbies:
- astrophotography ( widefield, time-lapse )
- flying ( SEP PPL )
- RC flying
- woodworking
- robotics / automation ( home, astronomy gear, 3d manufacturing, Arduino )
- photography
- travel

# Work Experience
## [Criteo](http://www.criteo.com "Criteo's Homepage"), AdTech global leader in retargeting solutions, 2014 to present
2.5B revenue, 2.7K employees, 8 datacenters around the world 2MW minimum footprint, Global nx100G WAN
### The US adventure, Applying my talents to a larger scope, 2017 to present
I built a project to move to our US office to create a set of teams that leverage the talent pool of the Valley and be as close as possible to where innovation is happening.
Over the past 3 years I've built 3 teams from scratch two of which where totally outside of my comfort zone and areas of expertise.
* A DBA team (3): The primary need of the Palo Alto office was to have a set of resident DataBase Administrators to help them with our SQL stack, I worked with our Paris HQ DBA teams to recruit local talent and managed to secure an experienced internal mobility to lead the team.
* An integrated infrastructure team (4): the whole point of being in the Valley was to innovate. In that regard I applied the SRE method to datacenter infrastructure, I didn't want a DC tech, a network guru and a systems ninja, I wanted to build a team of multidisciplinary experts that would streamline the way we build-out capacity while bringing-in the latest and best practices. we delivered the following projects:
  * Procedural datacenter layouts: where historically we were planning out floorplans by hand we now had a set of scripts to layout everything in 3D
  * Overhauled the order tracking process by moving the system from MS Excel to a web based system developed by my team
  * Automated the rack and roll validation process by creating a Raspberry pi based appliance to do the job.
  * Criteo's quickest capacity build-out to date
  * Brought to Criteo a complete line of Whitebox alternatives for our Clos fabrics
  * Became contributors to the SONiC OSS Network Operating System and were recognized at the OCP keynote for our efforts
  * Rolled out SONiC to our greenfield builds
  * Designed the future of our disaggregated datacenters and the DCI OLS solution it would be built upon
  * Launched a set of machine learning projects to leverage the monitoring data that we have been storing. The goal is to be able to predict rather than react to failures in the network
* Bootstrapped our local PRE team (4): PRE stands for Product Reliability Engineering, it consists in bringing the SRE method to Product Engineering. PREs sit with the product developers and clear all non-business-logic dependencies, they are responsible for the reliability of the product and are the first line of support when things go wrong.

This is a very interesting hybrid role as I have to technically contribute but I also have to hold an engineering manager position. I report directly to my VP of infrastructure on one side and through dotted lines to the VP of SRE and the local SVP of Product Engineering.

I am the designated successor to my VP of Infrastructure in the company's contingency and succession plan

### From leading network tech to leading the network engineers, 2015 to 2017
Having natural leadership in my team it became logical to give me the management of the team. This was a time of consolidation where we took everything we learned in the past 2 years and built:
* A team of 4 engineers: 3 local and 1 remote in Beijing, China.
* Guided 2 engineers through the P&P process to a successful promotion to Staff Operations Engineer level.
* A standardized way of building network fabrics that could scale cost effectively
  * 5 stage clos architectures built out of one generic SKU that could be sourced from multiple vendors ( 32x100G Tomahawk based switches )
* Designed the Edge pod and replaced expensive transit routers with a commodity switch based mini IP fabric + BGP optimizer. We no longer need expensive million route TCAMs but 10000 entries are enough with good route selection.
* Budgeting

### Bringing Criteo networks to the grownup table, 2014 to 2015
I joined Criteo with one project in mind: build Clos Fabrics at scale.
At the time Criteo used proprietary L2 tech from one entrenched vendor. The Premji-Lapukhov Draft had not been made public yet and the only literature available was a Microsoft presentation about using eBGP in large scale datacenters. Nevertheless I was convinced this was the way to go. The first challenge was to convince my new colleagues and with the help of several hyperscale vendors I was able to move my vision through. If we were going to build large vendor agnostic IP fabrics we would not only need new automation but also the support of other teams as we were going to drastically change the way services were provisioned and used. 
We built a v-team with the nascent SRE team and EPMs to kickstart the project. One year later we had built Europe's largest private Hadoop cluster with 5000 nodes and a full eBGP 5-stage Clos IP Fabric with automated network provisioning.

To summarize during that time I delivered the following:
* Introduced IP fabrics
* Created an Ansible based automation system that was vendor agnostic and could generate configurations from an abstraction ( OpenConfig was not a thing yet )
* Deployed the largest private Hadoop cluster in EMEA
* Kicked out the entrenched vendor who did not get hyper-scale concepts
* Streamlined build processes to move from a boutique operation to a just-in time industrialized builds
* Deployed a greenfield DC in Shanghai China
* Routing policy redesign
* Day to day Network operations and on-call rotations
* Actively participated in hiring committees

## [Prosodie Cap Gemini](http://www.odigo.com), Managed Services Provider, 2009 to 2014
3 datacenters, 250Kw minimum footprint, National dark fiber WAN
### From WAN to DC
I joined the company as a network engineer and rapidly rose to tech lead on the routing and WAN side of the business. I subsequently got introduced to the datacenter side and what it took to operate a multitenant system with hundreds of custom builds.
during my stay I delivered the following projects:
* WAN redesign: moving from SDH(EuroSonnet) loops to loops riding a DWDM muxponder network.
* Replaced all core routers and edge routers ( cisco6500 to Brocade MLXe )
* Redesigned the complete routing stack twice: first from a full OSPF to a MP-BGP based ISP design then to a BGP-free core design
* Merged Prosodie's and InternetFR networks during the M&A
* Introduced IPv6
* Peermaster
* Day to day Network operations and on-call rotations
* Budgeting

## [B3g Telecom](http://www.sfrbusiness.fr), VoIP Service Provider, 2006 to 2008
3 PoPs, 2500+ remote offices in France though DSL backhauls
### A new challenge
I came on-board when B3G signed it's largest customer: France's largest supermarket chain with more than 2000 locations. My mission was to build a redundant network to all locations to be able to provide the company's VoIP centrex product to the branches.
I solved the following challenges:
* Engineer the complete solution
* The whole network had to be autoconfigured: CPEs, IP phones, ATAs, accounts, centrex configs, LNS
* Create the supply chain to deploy 10 locations per day
* Provide L2 support
* Train L1 support and delivery managers

## [UUNET / Worldcom / MCI / Verizon](https://en.wikipedia.org/wiki/UUNET), ISP, 2000 to 2005
Global IP network, AS701,AS702,AS703, most connected IP network at the time.
### The learning years
My first official job. After school I knew where I wanted to work and it was at the largest ISP with the biggest pipes. I was ready to grab any job available to put my foot through the door. I thus started in the DAN ( Dial Access Networks ) team racking Max TNT NASes. After 3 months I was moved to the ABN ( Access and Backbone Networks ) team to work on the core of AS702. UUNet was ISP/Carrier networks university, I got to learn from the best in the business the best practices and the most scalable way to design carrier grade IP networks.
During my tenure there I did:
* Redesigned the OOB management network and deployed it to the EMEA region
* Day to day Network operations and on-call rotations
* Built the first STM16 network in Paris out of brand new Juniper M40 and M160
* Designed the technical components of the new xDSL based products
* Specil Bids technical consultant

# Education
## [Stevens Institute of Technology](https://www.stevens.edu/schaefer-school-engineering-science/departments/computer-science), Hoboken NJ, MS CS 2000 
Specialization in telecommunications
- Wrote WAN design tools
- MPI Mandelbrot generator

## [EPITA](http://www.epita.fr), Paris France, Specialized school in Computer Science, Engineer degree 1999
Specialized in Systems and Security.

Projects:
- Universal calculator
- MMORPG engine (server side)
- Write a shell
- Write make
- Java bytecode decompiler
- Private key sequester
- Corewar

# Misc.
Authorized to work in the USA ( green card ) and EU ( French citizen )

contact: michel.moriniaux@gmail.com  phone: +1 575 DCBUILD
