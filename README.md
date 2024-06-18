# General parameter-shift rules for quantum gradients

Authors of paper: David Wierichs, Josh Izaac, Cody Wang, and Cedric Yen-Yu Lin

Link to paper: https://quantum-journal.org/papers/q-2022-03-30-677/#

Abstract of paper: _Variational quantum algorithms are ubiquitous in applications of noisy intermediate-scale quantum computers. Due to the structure of conventional parametrized quantum gates, the evaluated functions typically are finite Fourier series of the input parameters. In this work, we use this fact to derive new, general parameter-shift rules for single-parameter gates, and provide closed-form expressions to apply them. These rules are then extended to multi-parameter quantum gates by combining them with the stochastic parameter-shift rule. We perform a systematic analysis of quantum resource requirements for each rule, and show that a reduction in resources is possible for higher-order derivatives. Using the example of the quantum approximate optimization algorithm, we show that the generalized parameter-shift rule can reduce the number of circuit evaluations significantly when computing derivatives with respect to parameters that feed into many gates. Our approach additionally reproduces reconstructions of the evaluated function up to a chosen order, leading to known generalizations of the Rotosolve optimizer and new extensions of the quantum analytic descent optimization algorithm._

Notebook by: [Óscar Amaro](https://github.com/OsAmaro)
