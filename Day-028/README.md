# Day 28 - K‑Means Clustering (Elbow, Knee, Silhouette)

Today I implemented and evaluated **K‑Means** clustering on a synthetic blobs dataset, explored methods to choose the number of clusters, and visualized clustering results.

---

## Key Learnings

- Learnt how to build and evaluate **K‑Means** clustering models on a 2‑D synthetic dataset
- Generated synthetic data using `make_blobs` and visualized the raw clusters with a scatter plot
- Applied preprocessing using `StandardScaler` and split data with `train_test_split`
- Implemented the **Elbow Method** (WCSS) to inspect within‑cluster variance as `k` varies
- Used `KneeLocator` to automatically detect the elbow point and suggest an optimal `k`
- Computed **Silhouette Scores** across different `k` values to evaluate cluster cohesion and separation
- Visualized cluster assignments using scatter plots colored by predicted labels
- Compared elbow and silhouette analyses to choose a suitable number of clusters; learned to consider both metrics together