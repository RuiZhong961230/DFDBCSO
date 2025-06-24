# DFDBCSO
Dynamic Fitness-Distance Balance Competitive Swarm Optimizer: Performance Investigation, Engineering Simulation, and Application in Superconductor Critical Temperature Prediction

## Abstract
This paper introduces the Dynamic Fitness-Distance Balance (DFDB) strategy to enhance the Competitive Swarm Optimizer (CSO), resulting in the proposed DFDBCSO algorithm. DFDBCSO improves exploration efficiency and solution accuracy by dynamically balancing individual fitness and population diversity throughout the optimization process. In the early exploration phase, DFDB emphasizes solution diversity by encouraging competition based on the distance from the best solution (\(P_{\text{best}}\)), fostering a balance between active and less active individuals. In the later stages, the focus shifts toward fitness-based competition, accelerating convergence by prioritizing interactions between high- and low-performing individuals. We conducted comparative experiments on the CEC2017, CEC2020, and CEC2022 benchmark functions against other algorithms. On the CEC2017 benchmark, DFDBCSO achieved the highest average ranking in the 30-dimensional setting and ranked second in both the 50-dimensional and 100-dimensional settings. For CEC2020, DFDBCSO secured the top average ranking across the 10-dimensional, 20-dimensional, and 100-dimensional settings. Similarly, on the CEC2022 benchmark, DFDBCSO achieved the highest average ranking in both the 10-dimensional and 20-dimensional settings. Additionally, we evaluated the performance of DFDBCSO on five engineering design problems. DFDBCSO ranked first on the CBDP, REBDP, and WBDP problems, while it ranked second and third on the SRDP and TCSDP problems, respectively. Furthermore, DFDBCSO is integrated into an ensemble regression model to predict the critical temperature of superconductors using atomic and physicochemical properties. The proposed DFDBCSO-Ensemble model achieves the highest prediction accuracy, outperforming the second-ranked ExtraTrees model by reducing the Mean Squared Error (MSE) by 1.82, decreasing the Mean Absolute Error (MAE) by 0.04, and improving the R-squared score R^2 by 0.01.

## Citation
@article{Cao:25,  
title={Dynamic Fitness-Distance Balance Competitive Swarm Optimizer: Performance Investigation, Engineering Simulation, and Application in Superconductor Critical Temperature Prediction},  
author={Yang Cao and Xingbang Du and Jun Yu and Rui Zhong and Masaharu Munetomo},  
journal={Cluster Computing},  
pages={},  
year={2025},  
volume={},  
publisher={Springer},  
not={Accepted}  
}  

## Datasets and Libraries
CEC benchmarks are provided by opfunu==1.0.0 library.

## Contact
If you have any questions, please don't hesitate to contact zhongrui[at]iic.hokudai.ac.jp
