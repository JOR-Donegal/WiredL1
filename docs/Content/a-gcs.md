# 1. Generic Cabling Systems
As with many technology standards, the early situations emerged in the United States. The Electronics Industries Association (EIA) ceased operations c. 2011 but is still referenced. The telecommunications industry Association (TIA) is still accredited by the American National standards Institute (ANSI). The first standards were interested in looking at is variously referred to as EIA/TIA 568 or ANSI/TIA 568, issued in 1991. In 1995, a coherent international standard was released for layer 1, ISO 11801:1995. The terminology is very different from ANSI/TIA 568 and is the standard we currently employ. The most recent version of this standard that I am familiar with is ISO 11801:2017. But this is an electrical standard, and as you might expect, there are separate European standards! An EN standard is one that has been ratified by either CEN, CENELEC or ETSI, I will leave it to you to look up these acronyms and understand the organizations. EN 50173 is derived from and compatible with the TIA and ISO standards but has some additional requirements. For the design of international projects, I normally refer to the ISO standards. In compliance with electrical regulations, you must quote the EN standard for work in Ireland.

The notion of a generic cabling system is that any required service can be provided at any location on a campus or in a data center. The principles are laid out in ISO/IEC 11801-1 [^1] and section 5 defines a generic cable design for offices and industrial sites.

<figure>
<img src = "https://jor-donegal.github.io/WiredL1/images/fig1.jpg">
<figcaption>Fig 1. From ISO11801.</figcaption>
</figure>

To make sense of this, imagine I have a telephone exchange in a building (left, distributor 4). I patch that through the building to a wiring closet which inter-connects buildings (distributor 3). That passes through an underground cable (subsystem cable 3) to my destination building wiring closet. The phone line now passes up the building to a distributor on the floor where I want to deliver the phone service (distributor 1). I now pass through horizontal cabling to a wall outlet (TE). I insert a patch lead and connect the phone.
The last time I reviewed this standard it included six documents. 

- Part 1: General Guidelines and cable specifications for copper and fiber. 
- Part 2: Office Premises, comprising single or multiple buildings on a campus in which the maximum distance over which telecommunications services can be distributed is 2km. 
- Part 3: Industrial Premises, which are similar in structure to the office hierarchy, but with an extra intermediate level for connecting automation equipment of a factory floor. The campus can also be bigger with maximum scope of 10km. 
- Part 4: Homes of multiple buildings with IT and communications technology. This document will not go into detail of this standard. 
- Part 5: Data Centers 
- Part 6: Distributed Building Services, heating, ventilation, security, etc.

We are interested in the cabling hierarchy. Let’s create an imaginary campus site; a campus is a location where we have more than one building on a single site.

<figure>
<img src = "https://jor-donegal.github.io/WiredL1/images/fig2.jpg">
<figcaption>Fig 2. Campus Site.</figcaption>
</figure>

[^1]: ISO/IEC 11801-1:2016 