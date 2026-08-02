# Copula-GARCH Interactive Dashboard: Workflow Introduction

### Mehrdad Heyrani (https://www.linkedin.com/in/mehrdad-heyrani/)

This dashboard, built with **Dash** and **Plotly**, offers a comprehensive tool for analyzing **dynamic dependence** and **bivariate tail risk** between various power hubs and Henry Hub natural gas prices. It enables users to gain deeper insights into complex market relationships and make informed decisions.

## Key Capabilities:

*   **Dynamic Dependence Analysis (Section 1):** Explore rolling rank correlations (Kendall's tau, Spearman's rho) with confidence bands, rolling annualized volatilities, and implied heat rates/price ratios. These visual tools help identify evolving relationships and market anomalies.
*   **Model Output & Diagnostics (Section 2):** Fit advanced **GARCH marginal models** (Standard, GJR, EGARCH) with various innovation distributions (Normal, Student's t, Skewed Student's t, GED). Subsequently, perform **bivariate copula selection** across 9 families (Gaussian, Student-t, Clayton, Gumbel, Frank, Joe, Survival Gumbel, Survival Clayton, SJC) to capture the full spectrum of dependencies, including tail dependence.
*   **Detailed Diagnostics:** Visualize best-fit copulas through empirical 2-D Kernel Density Estimates (KDE) of pseudo-observations, theoretical density heatmaps of the fitted copula, and contour overlays on empirical scatter plots for rigorous tail-asymmetry checks. A concise dependence summary bar chart quantifies Kendall's tau, lower tail dependence (λ_L), and upper tail dependence (λ_U).

## Data & Usage:

*   The dashboard can seamlessly load data from an Excel file (e.g., `Power Price Realized 2021-2026.xlsx`) or generate synthetic data for demonstration and testing purposes.
*   **Interactive Controls:** Users can intuitively select Hub 1 and Hub 2 assets, GARCH family, innovation distribution, and rank correlation method via dropdown menus. A dedicated 'Run analysis' button updates all plots and tables dynamically based on selections.

This powerful tool is essential for financial analysts, researchers, and anyone seeking to understand and model the complex dependencies in energy markets, providing both granular analysis and high-level insights.
