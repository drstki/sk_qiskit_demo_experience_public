# Qiskit illustrative demo experience

I provide Jupyter notebooks in this repository showing illustrative examples of different use cases in optimization, machine learning, etc. These examples can be used to demonstrate how these use cases are programmed using Qiskit and then run on IBM Quantum systems using Qiskit Runtime.

[Qiskit](https://qiskit.org/documentation/index.html) is an open-source software for working with quantum computers at the level of circuits, pulses, and algorithms. You can download and install Qiskit on your own workstation. 

[Qiskit Runtime](https://qiskit.org/documentation/partners/qiskit_ibm_runtime/index.html) is a quantum computing service and programming model that allows users to optimize workloads and efficiently execute them on quantum systems at scale. The programming model extends the existing interface in Qiskit with a set of new primitive programs like Estimator or Sampler.

Qiskit is open to different kind of hardware systems, as long as a quantum hardware vendor is providing a backend service ("[qiskit.providers](https://qiskit.org/documentation/apidoc/providers.html)"), you are good to go. I recommend to use the free available quantum resources from [IBM Quantum](https://quantum-computing.ibm.com/). You can simply connect to these devices from your Qiskit installation on your own workstation. 

You can find more information about Qiskit on the [Qiskit community page](https://qiskit.org/). The Qiskit community also provides lots of good resources to learn and experiment with quantum. For a basic understanding of quantum programming I highly recommend the [Qiskit text book](https://qiskit.org/learn/). Further learning material is available from Qiskit Global Summer Schools of [2020](https://qiskit.org/learn/summer-school/introduction-to-quantum-computing-and-quantum-hardware-2020), [2021](https://qiskit.org/learn/summer-school/quantum-computing-and-quantum-learning-2021), and [2022](https://qiskit.org/learn/summer-school/quantum-simulation-summer-school-2022).

Qiskit also provides programming examples in tutorials in different contexts (e.g. optimization, machine-learning). This repository is giving you a couple of illustrative quantum algorithm examples that I built to enhance these existing tutorials. The purpose of my examples is to give you a more instructive and practical approach to basic quantum algorithms, to explain in more detail the context of a use case and what steps are necessary to transform the problem so that it can be run on a quantum computer.

Hope you find them useful. Of course, my examples are open-soure and provided on as-is basis (I provide no error support, debugging or Q&A):

Following examples are provided:

1. Getting started with Qiskit and Qiskit runtime: Starting with simple programming task, building circuits, using primitives sampler & estimator, looking at dynamic circuits.

2. VQE with Qiskit runtime: Solving a simple QUBO problem (max-cut) illustratively by using Qiskit and Qiskit Runtime.

3. qke_with_qiskit_runtime: Quantum Kernel Estimate (QKE) is used with an illustrative example of a mchine learning classification with SVC.
