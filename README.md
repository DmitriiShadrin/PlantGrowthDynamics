# PlantGrowthDynamics
Tools for plant growth dynamics assessment

The paper presents a technology for plant growth dynamics estimation in an artificial soilless system. The approach consists of a hardware setup for automated image acquisition, plant feeding system, conditional monitoring and a software for automatic leaves segmentation and tracking. The software part of the system relies on a convolution neural network for instance segmentation. To train the neural network a manually [annotated dataset was made](https://www.dropbox.com/sh/7ox894u2449cr3m/AAD0gRPuSm7hTwOMek1Guu8ka).

We conducted experiments on salad. Observations were taken for 31 days with the fixed time frame of 30 minutes, resulting in a large image dataset for each plant. It was shown how obtained results on instance segmentation for a particular leaf can serve for detailed reconstruction of dynamics of plant growth.

