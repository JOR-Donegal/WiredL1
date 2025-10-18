# 3. Data Centers
An enterprise data centre can vary in size from 3 racks in a small room, to a full EN 50600 compliant facility. For a large custom designed data centre, there will be general offices, a control room, and many separate spaces for generators and fuel, electrical and transformers, mechanical, storage, docking/loading, etc. There will be at least two well separated telecoms entrance rooms. The design will be heavily influenced by availability, security/protection and efficiency. 

The main cabinet/server area was called a data hall, but all the new standards refer to it as a computer room. In this area, recommendations are for racks 800w and 1200d no greater than 20 cabinets per row in a hot aisle/cold aisle arrangement. Switches and active equipment can be located at the End-of-Row (EoR) or in the Middle-of-Row (MoR) and many design assumptions are based on one or other. Copper or fibre, price, speed and distance have to be considered in making the design decisions. Alternatively, Top-of-Rack (ToR) switches may exist in each rack. 

The data hall should not exceed 600m^2 or 25m x 25m and will typically have 10 rows of cabinets.
 The idea for the structured cabling is hierarchical, but the terminology is different from the previous examples. On its own, ISO11801 Part 4 is hard to read and translate into something that makes sense. It really needs to be combined with EN 50600 2-4 which is specifically aimed at data centre telecoms wiring. There are several types of wiring structure specified, for example;
We frequently use point to point cabling which is not part of a hierarchical standard and this is allowed for. It really should not be used on large installations!

The data centre may have an attached office, this follows ISO 11801 Part 2 as explained previously.
Monitoring and control will use a structure like that of an office, but with a service distributor (SD) level replacing the FD. This wiring complies with ISO 11801 Part 6 for Distributed Building Services.

The data hall services have a unique hierarchy. A typical example; storage and servers connect to EOs and are consolidated at LDPs and then at ZDs. The passive cabling terminates in switches at the ID and these switches connect to core switches and routers at the MD. There are different availability classes specified; this dictates the number of external telecoms providers and the number of dual paths or cross connects.

<figure>
<img src = "https://jor-donegal.github.io/WiredL1/images/fig4.jpg">
<figcaption>Fig 4. Reference points for a data centre.</figcaption>
</figure>