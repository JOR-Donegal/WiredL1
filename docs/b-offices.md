# Offices

On each floor of the main building, we will install a wiring rack or cabinet at a single location, such that we can reach all office desks keeping our cable length under 90m. We call this kind of cabinet a floor distributor (FD). Cabling/components in Ireland at present will typically be copper cables to Category 6 / Class E, the standards specify a link capable of 1 Gb/s. This cabling is called horizontal cabling and it terminates at a telecommunications outlet (TO). 

If we are going to have an enterprise data centre for the campus, we will put it on the first floor, making sure there is access for large equipment. Historically, these rooms were put on the ground floor or basement, which in the event of flooding, is a disaster.

We need to tie all our FDs to building distributor (BD) backbone cabling. We will typically bring our BD cabling back to one location and label it as the BD rack. In Ireland right now, the cabling will include OM3 or 4 multi-mode fibre optic cables and balanced copper cables for phone and other usage. It may include coaxial cable, but this is becoming uncommon. 

We need to tie all our BDs to campus distributor (CD) backbone cabling. We will typically bring our CD cabling back to more than one location and label it as a CD rack. In Ireland right now, the cabling will include outdoor grade fibre optic cables (multimode and single mode on sites with runs >300m) suited for longer runs and outdoor balanced copper cables for phone and other usage.

<figure>
<img src = "https://jor-donegal.github.io/WiredL1/images/fig3.jpg">
<figcaption>Fig 3. A ring, or a triangle?.</figcaption>
</figure>

For a site like the one above, we would wire each building to each other, forming a triangle. If a digger cuts through the ducting from building to building, we have a backup path whilst the cabling is being re-instated. We can also use our backup path to carry traffic and service, doubling our capacity. We have to bring in our carrier connections as well for phone lines and data. We will always try to bring in these two connections from redundant paths, spread as far apart as possible. In this example, we would bring these into the office building and warehouse.