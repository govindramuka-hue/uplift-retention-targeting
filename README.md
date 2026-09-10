# Uplift Modeling for Email ROI Optimization

This project demonstrates how causal machine learning (Uplift Modeling) can be used to optimize marketing ROI by targeting "Persuadables" rather than relying on naive response models.

### Business Impact
Using a Two-Model (T-Learner) approach on the MineThatData randomized email dataset, this model proved that targeting only the top 5 deciles of customers captures the vast majority of the campaign's success while instantly cutting email send costs by 50%.

### Repository Structure
* `report.pdf`: A 1-page executive memo summarizing the findings and business recommendations.
* `notebook.ipynb`: The Python codebase containing data setup, model training (Scikit-Uplift, Scikit-Learn), and evaluation.
* `output/`: Contains the Qini curve visualizations and the calculated decile lift table.