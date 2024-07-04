---
title: "Sensor fusion for needle deflection compensation"
excerpt: "We utilized Kalman filter and a needle bending model to incorporate measurements from two sensors (optical and EM) attached to a cryoablation needle to compensate for its deflection during insertion. <br/><img src='/images/fusion_figure.png'>"
collection: portfolio
---

**Purpose** In many clinical procedures such as cryoablation that involves needle insertion, accurate placement of the needle’s tip at the desired target is the major issue for optimizing the treatment and minimizing damage to the neighboring anatomy. However, due to the interaction force between the needle and tissue, considerable error in intraoperative tracking of the needle
tip can be observed as needle deflects.
**Methods** In this paper, measurements data from an optical sensor at the needle base and a magnetic resonance (MR) gradient field-driven electromagnetic (EM) sensor placed 10cm from the needle tip are used within a model-integrated Kalman filterbased sensor fusion scheme. Bending model-based estimations and EM-based direct estimation are used as the measurement vectors in the Kalman filter, thus establishing an online estimation approach.
**Results** Static tip bending experiments show that the fusion method can reduce the mean error of the tip position estimation from 29.23mm of the optical sensor-based approach to 3.15mm of the fusion-based approach and from 39.96 to 6.90mm, at the MRI isocenter and the MRI entrance, respectively.
**Conclusion** Thiswork established a novel sensor fusion scheme that incorporates model information, which enables real-time tracking of needle deflection with MRI compatibility, in a free-hand operating setup. 

Publications: [IJCARS-paper](https://link.springer.com/article/10.1007/s11548-018-1708-8)