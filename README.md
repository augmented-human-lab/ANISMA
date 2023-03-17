
**ANISMA Main Repository** <-- You are here!
* [ANISMA Software](https://github.com/augmented-human-lab/ANISMA-software)
* [ANISMA Controller Board](https://github.com/augmented-human-lab/ANISMA-controller-board)
* [ANISMA Driver Board](https://github.com/augmented-human-lab/ANISMA-driver-board)

# Introduction
![ANISMA_banner](https://ahlab.org/wp-content/uploads/2021/09/ANISMA_logo_sm.jpg)

ANISMA is a software and hardware toolkit to prototype on-skin haptic devices that generate skin deformation stimuli like pressure, stretch, and motion using shape-memory alloys (SMAs). The toolkit embeds expert knowledge that makes SMA spring actuators more accessible to researchers and anyone interested. Using the software tool, users can design different actuator layouts, program their spatio-temporal actuation and preview the resulting deformation behavior to verify a design. The toolkit allows exporting the actuator layout and 3D printing it directly on skin adhesive. To test different actuation sequences on the skin, a user can connect the SMA actuators to a customized driver board and reprogram them using our visual programming interface.

All parts of ANISMA are fully open-source. This repository links to three repositories for its different components.  

# ANISMA Components
ANISMA consists of three main parts:
1. The [ANISMA Software](https://github.com/augmented-human-lab/ANISMA-software)
2. The [ANISMA Controller Board](https://github.com/augmented-human-lab/ANISMA-controller-board)
3. The [ANISMA Driver Board](https://github.com/augmented-human-lab/ANISMA-driver-board)

In short, ANISMA Software is a standalone software to design and animate virtual ANISMA skin-deformation devices. You can try it straight away without any hardware parts.
The ANISMA Controller and Driver Board comprise the hardware parts to control ANISMA devices. 

ANISMA Software can communicate with and program the ANISMA Controller Board depending on the animation sequence.
The Controller Board in turn uses the Driver Board to actuate ANISMA devices.

ANISMA Software --> ANISMA Controller Board --> ANISMA Driver Board

# ANISMA Workflow
Click on the following image to watch the workflow on youtube.
[![Watch ANISMA Workflow on YouTube](https://user-images.githubusercontent.com/62531877/225813476-4e71f8e7-e72a-4d61-bce1-210ebdbec084.jpg)](https://youtu.be/0hwP_USbstA)

# Hardware Kit components

Apart from the Controller and Driver Board the hardware Kit consists of the following items:
We provide a full list with links and ways to purchase the items we used for our experiments. Some of these parts may not available due to stock shortage. However, many of these parts may be substituted. 

| Name               | URL                                                                                               | Part Number               | Count (Recommended Minimum) | Comment                                           |
|--------------------|---------------------------------------------------------------------------------------------------|---------------------------|-----------------------------|---------------------------------------------------|
| Nodes              | https://www.pcbway.com/project/shareproject/ANISMA_Node_cd43db88.html                             | -                         | 8                           |                                                   |
| Pin Header         | https://www.digikey.com/en/products/detail/phoenix-contact/1945193/950887                         | 277-1759-ND               | 2                           |                                                   |
| Jumper Cable       | https://www.digikey.com/en/products/detail/sparkfun-electronics/PRT-12796/5993861                 | 1568-1513-ND              | 1                           | longer recommended                                |
| Socket             | https://www.digikey.com/en/products/detail/hirose-electric-co-ltd/DF59M-1S-H-21/5226337           | DF59M-1S-H(21)            | 32                          |                                                   |
| Connector          | https://www.digikey.com/en/products/detail/hirose-electric-co-ltd/DF59M-2628PCF/5226341           | DF59M-2628PCF             | 32                          |                                                   |
| SMA Spring         | https://www.dynalloy.com/tech_data_springs.php                                                    | FLEXINOL® Actuator Spring | 10                          | For specific parameters, refer to ANISMA Software |
| Skin Adhesive Tape | https://www.chemistwarehouse.com.au/buy/106518/primafix-plus-conformable-retention-tape-10cm-x-2m | PRIMAFIX Plus             | 1                           | Or similar product                                |
|                    |                                                                                                   |                           |                             |                                                   |

To print the layout with node moutns on skin adhesive we used Prusa i3 3D Printer and PLA Filament.
