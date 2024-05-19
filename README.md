# GOTHAM--Graph-based-Class-Incremental-Learning-Framework-under-Weak-Supervision

Graphs are growing rapidly and so are the number of different categories associated with it.  Applications like e-commerce, healthcare, recommendation systems, and various social media platforms are rapidly moving towards graph representation of data due to their ability to capture both structural and attribute information. One crucial task in graph analysis is node classification, where unlabeled nodes are categorized into predefined classes. In practice, novel classes appear incrementally sometimes with just a few labels (seen classes) or even without any labels (unseen classes), either because they are new or haven't been explored much. Traditional methods assume abundant labeled data for training, which isn't always feasible. We investigate a broader objective: \emph{Graph Class Incremental Learning under Weak Supervision (GCL)}, addressing this challenge by meta-training on base classes with limited labeled instances.  During the incremental streams, novel classes can have few-shot or zero-shot representation. Our proposed framework GOTHAM efficiently accommodates these unlabeled nodes by finding the closest prototype representation, serving as class representatives in the attribute space. For Text-Attributed Graphs (TAGs), our framework additionally incorporates semantic information to enhance the representation. By employing teacher-student knowledge distillation to mitigate forgetting, GOTHAM achieves promising results across various tasks. Experiments on datasets such as Cora-ML, Amazon, and OBGN-Arxiv showcase the effectiveness of our approach in handling evolving graph data under limited supervision.
