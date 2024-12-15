# Fraud Detection Pipeline with Dockerized ML

This project detects fraudulent transactions using machine learning models in a Dockerized pipeline. It showcases the ability to preprocess large-scale data, train and evaluate classification models, and deploy scalable APIs.

---

## Key Features

1. **Fraud Detection**:
   - Use classification models like Random Forest and XGBoost for fraud detection.
2. **Dockerized Pipeline**:
   - Build a containerized solution for training, inference, and deployment.
3. **API Integration**:
   - Expose model predictions via RESTful APIs.

---

## Repository Structure

```
Fraud_Detection_Pipeline/
├── data/
│   ├── raw/                  # Unprocessed transaction data
│   ├── processed/            # Cleaned and feature-engineered data
├── notebooks/                # Jupyter notebooks for exploration
├── src/
│   ├── preprocessing.py      # Data preprocessing scripts
│   ├── train_model.py        # Model training script
│   ├── evaluate_model.py     # Evaluation metrics
├── api/
│   ├── app.py                # FastAPI application
├── docker/
│   ├── Dockerfile            # Docker configuration
│   ├── docker-compose.yml    # Compose file for multi-container setup
├── tests/                    # Unit tests
├── results/
│   ├── metrics.json          # Evaluation metrics
│   ├── figures/              # Visualizations
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.