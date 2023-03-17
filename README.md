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
