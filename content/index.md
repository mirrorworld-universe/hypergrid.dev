## Introduction

HyperGrid protocol is a rollup scaling and orchestration framework for dedicated Solana Virtual Machine (SVM) ecosystem rollup operators. HyperGrid utilizes state compression and Byzantine Fault Tolerance (BFT) to achieve potentially infinite transaction throughput by enabling horizontal scaling across multiple grids, exemplified by [Sonic](https://sonic.game) – a gaming-specific grid that settles on Solana.

### Atomic Interoperability

HyperGrid is designed to be interoperable with Solana. It implements an interoperability interface that allows for wholly encapsulated programs on Solana to delegate execution to Grids orchestrated by HyperGrid. This allows for the creation of a single-source-of-truth for all programs running on Solana, while also facilitating the delegation of computation of programs to HyperGrid. This enables rollups to benefit from the Base layer's services and liquidity.

### SVM Client Diversity

HyperGrid is client-agnostic, meaning that it can be used with any SVM client implementation. This makes it possible for program authors on Solana to implement high-performance clients while relying on HyperGrid's Shared Sequencer Network (HSSN) for consensus and interoperability.

### Write for EVM, Execute on SVM

HyperGrid implements an EVM interpreter for developers that want the speed of execution on SVMs while still being able to write for EVM. This allows for the creation of EVM-compatible smart contracts that can be executed on HyperGrid.

---

HyperGrid is built and maintained by [Sonic](https://sonic.game), and will soon be open sourced under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Learn more about HyperGrid on [the official documentation](https://docs.sonic.game/developers/hypergrid-framework).
