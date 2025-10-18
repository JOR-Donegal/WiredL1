# 4. Fiber
An optical fiber consists of a cylinder of glass called the core surrounded by a concentric layer of glass called the cladding. The glass in the cladding has a lower refractive index than the glass in the core. when light passes From a medium with a higher refractive index to a medium with a lower refractive index the lights it's been backwards towards the original medium. Any lights passing down the core which intersects with the cladding will be reflected back into the core. Lights can thus passed down the cable from end to end. To some reading here.

There are many types of fiber optic cable and connectors. These are standardized in ISO11801.

Cables are specified for indoor, outdoor, indoor/outdoor use. There are also specialist cables for undersea and for wrapping around powerlines. Outdoor cables tend to have a hygroscopic grease between the inner and outer layers, to prevent water entry. They may also be steel-wire armored (SWA).

## Multimode Fiber
For LAN applications, we use Multimode Fiber Optic links. They may use any one of several light frequencies and have different applications.

<figure>
<img src = "https://jor-donegal.github.io/WiredL1/images/table1.jpg">
<figcaption>Table 1. Standardised Fibre.</figcaption>
</figure>

When I installed fiber first in the 1990s, OM1 was standard. However, on the Letterkenny campus of ATU, we have runs up to 330m, and OM1 was only specified for 275m at 1000BASE-F.

## Single Mode Fiber
For long distance runs, we use Single Mode Fiber (SMF), carriers like Eir or BT will only use SMF. The types commonly in use are:
- OS1: Single-mode fiber type 1 db/km attenuation
- OS2: Single-mode fiber type 0.4 db/km attenuation 

## Connector Types
Pay attention to the connector types, there are many.
The ST or straight tip connector has almost disappeared now. These were also referred to as BNC connectors because of the original connector type. The original standard connector or SC connector was large and blocky.
Often, the SC connector for both fibers has hooked together and keyed, so you couldn’t connect them in reverse. 
You are more likely to see the LC or Lucent Connector on modern equipment.

## Transceivers
A transceiver will exist to convert the physical signal from copper or fiber into electrical ones and zeroes. In Ethernet terms, this is the PHY sub-layer of layer 2.

Even though this signal could have travelled 40kms before reaching the transceiver, it has done so in a very fixed environment. There is a definite physical limit for distance between the transceiver and the processing ASIC on the HBA or in the switch fabric and it’s in centimeters! There may be signal conditioning chips or serial/parallel conversion in here also (often called glue chips).
Interfaces are typically Gigabit Interface Converter (GBICs) on older equipment, Small Form Factor (SFP) on modern equipment, or SFP+ on equipment supporting 10GBs. 

Older equipment may use XENPAK or XFP modules to support 10GBs, these were horrendously expensive! 

Some vendors are anti-competitive and lock you in to using their (very expensive) own-brand transceivers. Check this in advance of buying any equipment, as your economical network may become very expensive if you don’t factor this in. 

You need to match one side of a link with the other, there are many variants. We typically use multi-mode fiber within LANs and these days would use OM5 fibers. If you have very old fiber (OM1 or OM2) you need to test and minimize length and look up the LRM standard. 
Short range (SX) transceivers use LEDs and not very much power. When we use very long range transceivers, they use laser diodes and put out enough power to destroy your retina. Do not look int this equipment.

<figure>
<img src = "https://jor-donegal.github.io/WiredL1/images/table2.jpg">
<figcaption>Table 2. Transcievers.</figcaption>
</figure>

