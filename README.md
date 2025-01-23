# SecurityAttackTypeDataset

This repository provides datasets designed to explore the relationship between complexity and vulnerability metrics in identifying security vulnerabilities and their attack types at the function level. These datasets can be used as input for machine learning and deep learning models to develop high-accuracy security vulnerability detection systems.

Unlike previous datasets, this collection is structured separately for each security attack type. In each attack-specific dataset, the number of vulnerable functions is balanced with non-vulnerable functions, extracted from real-world projects. For instance, in the **DoS attack dataset**, there are 11 subsets. Each of the first 10 datasets contains a balanced distribution of vulnerable functions related to DoS attacks and non-vulnerable functions, which are extracted in a distributed manner from multiple real-world projects.

Each dataset consists of **complexity metrics (C1, ..., C4)** and **vulnerability metrics (V1, ..., V11)**. By applying machine learning and deep learning techniques on these datasets, we have developed models capable of achieving high accuracy in vulnerability detection and security attack classification. Additionally, these datasets enable the identification of key influencing metrics, allowing us to determine which factors contribute most effectively to vulnerability detection.
