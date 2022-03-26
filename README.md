Using XG Boost to apply multi-step forecasting. Based on a paper from Elsayed, Thyssens et al. (2021).
I copied their code and made some changes to the code to have a sliding window for the testing period, 
which means we make prediction for the first 5 steps and then for the following 5 steps, etc.

The original paper can be found here: https://arxiv.org/abs/2101.02118
