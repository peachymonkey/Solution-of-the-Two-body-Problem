# Solution-of-the-Two-body-Problem
This project presents a novel machine learning approach designed to efficiently solve the classical two-body problem. The inherent nature of the two-body problem involves integrating a system of second-order nonlinear ordinary differential equations. Conventional numerical integration techniques, relying on small computation steps, result in prolonged computational durations. Simultaneously, calculus has unveiled its limitations in resolving the two-body problem, inevitably converging towards an unresolved Kepler equation of transcendental nature. To tackle this issue, we integrate the conventional analytical solution based on true anomaly with a deep neural network representation of the Kepler equation. This results in a highly accurate closed-form solution solely dependent on time, termed the learning-based solution of the two-body problem. To enhance precision, a correction module based on Halley iteration is introduced, substantially improving the final solution in terms of high precision and reduced computational cost. Compared to state-of-the-art methods, such as piecewise Padé approximation, Adomian decomposition method and modified Mikkola's method, our approach achieves computational speed-ups of several thousand to tens of thousands while maintaining accuracy in large-scale orbit propagation scenarios. Empirical validation in simulated conditions underscores its effectiveness and potential value in long-term orbit prediction.

**Announcement：
We are pleased to announce that the code, datasets, and key parameters associated with our Two-Body Problem Solver project will be gradually released following the publication of our research findings.
Stay tuned for updates and thank you for your interest and support.
