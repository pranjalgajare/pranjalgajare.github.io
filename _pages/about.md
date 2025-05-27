---
permalink: /
title: " "
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Pranjal Gajare, a PhD Student at the School of Computer and Electrical Engineering at [Georgia Institute of Technology](https://www.gatech.edu/) working on control and stability analysis of inverter-based-resources. I am affiliated with the [Center for Distributed Energy (CDE) at Georgia Tech](https://cde.gatech.edu/), where I am advised by [Prof. Deepak Divan](https://ece.gatech.edu/directory/deepakraj-m-divan). I graduated with my Bachelor of Technology in Electrical Engineering from the [Indian Institute of Technology Roorkee](https://www.iitr.ac.in/) and am fortunate to have worked with [Prof. Anubrata Dey](https://www.iitr.ac.in/~EE/Anubrata_Dey). During my undergraduate degree, I was a visiting researcher with the [Chair of Power Electronics at Kiel University](https://www.uni-kiel.de/en/tf/research/institute-etit/power-electronics) with [Prof. Marco Liserre](https://www.uni-kiel.de/en/person/liserre-marco-50519).

## Research Interests

My research interests broadly revolve around Power Electronics and its role in future power systems, driven by the explosive growth of distributed energy resources on the grid. My current research interests include studying interactions in multi-inverter systems and designing controls for inverters to prevent adverse interactions. I have also worked on current sensor design for utility applications in the early part of my PhD. During my undergraduate studies, I worked on converter hardware and control design for multilevel inverters, including MMCs, 3L-NPC, and ANPC for medium voltage drives and active power filter applications. Some of my major projects are listed below:

### Interoperability and Scalability in Grid-forming Inverters 
As the penetration of distributed energy resources (DERs) in the grid increases, grid-forming (GFM) inverters are being touted as a cornerstone for realizing these multi-inverter systems. Fundamental to the idea is the need for multiple sources from different vendors and varying power ratings to collaborate and form a stable grid. To enable this, we propose a control framework based on time-scale separation to guide the principles for interoperability between grid-interactive inverters from different vendors and technologies. I am currently developing control algorithms that can be adapted to this middle layer formulation and preparing a reference design for use by UNIFI stakeholder industries. 

The formulation divides the controls for GFM inverters across three timescales and specifies the requirements for each timescale. For the fast timescales, impedance passivity is specified as the required criterion. For the slow timescales, a comparative study is performed to propose a GFM control with superior disturbance-rejection properties. More details about the control algorithms and the framework can be found in the following publications:

1. P. M. Gajare, J. Benzaquen and D. Divan, "Grid-Forming Controller with Enhanced Disturbance Rejection," IEEE Journal of Emerging and Selected Topics in Power Electronics. [(link)](https://ieeexplore.ieee.org/document/11007119)
2. P. M. Gajare, J. Benzaquen, and D. Divan, “Universal Interoperable Control Framework for Inverter-Based-Resources,” in 2024 IEEE 15th International Symposium on Power Electronics for Distributed Generation Systems (PEDG), Luxembourg. [(link)](https://ieeexplore.ieee.org/document/10667356)
3. M. Miranbeigi, P. M. Gajare, J. Benzaquen, P. Kandula and D. Divan, "On the Passivity of Grid-Forming Converters — Role of Virtual Impedance," in 2022 IEEE Applied Power Electronics Conference and Exposition (APEC), Houston, TX, USA, 2022, pp. 650-656. [(link)](https://ieeexplore.ieee.org/document/9773656)

The project is funded by the U.S. Department of Energy through the [UNIFI consortium](https://unificonsortium.org/).

### High-bandwidth Universal AC/DC Current Sensor Design for Utility Applications
The power grid is undergoing a significant transformation as an increasing number of DERs, often a combination of DC and AC resources, are integrated into the grid. As essential components in metering and control systems for integrating DERs, low-cost sensors with a small form factor, easy installation, and AC/DC measuring capability are required. In this work, a switched-Rogowski current sensor along with its novel operation is proposed to achieve both DC and AC measuring capabilities with an introduced switching element. It retains the benefits of the Rogowski coil in high bandwidth, low cost, and inherent isolation. Miniaturized and cost-effective metering systems can thus be realized with integrated local data processing and communication functionalities, which are essential to enable a decentralized smart grid. More details on the design and performance of the system can be found in the following publications and patent:

1. P.M. Gajare, S. Kulkarni, D. Divan and R. Hao, “Universal AC/DC Current Sensor and Isolator” US patent 18/694,294. [(link)](https://patentimages.storage.googleapis.com/28/e2/17/766b8de54b842e/US20250132089A1.pdf)
2. R. Hao, P. M. Gajare, S. Kulkarni, J. Benzaquen and D. Divan, “A Low-cost Miniature DC/AC-compatible Switched-Rogowski Current Sensor,” in 2023 IEEE Energy Conversion Congress and Exposition (ECCE), Nashville, TN, USA. [(link)](https://ieeexplore.ieee.org/abstract/document/10362623)

### 
