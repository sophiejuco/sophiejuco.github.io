# Data Science Consultant

## Experience
**Data Science Consultant,** Kalypso, A Rockwell Automation Business (Sep 2025-Present)

**Research Assistant,** New York University (Sep 2024-Aug 2025)

**Data Science Consultant Intern,** Kalypso, A Rockwell Automation Business (Jun-Aug 2024)

**Data Analytics Consultant,** Passaic Metal and Building Supplies Company (2021-2023)

## Education
**New York University, Graduate School of Arts & Science,** New York, NY (_May 2025_)  
Master of Science, Data Science

**New York University, College of Arts & Science,** New York, NY (_May 2023, Cum Laude_)  
Bachelor of Art in Data Science; Minors: Astronomy and Food Studies

## Projects
**How Do LLMs Take the SAT and ACT?** (Graduate Natural Language Understanding Final Project)
[GitHub Repository](https://github.com/sophiejuco/NLU-Final-Project)

As a follow up project to the *Answer-Level Calibration for SAT/ACT Multiple Choice Questions* project, GPT-2 XL was fine-tuned on a novel dataset of 1,315 official SAT/ACT reading comprehension questions and a comparable RACE-H benchmark to investigate whether LLMs learn test-specific heuristics. Model interpretability was assessed through four experiments — prompt information removal, synonym-based noise injection, chain-of-thought prompting, and rationality profiling via SHAP attributions — revealing that the SAT/ACT fine-tuned model learned a strong reliance on exam-specific vocabulary and syntax.

**Answer-Level Calibration for SAT/ACT Multiple Choice Questions** (Graduate NLP with RL Capstone Project)
[GitHub Repository](https://github.com/sophiejuco/DS_GA_1011-Final_Project)

Applied answer-level calibration (ALC) techniques to a GPT-2 model to evaluate performance on a dataset of ~1,000 official SAT/ACT multiple-choice questions spanning English, History, and Science, with the goal of identifying which prompt and answer tokens most influence correct predictions. Ten calibration methods were benchmarked — including length normalization, token calibration, and Bayesian calibration — and a token saliency score extractor was built to surface the key terms driving model decisions.

**Multimodal Sequencing for POS Tagging** (Graduate NLP Capstone Project)
[GitHub Repository](https://github.com/sophiejuco/POSnet)

Developed a multimodal neural network that jointly fuses text embeddings with VGG16-extracted image features to improve Part-of-Speech tagging, particularly for homographs and context-dependent words. A custom annotated dataset was constructed by pairing tokens from the RecipeQA corpus with associated step images. The multimodal NN was evaluated against NLTK Unigram and Bigram taggers and a manual human evaluation, achieving a best score of F1=0.8937.

**Music Assessment & Recommendation System using Spotify Music Ratings Data** (Graduate Intro to Data Science Capstone Project)  
[GitHub Repository](https://github.com/sophiejuco/DSGA-1001_Final_Project)  

Using Spotify data on 52,000 songs and song ratings by 10,000 users, this project sets out to better understand what makes music popular as well as audio features that make up specific genres. A recommender system for the 10,000 users is also built in this project.

**Document Localization with Transfer Learning** (Advanced Topics in Data Science: Deep Learning Capstone Project)  
[GitHub Repository](https://github.com/sophiejuco/DS301_final_project)  

Pre-trained ResNet 18 (ImageNet) CNN models refined to recognize document boundaries, evaluating performance using intersection-over-union. Three variations of refinement of the pre-trained CNN model were executed using *TensorFlow* and the results were used to find the optimal refined model. The three variations were (1) regression head training only, (2) partial fine-tuning, and (3) full fine-tuning.

**Image Style Transfer** (Graduate Intro to Computer Vision Capstone Project)
[GitHub Repository](https://github.com/sophiejuco/CV-Final-Project)

Implemented neural style transfer following Gatys et al. (2016), using a pretrained VGG-19 CNN to separate and recombine the content of one image with the artistic style of another by minimizing a combined content and style loss function. The implementation extended the original paper with an Adam optimizer, max pooling, and a novel dual-style blending feature.

**90-Day Metastatic Cancer Diagnosis Predictor** (Graduate Responsible Data Science Capstone Project)
[GitHub Repository](https://github.com/sophiejuco/RDS-Final-Project)

Used a real-world dataset of ~18,700 patient records (from Gilead Sciences) to train a classification system to predict whether a patient with Metastatic Triple Negative Breast Cancer would receive a diagnosis within 90 days of testing, incorporating demographics, insurance, treatment history, and geo-demographic enrichment data. Gradient boosting models (XGBoost, LightGBM, CatBoost) were trained using cross-validation and optimized for ROC-AUC, with fairness evaluated across race, age, region, and payer type subgroups using metrics including demographic parity ratio and equalized odds ratio.

**Hypothesis Testing using Movie Ratings Data** (Graduate Intro to Data Science Project 1)  
[GitHub Repository](https://github.com/sophiejuco/DSGA-1001_data_analysis_project1)  

Using movie ratings data and viewer characteristics data, hypothesis testing was used to answer questions surrounding movie popularity and enjoyment.

**Machine Learning Methods using Movie Ratings Data** (Graduate Intro to Data Science Project 2)  
[GitHub Repository](https://github.com/sophiejuco/DSGA-1001_Data_Analysis_Project2)  
Linear regression, multiple linear regression, regularized regression, ridge regression, LASSO regression, and logistic regression models were implemented and trained on movie ratings data and viewer characteristics data to produce predictions involving movie enjoyment and viewers' ratings.
