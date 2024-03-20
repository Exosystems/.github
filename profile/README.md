# Exosystems Github

Hello! Welcome to the company page. 
Here you will find the source code for the projects we are currently developing and more.

**General guidelines**: 
1. If you are creating a new repository follow this [template](https://github.com/Exosystems/RnD_template_repo) 
2. If there is a new project that include other members you can use this [template](https://github.com/orgs/Exosystems/projects/18)
3. For more questions or issues [Contact Us](mailto:exosystems@exosystems.io)
   
---

### Databases list

The company has collected various databases that you can find in the following [repository](https://github.com/Exosystems/databases).
Unless specified, all databases was collected using the company exoPill. 

| Dataset | #Samples| #Channels | #Classes | Length | Freq (Hz) |
| --- | --- | --- | --- | --- | --- |
| KHU-EMG | 90 | 6 | 4 | 6500 | 1000 |
| KHU-IMU | 180 | 24 | 4 | - | 148 |

---

### Benchmark list

There are various project related to EMG and IMU under development. The following table summarizes the statistics of the models under research and the current best performance

| Project | Metric| Performance | Database | Repo |
| --- | --- | --- | --- |--- |
| Sarcopenia Classification | Accuracy | 0.70 | KHU-IMU | link |

---

### General description of current repositories

| repo name | Contributor| Summary |
| --- | --- | --- |
| [RnD_fitness_IMU](https://github.com/Exosystems/RnD_fitness_IMU) | [@meier](https://github.com/Meier0105) | Flexibility and gait analysis utilizing IMU data (exoFit) |
| [RnD_fitness_emg](https://github.com/Exosystems/RnD_fitness_emg) | [@ellie](https://github.com/ellie-exo) | Muscle balance and fatigue measurement utilizing EMG data from our database, collected during squat and isometric exercises (exoFit) |
| [RnD_ECF_emg](https://github.com/Exosystems/RnD_ECF_emg) | [@ellie](https://github.com/ellie-exo) | Voluntary contraction detection utilizing EMG data. Includes preprocessing for controlling electrical stimulation (EMG-Controlled FES) |
| [RnD_MQ_regression_smcs_khu](https://github.com/Exosystems/RnD_MQ_regression_smcs_khu) | [@ellie](https://github.com/ellie-exo) | MQ regression utilizing SMCS data from KHU database |
| [RnD_SMA_regression](https://github.com/Exosystems/RnD_SMA_regression) | [@chloe](https://github.com/soyoung-exo) | Spinal Muscular Atrophy(SMA) regression using sEMG data(SMA-MQ).|
| [RnD_gait_analysis_imu](https://github.com/Exosystems/RnD_gait_analysis_imu) | [@pato](https://github.com/patoalejor-exo)| 🏃 Start code for working with Pfizer's library skdh for gait analysis using accelerometer raw signal from IMU sensor |
| [RnD_sarcopenia_classification_imu_khu](https://github.com/Exosystems/RnD_sarcopenia_classification_imu_khu)| [@pato](https://github.com/patoalejor-exo) | Sarcopenia classification utilizing 4 IMU (acc and gyro) from KHU database between healthy and "risk" groups. Includes data ingest, preprocessing, split, model build, train, test, and metrics|
| [RnD_sarcopenia_classification_smcs_khu](https://github.com/Exosystems/RnD_sarcopenia_classification_smcs_khu)| [@pato](https://github.com/patoalejor-exo) | Sarcopenia classification utilizing SMCS data from KHU database, the data is filtered to use the same subjects from IMU analysis and split between healthy and "risk" groups. Includes data ingest, preprocessing, split, model build, train, test, and metrics|
| [RnD External Requests](https://github.com/Exosystems/RnD_External_Requests)| [@meier](https://github.com/Meier0105)| External Requests to RnD|
| [RnD_MFI_D_Sarcopenia_WND](https://github.com/Exosystems/RnD_MFI_D_Sarcopenia_WND)| [@meier](https://github.com/Meier0105)| Sarcopenia regression utilizing SMCS data from WND database (handgrip strength, SMI, gait speed)|
| insert link | [@will](https://github.com/ExosystemsWill) | todo |

