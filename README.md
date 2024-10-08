# Neural Network Project

## Overview

This project is focused on building, training, and evaluating neural network models. It includes components for loading data, defining model architectures, training models, and performing evaluations.

## Getting Started

### Prerequisites

- Python 3.8 or later
- Recommended to use a virtual environment for package management.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/nnfs.git
   cd nnfs
   ```

2. **Set up virtual environment** (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**:
   - Create a `.env` file in the root directory to store secrets, API keys, or other environment-specific variables.
5. **Run Jupyter Notebook** (if needed):
   ```bash
   jupyter lab
   ```

## Usage

- **Data Preparation**: Place your datasets in the `data/raw/` directory.
- **Model Training**: Use `src/train.py` to train your model with the dataset.
- **Evaluation**: Use `src/evaluate.py` to evaluate your trained models on test data.

## Testing

To run the tests, use `pytest`:

```bash
pytest
```
