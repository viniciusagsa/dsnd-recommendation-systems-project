# IBM Recommendation Systems Project

Explore and compare four recommendation system approaches to suggest relevant articles on IBM Watson Studio Community:  

- **Rank-Based Filtering** – recommends most popular articles  
- **User-User Collaborative Filtering** – recommends based on similar users  
- **Content-Based Recommendations** – uses TF-IDF + K-means for semantic similarity  
- **Matrix Factorization (SVD)** – personalized recommendations via latent factors  

---

## 🚀 Getting Started

### Dependencies

```
pandas >= 1.3.0
numpy >= 1.21.0
scikit-learn >= 1.0.0
matplotlib >= 3.4.0
pickle >= 4.0
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/viniciusagsa/dsnd-recommendation-systems-project
cd dsnd-recommendation-systems-project
```

2. Install Python packages:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3. Verify data:
```
# Ensure these exist:
# starter/data/user-item-interactions.csv
# starter/Recommendations_with_IBM.ipynb
```

4. Launch notebook:
```bash
jupyter notebook starter/Recommendations_with_IBM.ipynb
```

---

## 📊 Insights & Strategy

- **New Users:** rank-based recommendations  
- **Moderate Activity Users:** user-user collaborative filtering  
- **Content Discovery:** content-based recommendations  
- **Active Users:** matrix factorization  

Optimal settings: 150–200 latent features (SVD), 50 clusters (content-based). Cosine similarity performs best across methods.

---

## 🛠 Built With

* [Pandas](https://pandas.pydata.org/) – data manipulation  
* [NumPy](https://numpy.org/) – numerical computing  
* [Scikit-learn](https://scikit-learn.org/) – ML algorithms  
* [Matplotlib](https://matplotlib.org/) – visualization
* [Seaborn](https://seaborn.pydata.org/) - visualization  
* [Jupyter Notebook](https://jupyter.org/) – interactive development  

---

## 📄 License

[License](LICENSE.txt)
