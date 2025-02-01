# Home_Sales
Comparison of Environments for "BIG" Data

```markdown
| **Aspect**                          | **Google Colab**                       | **Neural_Net (Custom Container)**          |
|-------------------------------------|----------------------------------------|--------------------------------------------|
| **Setup Time**                      | High (10-15 mins, dynamic setup)       | Low (1-3 mins, pre-configured)             |
| **Reproducibility**                 | Low (transient environment)            | High (deterministic setup)                 |
| **Scalability**                     | Limited (single-node execution)        | Excellent (supports multi-node clusters)   |
| **Performance for Small Datasets**  | Good (small to medium workloads)       | Good (equivalent performance)              |
| **Performance for Large Datasets**  | Poor (struggles with >5GB)             | Superior (handles >5GB efficiently)        |
| **Caching Efficiency**              | Moderate (limited persistent memory)   | High (leverages persistent memory)         |
| **Cost-Efficiency**                 | Free for small-scale use               | Cost for cloud resources but efficient     |
| **Ease of Collaboration**           | Easy (notebook sharing)                | Moderate (requires setup)                  |
| **Resource Control**                | Minimal (fixed VM allocation)          | High (fine-grained control over hardware)  |
| **Support for Advanced Configs**    | Limited (restricted runtime control)   | Excellent (full Spark config support)      |
```
REFERENCES:   CHATGPT WAS USED TO RUN SOME SCRIPTS
