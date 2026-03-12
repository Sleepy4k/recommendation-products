# Product Recommendation System

Amazon E-Commerce recommendation system using SVD and KNN model based Health and Care category product data.

## Project Structure

```
recommendation-products/
├── pyproject.toml                          # Project dependencies
├── README.md                               # This file
├── notebook/                               # Model training
│   └── main.ipynb                          # Jupyter notebook for training
└── data/                                   # Saved model files (generated)
    └── amazon_product_reviews_2023.jsonl   # Amazon dataset
```

## Installation

### Prerequisites

- Python 3.12
- pip or uv package manager

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sleepy4k/recommendation-products
   cd recommendation-products
   ```

2. **Install dependencies**:
   
   Using pip:
   ```bash
   pip install -r requirements.txt
   ```
   
   Or using uv:
   ```bash
   uv sync
   ```

3. **Verify installation**:
   ```bash
   python -c "import matplotlib, numpy, pandas, sklearn, surprise; print('All dependencies installed!')"
   ```

4. **Download Dataset**:

   Change directory to data:
   ```bash
   cd data
   ```

   Open README file:
   ```bash
   type README.md   # Windows
   cat README.md    # Linux
   ```

   Download Dataset from url give