# CEGCN

CNN-Enhanced Graph Convolutional Network with Pixel- and Superpixel-Level Feature Fusion for Hyperspectral Image Classification

has been accepted by IEEE Transactions on Geoscience and Remote Sensing (TGRS)

Abstract: Recently, the graph convolutional network (GCN) has drawn increasing attention in hyperspectral image (HSI) classification. Compared with the convolutional neural network (CNN) with fixed square kernels, GCN can explicitly utilize the correlation between adjacent land covers and conduct flexible convolution on arbitrarily irregular image regions; hence, the HSI spatial contextual structure can be better modeled. However, to reduce the computational complexity and promote the semantic structure learning of land covers, GCN usually works on superpixel-based nodes rather than pixel-based nodes; thus, the pixel-level spectral-spatial features cannot be captured. To fully leverage the advantages of the CNN and GCN, we propose a heterogeneous deep network called CNN-enhanced GCN (CEGCN), in which CNN and GCN branches perform feature learning on small-scale regular regions and large-scale irregular regions, and generate complementary spectral-spatial features at pixel and superpixel levels, respectively. To alleviate the structural incompatibility of the data representation between the Euclidean data-oriented CNN and non-Euclidean data-oriented GCN, we propose the graph encoder and decoder to propagate features between image pixels and graph nodes, thus enabling the CNN and GCN to collaborate in a single network. In contrast to other GCN-based methods that encode HSI into a graph during preprocessing, we integrate the graph encoding process into the network and learn edge weights from training data, which can promote the node feature learning and make the graph more adaptive to HSI content. Extensive experiments on three data sets demonstrate that the proposed CEGCN is both qualitatively and quantitatively competitive compared with other state-of-the-art methods.

Environment: 
Python 3.6
PyTorch 1.5


Early Access is available now at https://ieeexplore.ieee.org/document/9268479

If this work is helpful to you, please citing our work as follows: 

Q. Liu, L. Xiao, J. Yang and Z. Wei, "CNN-Enhanced Graph Convolutional Network With Pixel- and Superpixel-Level Feature Fusion for Hyperspectral Image Classification," in IEEE Transactions on Geoscience and Remote Sensing, doi: 10.1109/TGRS.2020.3037361.

Or

@ARTICLE{9268479,  author={Q. {Liu} and L. {Xiao} and J. {Yang} and Z. {Wei}},  journal={IEEE Transactions on Geoscience and Remote Sensing},   title={CNN-Enhanced Graph Convolutional Network With Pixel- and Superpixel-Level Feature Fusion for Hyperspectral Image Classification},   year={2020},  volume={},  number={},  pages={1-15},  doi={10.1109/TGRS.2020.3037361}}


Note that the code is stinky and long.
