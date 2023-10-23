# EMNLP23_Fair_Explanation

Code of EMNLP 2023 Paper "Towards Conceptualization of ‘Fair Explanation’: Disparate Impacts of anti-Asian Hate Speech Explanations on Content Moderators".

## Dependencies
* numpy==1.23.0                   
* pandas==1.5.3           
* seaborn==0.11.2
* matplotlib==3.7.1
* scipy==1.10.1     
* statsmodels==0.13.5
* scikit-learn==1.0.2
* torch==2.0.1 
* transformers==4.30.2 
* lime==0.2.0.1 
* econml==0.14.1

## Functionalities
* EMNLP_roberta_train.ipynb: code to fine-tune a roberta binary (hate vs. non-hate) classifier.

* EMNLP_roberta_test_saliency.ipynb: code to generate saliency maps (LIME) explanations.

* EMNLP_roberta_test_counter.ipynb: code to generate predictions for counterfactual explanations

* EMNLP_calculate_all_metrics.ipynb: code to calculate 5 output metrics (accuracy, label time, mental discomfort, perceived workload, and stereotype activation).

* EMNLP_statistical_analysis_t_test_all_metrics_final.ipynb: code to conduct t-tests under different conditions (no explanations, saliency maps, counterfactual explanations) and to reproduce all plots included in the paper.

* EMNLP_hte_causal_analysis.ipynb: code to conduct heterogeneous treatment effects analysis. 

* EMNLP_evaluate_individual_fairness.ipynb: code to conduct individual fairness analysis. 


