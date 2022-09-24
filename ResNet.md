##  Intention
- The deeper network has higher training error, and this test error.
## Main Idea
- The deeper network with fully train can definitely works no worse than simple network, because after achieving the best score, you can still add layers which form an identity mapping to ensure the performance wouldn't get worse.
- The gradient will become larger by using residual blocks. d F(g(x))-> d F(g(x))+g(x)