# spam-detection-research
multi-lingual-spam-detection-using-methaheuristic-algorithems-sentence-transformer

# 📌 Objective
Reproduce and improve spam detection model on multi-lingual dataset.

#🧪 Methodology
1. Implemented baseline model from research paper
   -use data set enron 1 contains 5000 records of spam and ham . It is unbalanced data
   -firstly we performed preprocessoing and tf-idf vectorization for feature extraction
   -secondly we use xgboost for feature selection
   -third we applied the hybrid-algo+lr
   -finally we calculated the confusion matrix
 2.Proposed improvements:
   -previous shows beter performance on english data but fails on multi-lingual data
   - we we improved a madel that shows beter performance on multilingual data
   - we used sentence transformer for multi-lingual embedings then metaheuristic algo+lr 
   - Model tuning

#📊 Results

| Model        | Accuracy | F1 Score |
|-------------|--------|---------|
| Baseline    | 88%    | 0.85    |
| Improved    | 94%    | 0.92    |


