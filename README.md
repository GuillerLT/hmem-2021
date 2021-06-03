# HMEM 2021 - 2nd Workshop on Heterogeneous Memory Systems

Heterogeneous memory architectures have recently emerged and revolutionized the traditional memory hierarchy. Today’s architectures may comprise multiple memory nodes, organized in complex non-uniform access (NUMA) topologies, whose nodes include not just DRAM, but also die-stacked DRAM, high-bandwidth multi-channel RAM, or persistent memory.

By combining different memory technologies, heterogeneous memory architectures allow today’s systems to take advantage of the strengths of each technology — namely, in terms of latency, bandwidth, capacity, persistence or cost. As a result, applications may benefit from improved performance, energy-efficiency, and cost trade-offs.

Still, exploiting the full potential of heterogeneous memory architectures poses significant challenges. Since heterogeneous memory architectures introduce dramatic disruptions to the usual memory hierarchy assumptions that have guided decades of system and software design, we need to rethink the full system stack to embrace the new era of memory heterogeneity.

## Optane PMem as an Enabler for Large DNN Models with Homomorphic Encryption

The proliferation of machine learning services in the last few years has raised privacy concerns. Homomorphic encryption (HE) enables inference using encrypted data but it incurs 100x-10,000x memory and runtime overhead. Secure deep neural network (DNN) inference using HE is currently limited by computing and memory requirements, with frameworks requiring hundreds of gigabytes of DRAM to evaluate small models. To overcome these limitations, we explore the feasibility of leveraging hybrid memory systems comprised of DRAM and persistent memory subsystems. In particular, we explore the recently-released Intel Optane PMem to run large DNNs such as MobileNetV2 (in its largest variant) and ResNet-50 for the first time ever. We present an in-depth analysis of the efficiency of the executions with different hardware and software configurations. Our results conclude that DNN inference using HE incurs on friendly access patterns for this memory configuration, yielding efficient executions.
