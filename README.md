# Few_Shot_DL

This project explores the challenges of training deep learning models in data-scarce scenarios. It is structured in two main parts.

In the first challenge, the task was to classify CIFAR-10 images using only 25 training samples per class, without relying on any external data or pre-trained models. This required carefully tuning small models from scratch, pushing the limits of generalization under severe data constraints.

The second challenge introduced the possibility of leveraging pre-trained networks. I experimented with transfer learning by fine-tuning architectures such as ResNet-18 and ResNet-50. To push further, I also implemented Model-Agnostic Meta-Learning (MAML), enabling the model to quickly adapt to new tasks from limited data. While the MAML implementation was technically successful, it did not yield significantly impactful results in this specific setting.

All experiments were tracked and analyzed using Weights & Biases. This project allowed me to compare different learning strategies—from naive training to meta-learning—while understanding their trade-offs in few-shot learning contexts.

Further explanations and methodological insights can be found in the written report.
The best-performing models and results are available in the notebook titled __notebooks/40316218_DL_Project_Best_Approach.ipynb_.
Additional experiments, including the full MAML implementation and other exploratory approaches, are documented in the appendix notebook __notebooks/40316218_DL_Project_Appendix.ipynb_.
