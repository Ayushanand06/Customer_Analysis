# CustomerCompass

## Overview
Understanding customer sentiment is key to building better products and services. **CustomerCompass** helps businesses analyze customer feedback using AI-powered sentiment classification and satisfaction prediction. With **DistilBERT** and **machine learning models**, it delivers deep insights and **Power BI dashboards** for data-driven decisions.

## Features
- 📝 **Sentiment Analysis:** Detects if feedback is **positive, negative, neutral, or irrelevant** (90% accuracy).
- 📊 **Satisfaction Prediction:** Uses purchase frequency, demographics, and feedback to predict scores (83% accuracy).
- 🔍 **Insightful Analytics:** Processes data with **scikit-learn**, **PyTorch**, and visualizes trends with **Power BI**.

## Installation
```sh
git clone https://github.com/yourusername/CustomerCompass.git
cd CustomerCompass
pip install -r requirements.txt
```

## Usage
### 🏷 Sentiment Analysis
```python
from transformers import pipeline
classifier = pipeline("text-classification", model="distilbert-base-uncased-finetuned-sst-2-english")
print(classifier("Love the product!"))
```

### 📉 Satisfaction Prediction
```python
import joblib, numpy as np
model = joblib.load("satisfaction_model.pkl")
print(model.predict(np.array([[25, 1, 5, 4.5, 4.2]])))
```

## Results & What's Next
- ✅ **Sentiment Model Accuracy:** 90%
- ✅ **Satisfaction Prediction Accuracy:** 83%
- 🚀 **Next Steps:** Fine-tune models, expand datasets, and integrate with CRM systems for real-time analysis.


