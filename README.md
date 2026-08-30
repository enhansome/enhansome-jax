<!--lint ignore double-link-->

# Awesome JAX with stars

<!--lint ignore double-link-->

[JAX](https://github.com/google/jax) ⭐ 36,226 | 🐛 2,493 | 🌐 Python | 📅 2026-08-30 brings automatic differentiation and the [XLA compiler](https://www.tensorflow.org/xla) together through a [NumPy](https://numpy.org/)-like API for high performance machine learning research on accelerators like GPUs and TPUs.

<!--lint enable double-link-->

This is a curated list of awesome JAX libraries, projects, and other resources. Contributions are welcome!

## Contents

* [Papers](#papers)<https://github.com/jax-ml/jax> ⭐ 36,226 | 🐛 2,493 | 🌐 Python | 📅 2026-08-30
* [Libraries](#libraries)
* [Models and Projects](#models-and-projects)
* [Videos](#videos)
* [Tutorials and Blog Posts](#tutorials-and-blog-posts)
* [Books](#books)
* [Community](#community)

<a name="libraries" />

## Libraries

* [NumPyro](https://github.com/pyro-ppl/numpyro) ⭐ 2,750 | 🐛 75 | 🌐 Python | 📅 2026-08-28 - Probabilistic programming based on the Pyro library. <img src="https://img.shields.io/github/stars/pyro-ppl/numpyro?style=social" align="center">
* [EasyLM](https://github.com/young-geng/EasyLM) ⭐ 2,514 | 🐛 32 | 🌐 Python | 📅 2024-08-13 - LLMs made easy: Pre-training, finetuning, evaluating and serving LLMs in JAX/Flax.  <img src="https://img.shields.io/github/stars/young-geng/EasyLM?style=social" align="center">
* [Optax](https://github.com/deepmind/optax) ⭐ 2,327 | 🐛 110 | 🌐 Python | 📅 2026-08-29 - Gradient processing and optimization library. <img src="https://img.shields.io/github/stars/deepmind/optax?style=social" align="center">
* [cvxpylayers](https://github.com/cvxgrp/cvxpylayers) ⭐ 2,130 | 🐛 23 | 🌐 Python | 📅 2026-05-19 - Construct differentiable convex optimization layers. <img src="https://img.shields.io/github/stars/cvxgrp/cvxpylayers?style=social" align="center">
* [TensorLy](https://github.com/tensorly/tensorly) ⭐ 1,691 | 🐛 76 | 🌐 Python | 📅 2025-11-16 - Tensor learning made simple. <img src="https://img.shields.io/github/stars/tensorly/tensorly?style=social" align="center">
* [JAX, M.D.](https://github.com/google/jax-md) ⭐ 1,458 | 🐛 37 | 🌐 Jupyter Notebook | 📅 2026-08-18 - Accelerated, differential molecular dynamics. <img src="https://img.shields.io/github/stars/google/jax-md?style=social" align="center">
* [RLax](https://github.com/deepmind/rlax) ⭐ 1,441 | 🐛 24 | 🌐 Python | 📅 2026-08-06 - Library for implementing reinforcement learning agents. <img src="https://img.shields.io/github/stars/deepmind/rlax?style=social" align="center">
* [BlackJAX](https://github.com/blackjax-devs/blackjax) ⭐ 1,117 | 🐛 49 | 🌐 Python | 📅 2026-08-28 - Library of samplers for JAX. <img src="https://img.shields.io/github/stars/blackjax-devs/blackjax?style=social" align="center">
* [Dynamax](https://github.com/probml/dynamax) ⭐ 1,002 | 🐛 71 | 🌐 Python | 📅 2026-08-26 - Probabilistic state space models. <img src="https://img.shields.io/github/stars/probml/dynamax?style=social" align="center">
* [Chex](https://github.com/deepmind/chex) ⭐ 955 | 🐛 77 | 🌐 Python | 📅 2026-08-06 - Utilities to write and test reliable JAX code. <img src="https://img.shields.io/github/stars/deepmind/chex?style=social" align="center">
* [Fortuna](https://github.com/awslabs/fortuna) ⚠️ Archived - AWS library for Uncertainty Quantification in Deep Learning. <img src="https://img.shields.io/github/stars/awslabs/fortuna?style=social" align="center">
* [Levanter](https://github.com/stanford-crfm/levanter) ⭐ 713 | 🐛 25 | 🌐 Python | 📅 2026-01-26 - Legible, Scalable, Reproducible Foundation Models with Named Tensors and JAX.  <img src="https://img.shields.io/github/stars/stanford-crfm/levanter?style=social" align="center">
* [NetKet](https://github.com/netket/netket) ⭐ 693 | 🐛 100 | 🌐 Python | 📅 2026-08-18 - Machine Learning toolbox for Quantum Physics. <img src="https://img.shields.io/github/stars/netket/netket?style=social" align="center">
* [Distrax](https://github.com/deepmind/distrax) ⭐ 650 | 🐛 60 | 🌐 Python | 📅 2026-07-30 - Reimplementation of TensorFlow Probability, containing probability distributions and bijectors. <img src="https://img.shields.io/github/stars/deepmind/distrax?style=social" align="center">
* [Coax](https://github.com/coax-dev/coax) ⭐ 186 | 🐛 7 | 🌐 Python | 📅 2023-02-01 - Turn RL papers into code, the easy way. <img src="https://img.shields.io/github/stars/coax-dev/coax?style=social" align="center">
* Neural Network Libraries
  * [HuggingFace Transformers](https://github.com/huggingface/transformers) ⭐ 164,629 | 🐛 2,401 | 🌐 Python | 📅 2026-08-30 - Ecosystem of pretrained Transformers for a wide range of natural language tasks (Flax). <img src="https://img.shields.io/github/stars/huggingface/transformers?style=social" align="center">
  * [Trax](https://github.com/google/trax) ⚠️ Archived - "Batteries included" deep learning library focused on providing solutions for common workloads. <img src="https://img.shields.io/github/stars/google/trax?style=social" align="center">
  * [Flax](https://github.com/google/flax) ⭐ 7,308 | 🐛 516 | 🌐 Jupyter Notebook | 📅 2026-08-24 - Centered on flexibility and clarity. <img src="https://img.shields.io/github/stars/google/flax?style=social" align="center">
  * [Flax NNX](https://github.com/google/flax/tree/main/flax/nnx) ⭐ 7,308 | 🐛 516 | 🌐 Jupyter Notebook | 📅 2026-08-24 - An evolution on Flax by the same team <img src="https://img.shields.io/github/stars/google/flax?style=social" align="center">
  * [Scenic](https://github.com/google-research/scenic) ⭐ 3,821 | 🐛 305 | 🌐 Python | 📅 2026-08-28 - A Jax Library for Computer Vision Research and Beyond.  <img src="https://img.shields.io/github/stars/google-research/scenic?style=social" align="center">
  * [Haiku](https://github.com/deepmind/dm-haiku) ⭐ 3,277 | 🐛 105 | 🌐 Python | 📅 2026-08-25 - Focused on simplicity, created by the authors of Sonnet at DeepMind. <img src="https://img.shields.io/github/stars/deepmind/dm-haiku?style=social" align="center">
  * [Equinox](https://github.com/patrick-kidger/equinox) ⭐ 2,962 | 🐛 248 | 🌐 Python | 📅 2026-08-10 - Callable PyTrees and filtered JIT/grad transformations => neural networks in JAX. <img src="https://img.shields.io/github/stars/patrick-kidger/equinox?style=social" align="center">
  * [Neural Tangents](https://github.com/google/neural-tangents) ⚠️ Archived - High-level API for specifying neural networks of both finite and *infinite* width. <img src="https://img.shields.io/github/stars/google/neural-tangents?style=social" align="center">
  * [Penzai](https://github.com/google-deepmind/penzai) ⚠️ Archived - Prioritizes legibility, visualization, and easy editing of neural network models with composable tools and a simple mental model.  <img src="https://img.shields.io/github/stars/google-deepmind/penzai?style=social" align="center">
  * [Jraph](https://github.com/deepmind/jraph) ⚠️ Archived - Lightweight graph neural network library. <img src="https://img.shields.io/github/stars/deepmind/jraph?style=social" align="center">
  * [Objax](https://github.com/google/objax) ⚠️ Archived - Has an object oriented design similar to PyTorch. <img src="https://img.shields.io/github/stars/google/objax?style=social" align="center">
  * [Elegy](https://poets-ai.github.io/elegy/) - A High Level API for Deep Learning in JAX. Supports Flax, Haiku, and Optax. <img src="https://img.shields.io/github/stars/poets-ai/elegy?style=social" align="center">

<a name="new-libraries" />

### New Libraries

This section contains libraries that are well-made and useful, but have not necessarily been battle-tested by a large userbase yet.

* [ALX](https://github.com/google-research/google-research/tree/master/alx) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Open-source library for distributed matrix factorization using Alternating Least Squares, more info in [*ALX: Large Scale Matrix Factorization on TPUs*](https://arxiv.org/abs/2112.02194).
* [Oryx](https://github.com/tensorflow/probability/tree/master/spinoffs/oryx) ⭐ 4,431 | 🐛 726 | 🌐 Jupyter Notebook | 📅 2026-08-06 - Probabilistic programming language based on program transformations.
* [BRAX](https://github.com/google/brax) ⭐ 3,227 | 🐛 109 | 🌐 Jupyter Notebook | 📅 2026-08-06 - Differentiable physics engine to simulate environments along with learning algorithms to train agents for these environments. <img src="https://img.shields.io/github/stars/google/brax?style=social" align="center">
* [Mctx](https://github.com/deepmind/mctx) ⭐ 2,655 | 🐛 7 | 🌐 Python | 📅 2026-08-06 - Monte Carlo tree search algorithms in native JAX. <img src="https://img.shields.io/github/stars/deepmind/mctx?style=social" align="center">
* [MaxText](https://github.com/google/maxtext) ⭐ 2,406 | 🐛 312 | 🌐 Python | 📅 2026-08-30 - A simple, performant and scalable Jax LLM written in pure Python/Jax and targeting Google Cloud TPUs. <img src="https://img.shields.io/github/stars/google/maxtext?style=social" align="center">
* [Diffrax](https://github.com/patrick-kidger/diffrax) ⭐ 2,091 | 🐛 239 | 🌐 Python | 📅 2026-06-21 - Numerical differential equation solvers in JAX. <img src="https://img.shields.io/github/stars/patrick-kidger/diffrax?style=social" align="center">
* [purejaxrl](https://github.com/luchris429/purejaxrl) ⭐ 1,100 | 🐛 19 | 🌐 Python | 📅 2024-09-09 - Vectorisable, end-to-end RL algorithms in JAX. <img src="https://img.shields.io/github/stars/luchris429/purejaxrl?style=social" align="center">
* [EvoJAX](https://github.com/google/evojax) ⚠️ Archived - Hardware-Accelerated Neuroevolution <img src="https://img.shields.io/github/stars/google/evojax?style=social" align="center">
* [gymnax](https://github.com/RobertTLange/gymnax) ⭐ 916 | 🐛 1 | 🌐 Python | 📅 2026-08-30 - Reinforcement Learning Environments with the well-known gym API. <img src="https://img.shields.io/github/stars/RobertTLange/gymnax?style=social" align="center">
* [Jumanji](https://github.com/instadeepai/jumanji) ⭐ 859 | 🐛 27 | 🌐 Python | 📅 2026-08-24 - A Suite of Industry-Driven Hardware-Accelerated RL Environments written in JAX. <img src="https://img.shields.io/github/stars/instadeepai/jumanji?style=social" align="center">
* [evosax](https://github.com/RobertTLange/evosax) ⭐ 790 | 🐛 3 | 🌐 Python | 📅 2026-08-17 - JAX-Based Evolution Strategies <img src="https://img.shields.io/github/stars/RobertTLange/evosax?style=social" align="center">
* [OTT-JAX](https://github.com/ott-jax/ott) ⭐ 755 | 🐛 63 | 🌐 Python | 📅 2026-06-14 - Optimal transport tools in JAX. <img src="https://img.shields.io/github/stars/ott-jax/ott?style=social" align="center">
* [GPJax](https://github.com/thomaspinder/GPJax) ⭐ 658 | 🐛 27 | 🌐 Python | 📅 2026-08-25 - Gaussian processes in JAX.
* [Pgx](http://github.com/sotetsuk/pgx) ⭐ 641 | 🐛 57 | 🌐 Python | 📅 2025-03-06 - Vectorized board game environments for RL with an AlphaZero example. <img src="https://img.shields.io/github/stars/sotetsuk/pgx?style=social" align="center">
* [Pax](https://github.com/google/paxml) ⭐ 558 | 🐛 30 | 🌐 Python | 📅 2026-08-07 - A Jax-based machine learning framework for training large scale models. <img src="https://img.shields.io/github/stars/google/paxml?style=social" align="center">
* [mpi4jax](https://github.com/PhilipVinc/mpi4jax) ⭐ 543 | 🐛 25 | 🌐 Python | 📅 2026-08-25 - Combine MPI operations with your Jax code on CPUs and GPUs. <img src="https://img.shields.io/github/stars/PhilipVinc/mpi4jax?style=social" align="center">
* [XLB](https://github.com/Autodesk/XLB) ⭐ 503 | 🐛 15 | 🌐 Python | 📅 2026-05-29 - A Differentiable Massively Parallel Lattice Boltzmann Library in Python for Physics-Based Machine Learning. <img src="https://img.shields.io/github/stars/Autodesk/XLB?style=social" align="center">
* [PIX](https://github.com/deepmind/dm_pix) ⭐ 446 | 🐛 2 | 🌐 Python | 📅 2026-08-25 - PIX is an image processing library in JAX, for JAX. <img src="https://img.shields.io/github/stars/deepmind/dm_pix?style=social" align="center">
* [JAX Toolbox](https://github.com/NVIDIA/JAX-Toolbox) ⭐ 428 | 🐛 49 | 🌐 Python | 📅 2026-08-30 - Nightly CI and optimized examples for JAX on NVIDIA GPUs using libraries such as T5x, Paxml, and Transformer Engine. <img src="https://img.shields.io/github/stars/NVIDIA/JAX-Toolbox?style=social" align="center">
* [EasyDeL](https://github.com/erfanzar/EasyDeL) ⭐ 373 | 🐛 15 | 🌐 Python | 📅 2026-08-22 - EasyDeL 🔮 is an OpenSource Library to make your training faster and more Optimized With cool Options for training and serving (Llama, MPT, Mixtral, Falcon, etc) in JAX <img src="https://img.shields.io/github/stars/erfanzar/EasyDeL?style=social" align="center">
* [QDax](https://github.com/adaptive-intelligent-robotics/QDax) ⭐ 361 | 🐛 27 | 🌐 Python | 📅 2025-10-30 - Quality Diversity optimization in Jax. <img src="https://img.shields.io/github/stars/adaptive-intelligent-robotics/QDax?style=social" align="center">
* [tinygp](https://github.com/dfm/tinygp) ⭐ 347 | 🐛 33 | 🌐 Python | 📅 2026-08-03 - The *tiniest* of Gaussian process libraries in JAX. <img src="https://img.shields.io/github/stars/dfm/tinygp?style=social" align="center">
* [FDTDX](https://github.com/ymahlau/fdtdx) ⭐ 341 | 🐛 47 | 🌐 Python | 📅 2026-08-24 - Finite-Difference Time-Domain Electromagnetic Simulations in JAX <img src="https://img.shields.io/github/stars/ymahlau/fdtdx?style=social" align="center">
* [jaxlie](https://github.com/brentyi/jaxlie) ⭐ 338 | 🐛 7 | 🌐 Python | 📅 2025-04-24 - Lie theory library for rigid body transformations and optimization. <img src="https://img.shields.io/github/stars/brentyi/jaxlie?style=social" align="center">
* [mcx](https://github.com/rlouf/mcx) ⭐ 332 | 🐛 19 | 🌐 Python | 📅 2024-03-20 - Express & compile probabilistic programs for performant inference. <img src="https://img.shields.io/github/stars/rlouf/mcx?style=social" align="center">
* [KFAC-JAX](https://github.com/deepmind/kfac-jax) ⭐ 329 | 🐛 24 | 🌐 Python | 📅 2026-08-28 - Second Order Optimization with Approximate Curvature for NNs. <img src="https://img.shields.io/github/stars/deepmind/kfac-jax?style=social" align="center">
* [SPU](https://github.com/secretflow/spu) ⭐ 325 | 🐛 41 | 🌐 C++ | 📅 2026-08-27 - A domain-specific compiler and runtime suite to run JAX code with MPC(Secure Multi-Party Computation). <img src="https://img.shields.io/github/stars/secretflow/spu?style=social" align="center">
* [dynamiqs](https://github.com/dynamiqs/dynamiqs) ⭐ 317 | 🐛 26 | 🌐 Python | 📅 2026-08-30 - High-performance and differentiable simulations of quantum systems with JAX. <img src="https://img.shields.io/github/stars/dynamiqs/dynamiqs?style=social" align="center">
* [flaxmodels](https://github.com/matthias-wright/flaxmodels) ⭐ 267 | 🐛 5 | 🌐 Python | 📅 2025-03-21 - Pretrained models for Jax/Flax. <img src="https://img.shields.io/github/stars/matthias-wright/flaxmodels?style=social" align="center">
* [jax-cosmo](https://github.com/DifferentiableUniverseInitiative/jax_cosmo) ⭐ 245 | 🐛 61 | 🌐 Python | 📅 2025-06-27 - Differentiable cosmology library. <img src="https://img.shields.io/github/stars/DifferentiableUniverseInitiative/jax_cosmo?style=social" align="center">
* [flowjax](https://github.com/danielward27/flowjax) ⭐ 242 | 🐛 4 | 🌐 Python | 📅 2026-06-21 - Distributions and normalizing flows built as equinox modules. <img src="https://img.shields.io/github/stars/danielward27/flowjax?style=social" align="center">
* [torchax](https://github.com/google/torchax/) ⭐ 238 | 🐛 17 | 🌐 Python | 📅 2026-08-07 - torchax is a library for Jax to interoperate with model code written in PyTorch.<img src="https://img.shields.io/github/stars/google/torchax?style=social" align="center">
* [jwave](https://github.com/ucl-bug/jwave) ⭐ 215 | 🐛 43 | 🌐 Python | 📅 2026-03-22 - A library for differentiable acoustic simulations <img src="https://img.shields.io/github/stars/ucl-bug/jwave?style=social" align="center">
* [Optimal Transport Tools](https://github.com/google-research/ott) ⚠️ Archived - Toolbox that bundles utilities to solve optimal transport problems.
* [tree-math](https://github.com/google/tree-math) ⚠️ Archived - Convert functions that operate on arrays into functions that operate on PyTrees. <img src="https://img.shields.io/github/stars/google/tree-math?style=social" align="center">
* [Praxis](https://github.com/google/praxis) ⭐ 200 | 🐛 23 | 🌐 Python | 📅 2026-08-26 - The layer library for Pax with a goal to be usable by other JAX-based ML projects. <img src="https://img.shields.io/github/stars/google/praxis?style=social" align="center">
* [NAVIX](https://github.com/epignatelli/navix) ⭐ 180 | 🐛 13 | 🌐 Python | 📅 2026-08-30 - A reimplementation of MiniGrid, a Reinforcement Learning environment, in JAX <img src="https://img.shields.io/github/stars/epignatelli/navix?style=social" align="center">
* [kvax](https://github.com/nebius/kvax) ⭐ 174 | 🐛 4 | 🌐 Python | 📅 2025-11-11 - A FlashAttention implementation for JAX with support for efficient document mask computation and context parallelism. <img src="https://img.shields.io/github/stars/nebius/kvax?style=social" align="center">
* [SCICO](https://github.com/lanl/scico) ⭐ 169 | 🐛 19 | 🌐 Python | 📅 2026-08-20 - Scientific computational imaging in JAX. <img src="https://img.shields.io/github/stars/lanl/scico?style=social" align="center">
* [jax-models](https://github.com/DarshanDeshpande/jax-models) ⭐ 162 | 🐛 0 | 🌐 Python | 📅 2022-06-25 - Implementations of research papers originally without code or code written with frameworks other than JAX. <img src="https://img.shields.io/github/stars/DarshanDeshpande/jax-modelsa?style=social" align="center">
* [Lorax](https://github.com/davisyoshida/lorax) ⭐ 143 | 🐛 1 | 🌐 Python | 📅 2024-02-26 - Automatically apply LoRA to JAX models (Flax, Haiku, etc.)
* [Spyx](https://github.com/kmheckel/spyx) ⭐ 137 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2026-07-07 - Spiking Neural Networks in JAX for machine learning on neuromorphic hardware. <img src="https://img.shields.io/github/stars/kmheckel/spyx?style=social" align="center">
* [JaxDF](https://github.com/ucl-bug/jaxdf) ⭐ 135 | 🐛 10 | 🌐 Python | 📅 2026-05-07 - Framework for differentiable simulators with arbitrary discretizations. <img src="https://img.shields.io/github/stars/ucl-bug/jaxdf?style=social" align="center">
* [SymJAX](https://github.com/SymJAX/SymJAX) ⭐ 132 | 🐛 3 | 🌐 Python | 📅 2023-05-22 - Symbolic CPU/GPU/TPU programming. <img src="https://img.shields.io/github/stars/SymJAX/SymJAX?style=social" align="center">
* [jax-tqdm](https://github.com/jeremiecoullon/jax-tqdm) ⭐ 130 | 🐛 2 | 🌐 Python | 📅 2026-05-22 - Add a tqdm progress bar to JAX scans and loops. <img src="https://img.shields.io/github/stars/jeremiecoullon/jax-tqdm?style=social" align="center">
* [TF2JAX](https://github.com/deepmind/tf2jax) ⭐ 124 | 🐛 22 | 🌐 Python | 📅 2026-08-29 - Convert functions/graphs to JAX functions. <img src="https://img.shields.io/github/stars/deepmind/tf2jax?style=social" align="center">
* [econpizza](https://github.com/gboehl/econpizza) ⭐ 117 | 🐛 1 | 🌐 Python | 📅 2026-06-22 - Solve macroeconomic models with hetereogeneous agents using JAX. <img src="https://img.shields.io/github/stars/gboehl/econpizza?style=social" align="center">
* [Einshape](https://github.com/deepmind/einshape) ⭐ 113 | 🐛 2 | 🌐 Python | 📅 2024-06-25 - DSL-based reshaping library for JAX and other frameworks. <img src="https://img.shields.io/github/stars/deepmind/einshape?style=social" align="center">
* [Eqxvision](https://github.com/paganpasta/eqxvision) ⭐ 113 | 🐛 7 | 🌐 Python | 📅 2024-07-19 - Equinox version of Torchvision. <img src="https://img.shields.io/github/stars/paganpasta/eqxvision?style=social" align="center">
* [bayex](https://github.com/alonfnt/bayex) ⭐ 109 | 🐛 5 | 🌐 Python | 📅 2026-08-08 - Bayesian Optimization powered by JAX. <img src="https://img.shields.io/github/stars/alonfnt/bayex?style=social" align="center">
* [jax-unirep](https://github.com/ElArkk/jax-unirep) ⭐ 107 | 🐛 12 | 🌐 TeX | 📅 2024-09-03 - Library implementing the [UniRep model](https://www.nature.com/articles/s41592-019-0598-1) for protein machine learning applications. <img src="https://img.shields.io/github/stars/ElArkk/jax-unirep?style=social" align="center">
* [CR.Sparse](https://github.com/carnotresearch/cr-sparse) ⭐ 103 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-10-17 - XLA accelerated algorithms for sparse representations and compressive sensing. <img src="https://img.shields.io/github/stars/carnotresearch/cr-sparse?style=social" align="center">
* [efax](https://github.com/NeilGirdhar/efax) ⭐ 77 | 🐛 9 | 🌐 Python | 📅 2026-08-28 - Exponential Families in JAX. <img src="https://img.shields.io/github/stars/NeilGirdhar/efax?style=social" align="center">
* [exojax](https://github.com/HajimeKawahara/exojax) ⭐ 74 | 🐛 30 | 🌐 Jupyter Notebook | 📅 2026-08-25 - Automatic differentiable spectrum modeling of exoplanets/brown dwarfs compatible to JAX. <img src="https://img.shields.io/github/stars/HajimeKawahara/exojax?style=social" align="center">
* [Kernex](https://github.com/ASEM000/kernex) ⭐ 73 | 🐛 8 | 🌐 Python | 📅 2025-11-15 - Differentiable stencil decorators in JAX. <img src="https://img.shields.io/github/stars/ASEM000/kernex?style=social" align="center">
* [astronomix](https://github.com/leo1200/astronomix) ⭐ 71 | 🐛 5 | 🌐 Python | 📅 2026-08-19 - differentiable (magneto)hydrodynamics for astrophysics in JAX <img src="https://img.shields.io/github/stars/leo1200/astronomix?style=social" align="center">
* [delta PV](https://github.com/romanodev/deltapv) ⭐ 67 | 🐛 0 | 🌐 Python | 📅 2025-09-28 - A photovoltaic simulator with automatic differentation. <img src="https://img.shields.io/github/stars/romanodev/deltapv?style=social" align="center">
* [PGMax](https://github.com/vicariousinc/PGMax) ⚠️ Archived - A framework for building discrete Probabilistic Graphical Models (PGM's) and running inference inference on them via JAX. <img src="https://img.shields.io/github/stars/vicariousinc/pgmax?style=social" align="center">
* [DiffeRT](https://github.com/jeertmans/DiffeRT) ⭐ 64 | 🐛 12 | 🌐 Python | 📅 2026-08-27 - Differentiable Ray Tracing toolbox for Radio Propagation powered by the JAX ecosystem. <img src="https://img.shields.io/github/stars/jeertmans/DiffeRT?style=social" align="center">
* [JAXFit](https://github.com/dipolar-quantum-gases/jaxfit) ⭐ 61 | 🐛 4 | 🌐 Python | 📅 2023-06-23 - Accelerated curve fitting library for nonlinear least-squares problems (see [arXiv paper](https://arxiv.org/abs/2208.12187)). <img src="https://img.shields.io/github/stars/dipolar-quantum-gases/jaxfit?style=social" align="center">
* [sklearn-jax-kernels](https://github.com/ExpectationMax/sklearn-jax-kernels) ⭐ 47 | 🐛 0 | 🌐 Python | 📅 2020-10-26 - `scikit-learn` kernel matrices using JAX. <img src="https://img.shields.io/github/stars/ExpectationMax/sklearn-jax-kernels?style=social" align="center">
* [safejax](https://github.com/alvarobartt/safejax) ⭐ 47 | 🐛 2 | 🌐 Python | 📅 2024-05-31 - Serialize JAX, Flax, Haiku, or Objax model params with 🤗`safetensors`. <img src="https://img.shields.io/github/stars/alvarobartt/safejax?style=social" align="center">
* [FlaxVision](https://github.com/rolandgvc/flaxvision) ⭐ 46 | 🐛 15 | 🌐 Python | 📅 2025-07-19 - Flax version of TorchVision. <img src="https://img.shields.io/github/stars/rolandgvc/flaxvision?style=social" align="center">
* [imax](https://github.com/4rtemi5/imax) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2024-04-09 - Image augmentations and transformations. <img src="https://img.shields.io/github/stars/4rtemi5/imax?style=social" align="center">
* [vivsim](https://github.com/haimingz/vivsim) ⭐ 44 | 🐛 5 | 🌐 Python | 📅 2026-06-27 - Fluid-structure interaction simulations using Immersed Boundary-Lattice Boltzmann Method. <img src="https://img.shields.io/github/stars/haimingz/vivsim?style=social" align="center">
* [Coreax](https://github.com/gchq/coreax) ⭐ 43 | 🐛 46 | 🌐 Python | 📅 2026-08-27 - Algorithms for finding coresets to compress large datasets while retaining their statistical properties. <img src="https://img.shields.io/github/stars/gchq/coreax?style=social" align="center">
* [flaxdiff](https://github.com/AshishKumar4/FlaxDiff) ⭐ 40 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-27 - Framework and Library for building and training Diffusion models in multi-node multi-device distributed settings (TPUs) <img src="https://img.shields.io/github/stars/AshishKumar4/FlaxDiff?style=social" align="center">
* [tmmax](https://github.com/bahremsd/tmmax) ⭐ 39 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2026-02-11 - Vectorized calculation of optical properties in thin-film structures using JAX. Swiss Army knife tool for thin-film optics research <img src="https://img.shields.io/github/stars/bahremsd/tmmax" align="center">
* [JAX-in-Cell](https://github.com/uwplasma/JAX-in-Cell) ⭐ 32 | 🐛 5 | 🌐 Python | 📅 2026-08-27 - Plasma physics simulations using a PIC (Particle-in-Cell) method to self-consistently solve for electron and ion dynamics in electromagnetic fields <img src="https://img.shields.io/github/stars/uwplasma/JAX-in-Cell?style=social" align="center">
* [MBIRJAX](https://github.com/cabouman/mbirjax) ⭐ 23 | 🐛 7 | 🌐 HTML | 📅 2026-08-26 - High-performance tomographic reconstruction. <img src="https://img.shields.io/github/stars/cabouman/mbirjax?style-social" align="center">
* [foragax](https://github.com/i-m-iron-man/Foragax) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-01-10 - Agent-Based modelling framework in JAX.  <img src="https://img.shields.io/github/stars/i-m-iron-man/Foragax?style=social" align="center">
* Neural Network Libraries
  * [Equivariant MLP](https://github.com/mfinzi/equivariant-MLP) ⭐ 288 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2023-05-08 - Construct equivariant neural network layers. <img src="https://img.shields.io/github/stars/mfinzi/equivariant-MLP?style=social" align="center">
  * [FedJAX](https://github.com/google/fedjax) ⭐ 272 | 🐛 12 | 🌐 Python | 📅 2026-08-06 - Federated learning in JAX, built on Optax and Haiku. <img src="https://img.shields.io/github/stars/google/fedjax?style=social" align="center">
  * [Parallax](https://github.com/srush/parallax) ⭐ 154 | 🐛 1 | 🌐 Python | 📅 2020-05-25 - Immutable Torch Modules for JAX. <img src="https://img.shields.io/github/stars/srush/parallax?style=social" align="center">
  * [jax-resnet](https://github.com/n2cholas/jax-resnet/) ⭐ 120 | 🐛 4 | 🌐 Python | 📅 2022-06-05 - Implementations and checkpoints for ResNet variants in Flax. <img src="https://img.shields.io/github/stars/n2cholas/jax-resnet?style=social" align="center">
  * [jax-raft](https://github.com/alebeck/jax-raft/) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-09-02 - JAX/Flax port of the RAFT optical flow estimator. <img src="https://img.shields.io/github/stars/alebeck/jax-raft?style=social" align="center">
* Nonlinear Optimization
  * [JAXopt](https://github.com/google/jaxopt) ⭐ 1,059 | 🐛 140 | 🌐 Python | 📅 2026-06-04 - Hardware accelerated (GPU/TPU), batchable and differentiable optimizers in JAX. <img src="https://img.shields.io/github/stars/google/jaxopt?style=social" align="center">
  * [Optimistix](https://github.com/patrick-kidger/optimistix) ⭐ 617 | 🐛 81 | 🌐 Python | 📅 2026-08-11 - Root finding, minimisation, fixed points, and least squares. <img src="https://img.shields.io/github/stars/patrick-kidger/optimistix?style=social" align="center">
* [jax-flows](https://github.com/ChrisWaites/jax-flows) - Normalizing flows in JAX. <img src="https://img.shields.io/github/stars/ChrisWaites/jax-flows?style=social" align="center">
* Brain Dynamics Programming Ecosystem
  * [BrainPy](https://github.com/brainpy/BrainPy) ⭐ 705 | 🐛 4 | 🌐 Python | 📅 2026-08-13 - Brain Dynamics Programming in Python. <img src="https://img.shields.io/github/stars/brainpy/BrainPy?style=social" align="center">
  * [brainstate](https://github.com/chaobrain/brainstate) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2026-08-24 - State-based Transformation System for Program Compilation and Augmentation. <img src="https://img.shields.io/github/stars/chaobrain/brainstate?style=social" align="center">
  * [brainunit](https://github.com/chaobrain/brainunit) ⭐ 16 | 🐛 0 | 📅 2026-08-12 - Physical units and unit-aware mathematical system in JAX. <img src="https://img.shields.io/github/stars/chaobrain/brainunit?style=social" align="center">
  * [dendritex](https://github.com/chaobrain/dendritex) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-08-29 - Dendritic Modeling in JAX. <img src="https://img.shields.io/github/stars/chaobrain/dendritex?style=social" align="center">
  * [braintaichi](https://github.com/chaobrain/braintaichi) ⚠️ Archived - Leveraging Taichi Lang to customize brain dynamics operators. <img src="https://img.shields.io/github/stars/chaobrain/braintaichi?style=social" align="center">

<a name="models-and-projects" />

## Models and Projects

### JAX

* [Amortized Bayesian Optimization](https://github.com/google-research/google-research/tree/master/amortized_bo) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Code related to [*Amortized Bayesian Optimization over Discrete Spaces*](http://www.auai.org/uai2020/proceedings/329_main_paper.pdf).
* [Accurate Quantized Training](https://github.com/google-research/google-research/tree/master/aqt) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Tools and libraries for running and analyzing neural network quantization experiments in JAX and Flax.
* [BNN-HMC](https://github.com/google-research/google-research/tree/master/bnn_hmc) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Implementation for the paper [*What Are Bayesian Neural Network Posteriors Really Like?*](https://arxiv.org/abs/2104.14421).
* [JAX-DFT](https://github.com/google-research/google-research/tree/master/jax_dft) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - One-dimensional density functional theory (DFT) in JAX, with implementation of [*Kohn-Sham equations as regularizer: building prior knowledge into machine-learned physics*](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.036401).
* [Robust Loss](https://github.com/google-research/google-research/tree/master/robust_loss_jax) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Reference code for the paper [*A General and Adaptive Robust Loss Function*](https://arxiv.org/abs/1701.03077).
* [Symbolic Functionals](https://github.com/google-research/google-research/tree/master/symbolic_functionals) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Demonstration from [*Evolving symbolic density functionals*](https://arxiv.org/abs/2203.02540).
* [TriMap](https://github.com/google-research/google-research/tree/master/trimap) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official JAX implementation of [*TriMap: Large-scale Dimensionality Reduction Using Triplets*](https://arxiv.org/abs/1910.00204).
* [Fourier Feature Networks](https://github.com/tancik/fourier-feature-networks) ⭐ 1,371 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2023-01-17 - Official implementation of [*Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains*](https://people.eecs.berkeley.edu/~bmild/fourfeat).
* [jaxns](https://github.com/Joshuaalbert/jaxns) ⭐ 254 | 🐛 11 | 🌐 Python | 📅 2026-08-30 - Nested sampling in JAX.
* [kalman-jax](https://github.com/AaltoML/kalman-jax) ⭐ 103 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-07-06 - Approximate inference for Markov (i.e., temporal) Gaussian processes using iterated Kalman filtering and smoothing.

### Flax

* [Performer](https://github.com/google-research/google-research/tree/master/performer/fast_attention/jax) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Flax implementation of the Performer (linear transformer via FAVOR+) architecture.
* [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Implementation of [*NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis*](http://www.matthewtancik.com/nerf) with multi-device GPU/TPU support.
* [RegNeRF](https://github.com/google-research/google-research/tree/master/regnerf) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*RegNeRF: Regularizing Neural Radiance Fields for View Synthesis from Sparse Inputs*](https://m-niemeyer.github.io/regnerf/).
* [Distributed Shampoo](https://github.com/google-research/google-research/tree/master/scalable_shampoo) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Implementation of [*Second Order Optimization Made Practical*](https://arxiv.org/abs/2002.09018).
* [FNet](https://github.com/google-research/google-research/tree/master/f_net) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*FNet: Mixing Tokens with Fourier Transforms*](https://arxiv.org/abs/2105.03824).
* [GFSA](https://github.com/google-research/google-research/tree/master/gfsa) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*Learning Graph Structure With A Finite-State Automaton Layer*](https://arxiv.org/abs/2007.04929).
* [IPA-GNN](https://github.com/google-research/google-research/tree/master/ipagnn) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*Learning to Execute Programs with Instruction Pointer Attention Graph Neural Networks*](https://arxiv.org/abs/2010.12621).
* [Flax Models](https://github.com/google-research/google-research/tree/master/flax_models) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Collection of models and methods implemented in Flax.
* [Protein LM](https://github.com/google-research/google-research/tree/master/protein_lm) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Implements BERT and autoregressive models for proteins, as described in [*Biological Structure and Function Emerge from Scaling Unsupervised Learning to 250 Million Protein Sequences*](https://www.biorxiv.org/content/10.1101/622803v1.full) and [*ProGen: Language Modeling for Protein Generation*](https://www.biorxiv.org/content/10.1101/2020.03.07.982272v2).
* [Slot Attention](https://github.com/google-research/google-research/tree/master/ptopk_patch_selection) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Reference implementation for [*Differentiable Patch Selection for Image Recognition*](https://arxiv.org/abs/2104.03059).
* [ARDM](https://github.com/google-research/google-research/tree/master/autoregressive_diffusion) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*Autoregressive Diffusion Models*](https://arxiv.org/abs/2110.02037).
* [D3PM](https://github.com/google-research/google-research/tree/master/d3pm) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*Structured Denoising Diffusion Models in Discrete State-Spaces*](https://arxiv.org/abs/2107.03006).
* [Gumbel-max Causal Mechanisms](https://github.com/google-research/google-research/tree/master/gumbel_max_causal_gadgets) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Code for [*Learning Generalized Gumbel-max Causal Mechanisms*](https://arxiv.org/abs/2111.06888), with extra code in [GuyLor/gumbel\_max\_causal\_gadgets\_part2](https://github.com/GuyLor/gumbel_max_causal_gadgets_part2) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2021-11-12.
* [Latent Programmer](https://github.com/google-research/google-research/tree/master/latent_programmer) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Code for the ICML 2021 paper [*Latent Programmer: Discrete Latent Codes for Program Synthesis*](https://arxiv.org/abs/2012.00377).
* [SNeRG](https://github.com/google-research/google-research/tree/master/snerg) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*Baking Neural Radiance Fields for Real-Time View Synthesis*](https://phog.github.io/snerg).
* [Spin-weighted Spherical CNNs](https://github.com/google-research/google-research/tree/master/spin_spherical_cnns) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Adaptation of [*Spin-Weighted Spherical CNNs*](https://arxiv.org/abs/2006.10731).
* [VDVAE](https://github.com/google-research/google-research/tree/master/vdvae_flax) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Adaptation of [*Very Deep VAEs Generalize Autoregressive Models and Can Outperform Them on Images*](https://arxiv.org/abs/2011.10650), original code at [openai/vdvae](https://github.com/openai/vdvae) ⚠️ Archived.
* [MUSIQ](https://github.com/google-research/google-research/tree/master/musiq) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Checkpoints and model inference code for the ICCV 2021 paper [*MUSIQ: Multi-scale Image Quality Transformer*](https://arxiv.org/abs/2108.05997)
* [AQuaDem](https://github.com/google-research/google-research/tree/master/aquadem) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*Continuous Control with Action Quantization from Demonstrations*](https://arxiv.org/abs/2110.10149).
* [Combiner](https://github.com/google-research/google-research/tree/master/combiner) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*Combiner: Full Attention Transformer with Sparse Computation Cost*](https://arxiv.org/abs/2107.05768).
* [Dreamfields](https://github.com/google-research/google-research/tree/master/dreamfields) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of the ICLR 2022 paper [*Progressive Distillation for Fast Sampling of Diffusion Models*](https://ajayj.com/dreamfields).
* [GIFT](https://github.com/google-research/google-research/tree/master/gift) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*Gradual Domain Adaptation in the Wild:When Intermediate Distributions are Absent*](https://arxiv.org/abs/2106.06080).
* [Light Field Neural Rendering](https://github.com/google-research/google-research/tree/master/light_field_neural_rendering) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Official implementation of [*Light Field Neural Rendering*](https://arxiv.org/abs/2112.09687).
* [Vision Transformer](https://github.com/google-research/vision_transformer) ⭐ 12,687 | 🐛 139 | 🌐 Jupyter Notebook | 📅 2026-08-01 - Official implementation of [*An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale*](https://arxiv.org/abs/2010.11929).
* [Big Transfer (BiT)](https://github.com/google-research/big_transfer) ⚠️ Archived - Implementation of [*Big Transfer (BiT): General Visual Representation Learning*](https://arxiv.org/abs/1912.11370).
* [mip-NeRF](https://github.com/google/mipnerf) ⚠️ Archived - Official implementation of [*Mip-NeRF: A Multiscale Representation for Anti-Aliasing Neural Radiance Fields*](https://jonbarron.info/mipnerf).
* [JAX RL](https://github.com/ikostrikov/jax-rl) ⭐ 758 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2022-10-26 - Implementations of reinforcement learning algorithms.
* [NesT](https://github.com/google-research/nested-transformer) ⭐ 204 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2026-03-03 - Official implementation of [*Aggregating Nested Transformers*](https://arxiv.org/abs/2105.12723).
* [XMC-GAN](https://github.com/google-research/xmcgan_image_generation) ⭐ 100 | 🐛 35 | 🌐 Python | 📅 2026-07-23 - Official implementation of [*Cross-Modal Contrastive Learning for Text-to-Image Generation*](https://arxiv.org/abs/2101.04702).
* [GNNs for Solving Combinatorial Optimization Problems](https://github.com/IvanIsCoding/GNN-for-Combinatorial-Optimization) ⭐ 67 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-11-09 -  A JAX + Flax implementation of [Combinatorial Optimization with Physics-Inspired Graph Neural Networks](https://arxiv.org/abs/2107.01188).
* [FID computation](https://github.com/matthias-wright/jax-fid) ⭐ 29 | 🐛 2 | 🌐 Python | 📅 2024-07-17 - Port of [mseitzer/pytorch-fid](https://github.com/mseitzer/pytorch-fid) ⭐ 3,851 | 🐛 27 | 🌐 Python | 📅 2024-07-03 to Flax.
* [DeepSeek-R1-Flax-1.5B-Distill](https://github.com/J-Rosser-UK/Torch2Jax-DeepSeek-R1-Distill-Qwen-1.5B) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2025-02-20 - Flax implementation of DeepSeek-R1 1.5B distilled reasoning LLM.
* [DETR](https://github.com/MasterSkepticista/detr) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-07-15 - Flax implementation of [*DETR: End-to-end Object Detection with Transformers*](https://github.com/facebookresearch/detr) ⚠️ Archived using Sinkhorn solver and parallel bipartite matching.
* [JaxNeuS](https://github.com/huangjuite/jaxneus) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-07-04 - Implementation of [*NeuS: Learning Neural Implicit Surfaces by Volume Rendering for Multi-view Reconstruction*](https://lingjie0206.github.io/papers/NeuS/)
* [awesome-jax-flax-llms](https://github.com/your-username/awesome-jax-flax-llms) - Collection of LLMs implemented in **JAX** & **Flax**
* [gMLP](https://github.com/SauravMaheshkar/gMLP) - Implementation of [*Pay Attention to MLPs*](https://arxiv.org/abs/2105.08050).
* [MLP Mixer](https://github.com/SauravMaheshkar/MLP-Mixer) - Minimal implementation of [*MLP-Mixer: An all-MLP Architecture for Vision*](https://arxiv.org/abs/2105.01601).
* [Sharpened Cosine Similarity in JAX by Raphael Pisoni](https://colab.research.google.com/drive/1KUKFEMneQMS3OzPYnWZGkEnry3PdzCfn?usp=sharing) -  A JAX/Flax implementation of the Sharpened Cosine Similarity layer.

### Haiku

* [Persistent Evolution Strategies](https://github.com/google-research/google-research/tree/master/persistent_es) ⭐ 38,652 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Code used for the paper [*Unbiased Gradient Estimation in Unrolled Computation Graphs with Persistent Evolution Strategies*](http://proceedings.mlr.press/v139/vicol21a.html).
* [Adversarial Robustness](https://github.com/deepmind/deepmind-research/tree/master/adversarial_robustness) ⭐ 15,176 | 🐛 358 | 🌐 Jupyter Notebook | 📅 2026-06-17 - Reference code for [*Uncovering the Limits of Adversarial Training against Norm-Bounded Adversarial Examples*](https://arxiv.org/abs/2010.03593) and [*Fixing Data Augmentation to Improve Adversarial Robustness*](https://arxiv.org/abs/2103.01946).
* [Bootstrap Your Own Latent](https://github.com/deepmind/deepmind-research/tree/master/byol) ⭐ 15,176 | 🐛 358 | 🌐 Jupyter Notebook | 📅 2026-06-17 - Implementation for the paper [*Bootstrap your own latent: A new approach to self-supervised Learning*](https://arxiv.org/abs/2006.07733).
* [Gated Linear Networks](https://github.com/deepmind/deepmind-research/tree/master/gated_linear_networks) ⭐ 15,176 | 🐛 358 | 🌐 Jupyter Notebook | 📅 2026-06-17 - GLNs are a family of backpropagation-free neural networks.
* [Glassy Dynamics](https://github.com/deepmind/deepmind-research/tree/master/glassy_dynamics) ⭐ 15,176 | 🐛 358 | 🌐 Jupyter Notebook | 📅 2026-06-17 - Open source implementation of the paper [*Unveiling the predictive power of static structure in glassy systems*](https://www.nature.com/articles/s41567-020-0842-8).
* [MMV](https://github.com/deepmind/deepmind-research/tree/master/mmv) ⭐ 15,176 | 🐛 358 | 🌐 Jupyter Notebook | 📅 2026-06-17 - Code for the models in [*Self-Supervised MultiModal Versatile Networks*](https://arxiv.org/abs/2006.16228).
* [Normalizer-Free Networks](https://github.com/deepmind/deepmind-research/tree/master/nfnets) ⭐ 15,176 | 🐛 358 | 🌐 Jupyter Notebook | 📅 2026-06-17 - Official Haiku implementation of [*NFNets*](https://arxiv.org/abs/2102.06171).
* [OGB-LSC](https://github.com/deepmind/deepmind-research/tree/master/ogb_lsc) ⭐ 15,176 | 🐛 358 | 🌐 Jupyter Notebook | 📅 2026-06-17 - This repository contains DeepMind's entry to the [PCQM4M-LSC](https://ogb.stanford.edu/kddcup2021/pcqm4m/) (quantum chemistry) and [MAG240M-LSC](https://ogb.stanford.edu/kddcup2021/mag240m/) (academic graph)
  tracks of the [OGB Large-Scale Challenge](https://ogb.stanford.edu/kddcup2021/) (OGB-LSC).
* [WikiGraphs](https://github.com/deepmind/deepmind-research/tree/master/wikigraphs) ⭐ 15,176 | 🐛 358 | 🌐 Jupyter Notebook | 📅 2026-06-17 - Baseline code to reproduce results in [*WikiGraphs: A Wikipedia Text - Knowledge Graph Paired Datase*](https://aclanthology.org/2021.textgraphs-1.7).
* [AlphaFold](https://github.com/deepmind/alphafold) ⭐ 14,818 | 🐛 307 | 🌐 Python | 📅 2026-04-22 - Implementation of the inference pipeline of AlphaFold v2.0, presented in [*Highly accurate protein structure prediction with AlphaFold*](https://www.nature.com/articles/s41586-021-03819-2).
* [NuX](https://github.com/Information-Fusion-Lab-Umass/NuX) ⭐ 87 | 🐛 0 | 🌐 Python | 📅 2023-11-30 - Normalizing flows with JAX.
* [Two Player Auction Learning](https://github.com/degregat/two-player-auctions) ⭐ 0 | 🐛 0 | 📅 2023-12-07 - JAX implementation of the paper [*Auction learning as a two-player game*](https://arxiv.org/abs/2006.05684).

### Trax

* [Reformer](https://github.com/google/trax/tree/master/trax/models/reformer) ⚠️ Archived - Implementation of the Reformer (efficient transformer) architecture.

### NumPyro

* [lqg](https://github.com/RothkopfLab/lqg) ⭐ 31 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-28 - Official implementation of Bayesian inverse optimal control for linear-quadratic Gaussian problems from the paper [*Putting perception into action with inverse optimal control for continuous psychophysics*](https://elifesciences.org/articles/76635)

### Equinox

* [Sampling Path Candidates with Machine Learning](https://differt.eertmans.be/icmlcn2025/notebooks/sampling_paths.html) - Official tutorial and implementation from the paper [*Towards Generative Ray Path Sampling for Faster Point-to-Point Ray Tracing*](https://arxiv.org/abs/2410.23773).

<a name="videos" />

## Videos

* [NeurIPS 2020: JAX Ecosystem Meetup](https://www.youtube.com/watch?v=iDxJxIyzSiM) - JAX, its use at DeepMind, and discussion between engineers, scientists, and JAX core team.
* [Introduction to JAX](https://youtu.be/0mVmRHMaOJ4) - Simple neural network from scratch in JAX.
* [JAX: Accelerated Machine Learning Research | SciPy 2020 | VanderPlas](https://youtu.be/z-WSrQDXkuM) - JAX's core design, how it's powering new research, and how you can start using it.
* [Bayesian Programming with JAX + NumPyro — Andy Kitchen](https://youtu.be/CecuWGpoztw) - Introduction to Bayesian modelling using NumPyro.
* [JAX: Accelerated machine-learning research via composable function transformations in Python | NeurIPS 2019 | Skye Wanderman-Milne](https://slideslive.com/38923687/jax-accelerated-machinelearning-research-via-composable-function-transformations-in-python) - JAX intro presentation in [*Program Transformations for Machine Learning*](https://program-transformations.github.io) workshop.
* [JAX on Cloud TPUs | NeurIPS 2020 | Skye Wanderman-Milne and James Bradbury](https://drive.google.com/file/d/1jKxefZT1xJDUxMman6qrQVed7vWI0MIn/edit) - Presentation of TPU host access with demo.
* [Deep Implicit Layers - Neural ODEs, Deep Equilibirum Models, and Beyond | NeurIPS 2020](https://slideslive.com/38935810/deep-implicit-layers-neural-odes-equilibrium-models-and-beyond) - Tutorial created by Zico Kolter, David Duvenaud, and Matt Johnson with Colab notebooks avaliable in [*Deep Implicit Layers*](http://implicit-layers-tutorial.org).
* [Solving y=mx+b with Jax on a TPU Pod slice - Mat Kelcey](http://matpalm.com/blog/ymxb_pod_slice/) - A four part YouTube tutorial series with Colab notebooks that starts with Jax fundamentals and moves up to training with a data parallel approach on a v3-32 TPU Pod slice.
* [JAX, Flax & Transformers 🤗](https://github.com/huggingface/transformers/blob/9160d81c98854df44b1d543ce5d65a6aa28444a2/examples/research_projects/jax-projects/README.md#talks) ⭐ 164,629 | 🐛 2,401 | 🌐 Python | 📅 2026-08-30 - 3 days of talks around JAX / Flax, Transformers, large-scale language modeling and other great topics.

<a name="papers" />

## Papers

This section contains papers focused on JAX (e.g. JAX-based library whitepapers, research on JAX, etc). Papers implemented in JAX are listed in the [Models/Projects](#projects) section.

<!--lint disable-->

* [**Compiling machine learning programs via high-level tracing**. Roy Frostig, Matthew James Johnson, Chris Leary. *MLSys 2018*.](https://mlsys.org/Conferences/doc/2018/146.pdf) - White paper describing an early version of JAX, detailing how computation is traced and compiled.
* [**JAX, M.D.: A Framework for Differentiable Physics**. Samuel S. Schoenholz, Ekin D. Cubuk. *NeurIPS 2020*.](https://arxiv.org/abs/1912.04232) - Introduces JAX, M.D., a differentiable physics library which includes simulation environments, interaction potentials, neural networks, and more.
* [**Enabling Fast Differentially Private SGD via Just-in-Time Compilation and Vectorization**. Pranav Subramani, Nicholas Vadivelu, Gautam Kamath. *arXiv 2020*.](https://arxiv.org/abs/2010.09063) - Uses JAX's JIT and VMAP to achieve faster differentially private than existing libraries.
* [**XLB: A Differentiable Massively Parallel Lattice Boltzmann Library in Python**. Mohammadmehdi Ataei, Hesam Salehipour. *arXiv 2023*.](https://arxiv.org/abs/2311.16080) - White paper describing the XLB library: benchmarks, validations, and more details about the library.

<!--lint enable-->

<a name="tutorials-and-blog-posts" />

## Tutorials and Blog Posts

* [Get started with JAX by Aleksa Gordić](https://github.com/gordicaleksa/get-started-with-JAX) ⭐ 786 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-11-29 - A series of notebooks and videos going from zero JAX knowledge to building neural networks in Haiku.
* [Extending JAX with custom C++ and CUDA code by Dan Foreman-Mackey](https://github.com/dfm/extending-jax) ⭐ 404 | 🐛 0 | 🌐 Python | 📅 2024-08-18 - Tutorial demonstrating the infrastructure required to provide custom ops in JAX.
* [Tutorial: image classification with JAX and Flax Linen by 8bitmp3](https://github.com/8bitmp3/JAX-Flax-Tutorial-Image-Classification-with-Linen) ⚠️ Archived - Learn how to create a simple convolutional network with the Linen API by Flax and train it to recognize handwritten digits.
* [Using JAX to accelerate our research by David Budden and Matteo Hessel](https://deepmind.com/blog/article/using-jax-to-accelerate-our-research) - Describes the state of JAX and the JAX ecosystem at DeepMind.
* [Getting started with JAX (MLPs, CNNs & RNNs) by Robert Lange](https://roberttlange.github.io/posts/2020/03/blog-post-10/) - Neural network building blocks from scratch with the basic JAX operators.
* [Learn JAX: From Linear Regression to Neural Networks by Rito Ghosh](https://www.kaggle.com/code/truthr/jax-0) - A gentle introduction to JAX and using it to implement Linear and Logistic Regression, and Neural Network models and using them to solve real world problems.
* [Plugging Into JAX by Nick Doiron](https://medium.com/swlh/plugging-into-jax-16c120ec3302) - Compares Flax, Haiku, and Objax on the Kaggle flower classification challenge.
* [Meta-Learning in 50 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/02/maml-jax.html) - Introduction to both JAX and Meta-Learning.
* [Normalizing Flows in 100 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/07/nf-jax.html) - Concise implementation of [RealNVP](https://arxiv.org/abs/1605.08803).
* [Differentiable Path Tracing on the GPU/TPU by Eric Jang](https://blog.evjang.com/2019/11/jaxpt.html) - Tutorial on implementing path tracing.
* [Ensemble networks by Mat Kelcey](http://matpalm.com/blog/ensemble_nets) - Ensemble nets are a method of representing an ensemble of models as one single logical model.
* [Out of distribution (OOD) detection by Mat Kelcey](http://matpalm.com/blog/ood_using_focal_loss) - Implements different methods for OOD detection.
* [Understanding Autodiff with JAX by Srihari Radhakrishna](https://www.radx.in/jax.html) - Understand how autodiff works using JAX.
* [From PyTorch to JAX: towards neural net frameworks that purify stateful code by Sabrina J. Mielke](https://sjmielke.com/jax-purify.htm) - Showcases how to go from a PyTorch-like style of coding to a more Functional-style of coding.
* [Evolving Neural Networks in JAX by Robert Tjarko Lange](https://roberttlange.github.io/posts/2021/02/cma-es-jax/) - Explores how JAX can power the next generation of scalable neuroevolution algorithms.
* [Exploring hyperparameter meta-loss landscapes with JAX by Luke Metz](http://lukemetz.com/exploring-hyperparameter-meta-loss-landscapes-with-jax/) - Demonstrates how to use JAX to perform inner-loss optimization with SGD and Momentum, outer-loss optimization with gradients, and outer-loss optimization using evolutionary strategies.
* [Deterministic ADVI in JAX by Martin Ingram](https://martiningram.github.io/deterministic-advi/) - Walk through of implementing automatic differentiation variational inference (ADVI) easily and cleanly with JAX.
* [Evolved channel selection by Mat Kelcey](http://matpalm.com/blog/evolved_channel_selection/) - Trains a classification model robust to different combinations of input channels at different resolutions, then uses a genetic algorithm to decide the best combination for a particular loss.
* [Introduction to JAX by Kevin Murphy](https://colab.research.google.com/github/probml/probml-notebooks/blob/main/notebooks/jax_intro.ipynb) - Colab that introduces various aspects of the language and applies them to simple ML problems.
* [Writing an MCMC sampler in JAX by Jeremie Coullon](https://www.jeremiecoullon.com/2020/11/10/mcmcjax3ways/) - Tutorial on the different ways to write an MCMC sampler in JAX along with speed benchmarks.
* [How to add a progress bar to JAX scans and loops by Jeremie Coullon](https://www.jeremiecoullon.com/2021/01/29/jax_progress_bar/) - Tutorial on how to add a progress bar to compiled loops in JAX using the `host_callback` module.
* [Writing a Training Loop in JAX + FLAX by Saurav Maheshkar and Soumik Rakshit](https://wandb.ai/jax-series/simple-training-loop/reports/Writing-a-Training-Loop-in-JAX-FLAX--VmlldzoyMzA4ODEy) - A tutorial on writing a simple end-to-end training and evaluation pipeline in JAX, Flax and Optax.
* [Implementing NeRF in JAX by Soumik Rakshit and Saurav Maheshkar](https://wandb.ai/wandb/nerf-jax/reports/Implementing-NeRF-in-JAX--VmlldzoxODA2NDk2?galleryTag=jax) - A tutorial on 3D volumetric rendering of scenes represented by Neural Radiance Fields in JAX.
* [Deep Learning tutorials with JAX+Flax by Phillip Lippe](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/JAX/tutorial2/Introduction_to_JAX.html) - A series of notebooks explaining various deep learning concepts, from basics (e.g. intro to JAX/Flax, activiation functions) to recent advances (e.g., Vision Transformers, SimCLR), with translations to PyTorch.
* [Achieving 4000x Speedups with PureJaxRL](https://chrislu.page/blog/meta-disco/) - A blog post on how JAX can massively speedup RL training through vectorisation.
* [Simple PDE solver + Constrained Optimization with JAX by Philip Mocz](https://levelup.gitconnected.com/create-your-own-automatically-differentiable-simulation-with-python-jax-46951e120fbb?sk=e8b9213dd2c6a5895926b2695d28e4aa) - A simple example of solving the advection-diffusion equations with JAX and using it in a constrained optimization problem to find initial conditions that yield desired result.

<a name="books" />

## Books

* [Jax in Action](https://www.manning.com/books/jax-in-action) - A hands-on guide to using JAX for deep learning and other mathematically-intensive applications.

<a name="community" />

## Community

* [JaxLLM (Unofficial) Discord](https://discord.com/channels/1107832795377713302/1107832795688083561)
* [JAX GitHub Discussions](https://github.com/google/jax/discussions) ⭐ 36,226 | 🐛 2,493 | 🌐 Python | 📅 2026-08-30
* [Reddit](https://www.reddit.com/r/JAX/)

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
