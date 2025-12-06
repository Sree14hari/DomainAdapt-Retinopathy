While deep learning has shown remarkable potential for automated Diabetic
Retinopathy (DR) detection, existing models often exhibit poor generalization
when deployed in clinical environments that differ from their training distribution. This limitation arises from domain shift, caused by variations in imaging
sensors, illumination conditions, and patient demographics. To overcome this
interoperability challenge, this project introduces an Unsupervised Domain Adaptation (UDA) framework capable of transferring diagnostic knowledge across heterogeneous datasets without requiring target-domain annotations. The proposed
system employs a Domain-Adversarial Neural Network (DANN) that integrates
a ResNet18 feature extractor with a Gradient Reversal Layer (GRL). Through
adversarial training, the model is encouraged to learn feature representations that
remain discriminative for DR severity while being invariant to dataset-specific
characteristics from either the source (EyePACS) or target (Messidor-2) domains.
By aligning feature distributions across these disparate datasets, the framework
aims to establish a robust, scanner-agnostic DR screening tool capable of maintaining high diagnostic sensitivity in real-world clinical deployments.
