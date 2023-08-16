# LEAKSTREAM

This work presents LEAKSTREAM, a novel approach for detecting leakages in water distribution networks by leveraging the power of clustering and stream processing techniques, combined with advanced machine learning approaches. Given the critical importance of efficient water management and the significant economic and environmental consequences of undetected leaks, it is crucial to develop innovative strategies that can accurately and promptly identify anomalies within distribution networks.

Our proposed method focuses on an algorithm that creates clusters of nodes in the water distribution network, taking into account their spatial proximity and hydraulic characteristics. We employ stream processing to efficiently handle large-scale real-time data generated from meters installed at consumer locations throughout the network.

The results of our study indicate that the proposed leakage detection algorithm effectively employs a generalization technique to detect events not included in the training data. We show performance in terms of precision and loss in the case of 75 different leakages positions in a water distribution network which extends in an area of 7 x 3.5 sqkm. Furthermore, its capacity to process data at the edge and in real-time enables prompt responses and mitigation measures, thereby reducing the overall impact of leaks on both the environment and infrastructure.

Our results attain an average accuracy of detecting and localizing the zone of the leakages of about 98.6% when leakages are not present during the training of the ML models.

## Requirements

All functionalities require Python 3.7 to execute.
