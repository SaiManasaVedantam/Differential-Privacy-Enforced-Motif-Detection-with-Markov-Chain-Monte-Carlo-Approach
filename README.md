# Differential-Privacy-Enforced-Motif-Detection-with-Markov-Chain-Monte-Carlo-Approach

## Idea
This project aims to detect Motif which is a short and recurring pattern in DNA holding critical genetic information using Machine Learning techniques like Markov Chain Monte Carlo (MCMC) algorithm while making the model robust against inference attacks by enforcing Differential Privacy on the data.

## Scope
Learning patterns from data to identify Motifs helps in biomedical research to invent new medicines that could prevent and/or cure several diseases to protect mankind. Also, Motifs can be used as an advanced way to provide security to a clan just like Iris and Fingerprint scan. Moreover, it may contribute to the research towards DNA data storage where it is believed that a single strand of DNA can store voluminous data.

## Execution
#### For the working system
1. dna_data_generation_and_differential_privacy.ipynb to generate datasets containing 1000, 5000, 10000, 50000, 100000 records
2. mcmc_gibbs.ipynb to implement MCMC's Gibbs sampling for motif detection and to make a preliminary analysis
3. gibbs_application_covid_detection.ipynb to detect COVID 19 using DNA motifs
4. Use the functions from file_io.ipynb, visualization.ipynb & info_content_ops.ipynb for utility functions.

#### For extended analysis
1. gibbs_motif_length_analysis.ipynb to analyze "Fixed information content → Different motif length & datasets"
2. gibbs_info_content_analysis.ipynb to analyze "Fixed motif length → Different information content & datasets"

## Related work
#### How differential privacy works:  
https://www.analyticssteps.com/blogs/what-differential-privacy-and-how-does-it-work 

#### Markov Chain Monte Carlo approach - Gibbs Sampling:  
https://towardsdatascience.com/gibbs-sampling-explained-b271f332ed8d

#### Research:
1. https://ieeexplore.ieee.org/document/9044511
2. https://ieeexplore.ieee.org/document/7565504
3. https://dl.acm.org/doi/abs/10.1007/s00521-020-04873-z
4. https://www.scientificamerican.com/article/dna-the-ultimate-data-storage-solution/

#### Resources for learning:
1. https://www.biostat.wisc.edu/bmi776/spring-07/lectures/gibbs-example.pdf
2. https://www.youtube.com/watch?v=cAtCTVVqCVU (Playlist)
3. https://www.ncbi.nlm.nih.gov/nuccore/1798174254
