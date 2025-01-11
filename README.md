# Project Background
Black Hole Mergers are believed to originate in the center of globular clusters. Over time, these interactions create a binary black hole system that merges to produce a gravitational wave event. Observations of gravitational waves have discovered nearly 100 mergers of binary black holes! Over time, these interactions create a binary black hole system that merges to produce a gravitational wave event.

Understanding how these globular Clusters can produce black hole mergers involves simulating their behavior using N-body codes.
- N-body simulations are computationally intensive and can take several months for a single stellar cluster.
- **Goal**: Develop an emulator using neural networks to mimic outcomes of astrophysical simulations on stellar clusters.

**Research Plan:**
- Utilize the Cluster Monte Carlo (CMC) dataset, an N-body simulation code
- Use Normalizing Flows, a family of generative AI models, to interpolate astrophysical outcomes
- Optimize network performance by fine-tuning hyperparameters and normalizings on how we simulate the data
