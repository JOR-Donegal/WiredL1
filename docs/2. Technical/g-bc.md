# 3. Balanced Cables
There are several different technologies which can be used for layer one infrastructure. The choice of the technology is based on the application. If I'm trying to communicate with a remotely operated vehicle underwater, I'm going to use an acoustic modem. Specialist applications like this will not be covered in my notes. 

The most ubiquitous form of cabling in a modern infrastructure use twisted pair cables. In their typical use, we run cables through containment from a floor distributor (FD) to a telecom outlet (TO), up to 90m, with a patch core <=5m at either end. This is sometimes referred to as the horizontal cabling. Early developments used cabling little better than phone wires. We define the components which make up these system based on categories from ISO11801.

<figure>
<img src = "https://jor-donegal.github.io/WiredL1/images/fig8.jpg">
<figcaption>Fig 8. ISO11801 reference points.</figcaption>
</figure>

In the 1990s, we began to install buildings with components to Category 5. This generally supported 100 megabits per second Ethernet. Category 5e later emerged to support Gigabit Ethernet. For a modern installation, we have standardized on Category 6.

If we assemble components of a certain category to best practice, we may achieve a channel of a particular class. 

- CAT5e components may provide a channel to class D performance (100MHz). This is generally used for 1Gb/s networking and typically uses RJ45 connectors.
- CAT6 components may provide a channel to class E performance (250MHz). This has replaced CAT5e for new installation. This is generally used for 1000BASE-T networking but can support 10GBASE-T over 55m. CAT6A supports 10GBASE-T over 100m. It typically uses RJ45 connectors.
- CAT7 components may provide a channel to class F performance (600MHz) and supports 10Gb/s over 100m but does not use RJ45. CAT7a provides a channel to (1000MHz).
- CAT8 components (2000MHz) supports 10Gb/s to 30m for data center use at 40BASE-T. 