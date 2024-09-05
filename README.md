# Open Source Experimentation Platform for Recommender Systems

This repository holds a collection of libraries to experiment with recommender system models in different settings and environments. This experimentation platform has been used to experiment with 5000+ recommendation models each with their own configuration; the results of our findings have been included 6+ peer-reviewed publications.

## Platform Modules
Currently, the experimentation platform holds four modules:

- Module `impressions-datasets` provides an API to load in memory different public datasets holding interactions and impressions. More information is available in the [module's README](https://github.com/fernandobperezm/polimiphd-DatasetsWithImpressions/blob/main/README.md). 

- Module `impressions-evaluation` implements many submodules to create experiments involving impression-aware recommendation models. More information is available in the [module's README](https://github.com/fernandobperezm/polimiphd-ImpressionsEvaluation/blob/main/README.md).

- Module `RecSysFramework_public` provides APIs to perform various experiments on recommendation models, e.g., reading and processing datasets, implementation of recommendation techniques, evaluation of recommendations, among others. More information is available in the [module's README](https://github.com/fernandobperezm/polimiphd-RecSysFramework_Public/blob/main/README.md).

- Module `recsys-framework-extensions` extends the APIs of the `RecSysFramework_public` module by re-implementing some of them to ensure faster computations with JIT compilation, parallel processing of recommendation tasks, among others. Additionally, extends evaluation APIs to perform statistical testing and compute confidence interval on results. Lastly, it provides quality-of-life traits when developing models, such as logging, memory consumption, and execution time measurement. More information is available in the [module's README](https://github.com/fernandobperezm/polimiphd-RecSysFrameworkExtensions/blob/main/README.md).

## Experimentation Scripts

Checkout the [README](https://github.com/fernandobperezm/polimiphd-ImpressionsEvaluation/blob/main/README.md) inside the `impressions-evaluation` module for a comprehensive list of all the available experiments. In the near future, scripts will be migrated to their dedicated `script` folder at the root of the platform.