# Navigating Random Realms: From Markov Chains to Hidden Models  
### Credit Card Fraud Detection using Stochastic Modeling

This project demonstrates the application of Markov Chains and Hidden Markov Models (HMMs) to detect fraudulent credit card transactions by modeling user spending behavior as a stochastic process. It connects theoretical probabilistic models with real-world fintech applications.

---

## Objective
To detect fraudulent transactions by modeling normal user spending behavior through Markov Chains and Hidden Markov Models (HMMs), and identifying anomalies using sequence likelihood estimation and the Viterbi algorithm.

---

## Approach
1. **Data Source**  
   - Dataset: [Credit Card Fraud Detection - Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
   - Used transaction features such as `Time`, `Amount`, and PCA components.

2. **Modeling Steps**
   - Represented each transaction category as a state in a Markov Chain.  
   - Constructed a transition probability matrix to capture spending transitions.  
   - Trained a Gaussian Hidden Markov Model (HMM) on non-fraudulent transactions to learn typical behavioral patterns.  
   - Applied sequence likelihood estimation and the Viterbi decoding algorithm to flag anomalous sequences as potential frauds.

---

## Results
- Achieved accuracy around **85%** with **false-positive rates below 10%**.  
- The model assigned high likelihoods to normal sequences and effectively flagged unusual spending as anomalies.  
- Demonstrated the interpretability and robustness of stochastic modeling in fraud detection.

---

## Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, scikit-learn, hmmlearn  
- **Environment:** Jupyter Notebook  

---
