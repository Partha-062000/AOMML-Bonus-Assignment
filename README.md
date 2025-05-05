# AOMML-Bonus-Assignment
In this work, we propose a novel optimization algorithm that combines Proximal Gradient
Descent with Nesterov Momentum to address weakly smooth objective functions under the
Polyak–Lojasiewicz (PL) inequality. Weakly smooth objectives, characterized by Hölder conti-
nuity of the gradient, present unique challenges for traditional optimization methods due to their
irregular and non-uniform smoothness properties. By integrating Nesterov momentum into the
proximal framework, our algorithm achieves accelerated convergence while maintaining robustness
in handling non-differentiable regularizers. We provide a comprehensive theoretical analysis of the
algorithm’s convergence, demonstrating its ability to achieve sublinear convergence rates under the PL
inequality. To validate the practical effectiveness of the proposed method, we apply it to a sparse sig-
nal recovery problem, a real-world application involving noisy measurements and high-dimensional
data. The results demonstrate that the algorithm successfully recovers the underlying sparse signal
while achieving competitive performance compared to existing state-of-the-art techniques. This work
contributes to the growing body of research on optimization methods for weakly smooth objectives,
offering both theoretical insights and practical utility for applications in machine learning, signal
processing, and beyond.
