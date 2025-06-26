# DeepMARCOSMobi

**AI-Driven, Explainable Smartphone Recommendation System**

DeepMARCOSMobi is an intelligent and adaptive smartphone ranking system that leverages Deep Neural Networks (DNN), the MARCOS (Measurement Alternatives and Ranking according to Compromise Solution) MCDM method, and LLaMA-3 (Large Language Model Meta AI) to generate highly personalized and explainable recommendations for users overwhelmed by complex smartphone specifications.

---

## Abstract

The growing complexity of smartphone specifications necessitates intelligent, user-centric ranking systems. **DeepMARCOSMobi** dynamically adjusts decision criteria weights through deep learning, ranks alternatives using MARCOS, and provides natural language explanations using LLaMA-3. The system outperforms traditional MCDM approaches by 15% in recommendation accuracy and achieves 90% user satisfaction for its explainability and personalization features.

---

##  Methodology

###  System Architecture

The system consists of three primary modules:

1. **Preprocessing & Feature Extraction**  
   - Collects user preferences, smartphone specifications, and historical data.  
   - Converts smartphones into feature vectors:
     ```
     X = [x1, x2, ..., xn]
     ```

2. **Dynamic Weight Adjustment via Deep Learning**  
   - A DNN learns optimal weights `W = [w1, w2, ..., wn]` where:
     ```
     ∑ wi = 1
     ```
   - Trained using user interaction history and real-time data.
   - Reduces error between predicted and actual user preferences.

3. **Explainability through GPT-2**  
   - Generates human-readable explanations for ranked smartphones, such as:  
     > "Based on your preference for high battery life and gaming performance, the XYZ smartphone ranks highest due to its 5000mAh battery and Snapdragon 8 Gen 2 processor."

---
