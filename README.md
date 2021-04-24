# Rich Semantics Improve Few-Shot Learning

> #### Abstract :
> Human learning benefits from multi-modal inputs that often appear as rich semantics (e.g., description of an object's attributes while learning about it). This enables us to learn generalizable concepts from very limited visual examples. However, current few-shot learning (FSL) methods use numerical class labels to denote object classes which do not provide rich semantic meanings about the learned concepts. In this work, we show that by using  'class-level' language descriptions, that can be acquired with minimal annotation cost, we can improve the FSL performance. Given a support set and queries, our main idea is to create a bottleneck visual feature (hybrid prototype) which is then used to generate language descriptions of the classes as an auxiliary task during training. We develop a Transformer based forward and backward encoding mechanism to relate visual and semantic tokens that can encode intricate relationships between the two modalities. Forcing the prototypes to retain semantic information about class description acts as a regularizer on the visual features, improving their generalization to novel classes at inference. Furthermore, this strategy imposes a human prior on the learned representations, ensuring that the model is faithfully relating visual and semantic concepts, thereby improving model interpretability. Our experiments on four datasets and ablation studies show the benefit of effectively modeling rich semantics for FSL.


![alt text](https://github.com/MohamedAfham/RS_FSL/blob/main/Figures/Architecture.png?raw=true)

## Code will be released soon !!
