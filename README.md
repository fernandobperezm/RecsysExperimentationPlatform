# Open Source Experimentation Platform for Recommender Systems

This repository holds a collection of libraries to experiment with recommender system models in different settings and environments. This experimentation platform has been used to experiment with 5000+ recommendation models each with their own configuration; the results of our findings have been included 6+ peer-reviewed publications.

## Platform Modules
Currently, the experimentation platform holds four modules:

- Module `impressions-datasets` provides an API to load in memory different public datasets holding interactions and impressions. More information on the [module's README](./impressions-datasets/README.md)  
- Module `impressions-evaluation` implements many submodules to create experiments involving impression-aware recommendation models. More information on the [module's README](./impressions-datasets/README.md)  
- Module `RecSysFramework_public` provides an API to load in memory different public datasets holding interactions and impressions. More information on the [module's README](./RecSysFramework_public/README.md)
- Module `recsys-framework-extensions` extends the APIs of the `RecSysFramework_public` module and re-implements some of them to ensure faster computations with JIT compilation, parallel processing of recommendation tasks, among others. More information on the [module's README](./recsys-framework-extensions/README.md) 

## Experimentation Scripts

Checkout the [scripts](./impressions-evaluation/scripts/) folder inside the `impressions-evaluation` module for a comprehensive list of all the available experiments. In the near future, these scripts will be migrated to their dedicated `script` folder at the root of the platform.