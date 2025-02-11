# RAG_Pipeline
This repository provides a step-by-step walkthrough of the RAG (Retrieval-Augmented Generation) pipeline codebase
 The pipeline is implemented using a series of Jupyter notebooks. Follow the steps below to understand and run the pipeline.

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.11.11
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)
- remove `.example` from `.env.example` and fill in the required values

  ## Setup

1. **Clone the Repository**
    ```bash
    git clone https://github.com/devzohaib/RAG_Pipeline.git
    cd RAG_Pipeline
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```
## Notebooks Overview

### 1. Data Preparation

**Notebook:** `01_data_preparation.ipynb`

- **Objective:** Prepare and preprocess the dataset for the RAG pipeline.
- **Steps:**
  1. Load the dataset.
  2. Clean and preprocess the text data.
  3. Save the processed data for further use.
