# IBM Machine Learning Capstone: Course Recommender System

A comprehensive, multi-strategy recommender engine built for online learning platforms to drive user engagement, increase course completion rates, and boost revenue. This project combines business impact with advanced machine learning techniques and showcases performance using real-world engagement metrics.

## 🚀 Project Highlights
- **Business Problem:** Solves information overload and course discovery challenges in online education by surfacing the right courses at the right time for each learner.
- **Multi-Strategy Approach:** Implements content-based, collaborative filtering, clustering, and neural embedding recommenders, combined in a hybrid system to leverage the strengths of each.
  - *Content-Based*: Genre vector/user profile, TF-IDF/cosine similarity, user-profile clustering (K-means)
  - *Collaborative Filtering*: User-based KNN (k=10), matrix factorization (10 latent factors)
  - *Neural Architecture*: NeuMF-style (deep neural embeddings)
- **Evaluation:** Robust evaluation using RMSE, MAE for accuracy, Precision@5, Recall@5, and Coverage. All metrics computed on 20% hold-out set.
- **Business Result:** Top-performing models projected to significantly increase user engagement, discovery, and completion rates with clear business value.

## 📊 Dataset
- 93 courses × 6 genres
- 200 users, 3,526 ratings (81% sparse)
- Balanced genre split, realistic positive-skew rating distribution

## 🛠️ Technologies Used
- Python (pandas, numpy, scikit-learn, surprise, Keras/PyTorch if NeuMF used)
- Jupyter Notebook, Data Visualizations (matplotlib, seaborn)

## 📝 Key Features
- State-of-the-art recommender workflows: feature engineering, cold-start mitigation, genre/exploration boost
- Clear, interpretable results with business- and user-focused metrics
- Recommendations for future work: containerized serving layer, real-time feedback (MLOps), fairness auditing

## 💡 Results
- *Genre-weighted content recommender* outperforms for core metrics
- Neural and hybrid approaches enable exploration and catalog coverage
- Projected improvement in key business outcomes at scale

## 📁 Repository Structure

```
├── /slides/          # Presentation slides (attach .pptx or .pdf for recruiters)
├── notebooks/        # Jupyter notebooks with analysis and modeling
├── data/            # Course and rating datasets
├── src/             # Source code for recommender models
├── results/         # Model evaluation results and visualizations
└── README.md        # This file
```

**Note:** Please see the `/slides` directory for presentation materials that summarize this project for recruiters and stakeholders.

## 👤 Author
Jimmie Williams
