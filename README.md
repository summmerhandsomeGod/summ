
[English](README.md)


LongLatiNet specifically designed to address the intricate challenge of detecting anomalies in fabric texture along the warp and weft directions, which have traditionally been difficult to identify. Our methodological approach consists of three main steps: Firstly, a Dimension-Enhancement Adjustment method grounded in the Neuron Energy Function (DEA-NEF) is proposed to reconstruct the input feature map from 3-channels to 4-channels, which amplifies the anomalous values at the fabric's defect sites and thereby enabling the neural network to extract more exhaustive information. Secondly, an Adaptive Multi-scale Convolution module (AMConv) is proposed to augment the feature extraction efficacy for defects oriented along the warp and weft directions. It acts as the cornerstone in constructing a Recursive Residual Block (RRBlock), which deepens the network to enhance its multi-scale feature extraction capabilities and strengthen model robustness. Lastly, we harness the synergistic effects of a Comprehensive Spatial Pyramid Pooling-Fast (CSPPF) and Bidirectional Feature Pyramid Network (BiFPN) to fuse features across various network levels. This integration fully exploits the semantic information present in higher layers and the positional information in lower layers, consequently elevating the precision of fabric defect detection. 



