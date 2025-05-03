# Few_Shot_DL

This project explores the challenges of training deep learning models in data-scarce scenarios. It is structured in two main parts.

In the first challenge, the task was to classify CIFAR-10 images using only 25 training samples per class, without relying on any external data or pre-trained models. This required carefully tuning small models from scratch, pushing the limits of generalization under severe data constraints.

The second challenge introduced the possibility of leveraging pre-trained networks. I experimented with transfer learning by fine-tuning architectures such as ResNet-18 and ResNet-50. To push further, I also implemented Model-Agnostic Meta-Learning (MAML), enabling the model to quickly adapt to new tasks from limited data.

All experiments were tracked and analyzed using Weights & Biases. This project allowed me to compare different learning strategies—from naive training to meta-learning—while understanding their trade-offs in few-shot learning contexts.
