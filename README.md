🧠 Thesis Summary: Unsupervised Estimation of Classifier Accuracy via Agreement Patterns (Ongoing)
This ongoing thesis explores how to estimate the accuracy of multiple classifiers without access to labeled data, relying only on agreement patterns between their predictions. Building on the Dawid-Skene model, it implements an Expectation-Maximization (EM) algorithm to jointly infer latent true labels and per-classifier accuracy.

Classifiers are implemented in PyTorch, and each one is trained on a different distribution of the Fashion-MNIST dataset. This setup creates a diverse ensemble where individual models specialize in different subsets of classes—mirroring real-world conditions like crowdsourcing or weak supervision.

Alongside the EM-based method, the work evaluates simpler unsupervised techniques such as average pairwise agreement, confidence-weighted voting, and a leave-one-out majority vote heuristic.

The goal is to build a robust framework for unsupervised evaluation of ensemble models, with applications in weak labeling, quality control, and settings where ground truth is unavailable.


