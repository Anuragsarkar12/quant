Objective
This project aims to segment financial markets into distinct behavioral regimes using unsupervised learning techniques. The regimes are characterized by three key factors:
1. Trending vs. Mean-Reverting
2. Volatile vs. Stable
3. Liquid vs. Illiquid

The analysis leverages real-time order book and trade volume data, incorporating advanced feature engineering, clustering methods (HDBSCAN, K-Means, GMM), and insightful visualizations.


Key Highlights
- Feature Engineering: Extracted liquidity, volatility, and price action features.
- Clustering: Identified regimes using HDBSCAN, achieving superior metrics (Silhouette: 0.365, DB Index: 0.681).
- Regime Insights: Analyzed regime-specific characteristics and transitions.
- Visualizations: Included PCA variance explained, t-SNE cluster visualization, and regime evolution over time.


Results
- Identified stable and interpretable regimes (e.g., "Stable & Liquid & Neutral").
- High persistence observed within regimes with well-defined transition probabilities.
- Provided actionable insights for market behavior analysis.
