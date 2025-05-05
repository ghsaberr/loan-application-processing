# Automated Loan Application Processing

## Overview
This project implements an automated system for processing and evaluating loan applications using natural language processing (NLP) and machine learning techniques. The system analyzes both textual and numerical data from loan applications to assess risk levels and make informed decisions.

## Features
- Automated processing of loan applications
- Text analysis of personal statements, career narratives, and financial documents
- Risk assessment using machine learning
- Support for batch processing of multiple applications
- Detailed performance metrics and evaluation reports

## Installation
1. Clone the repository:
```bash
git clone https://github.com/ghsaberr/Automated-Loan-Application-Processing.git
cd Automated-Loan-Application-Processing
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Model Performance
- Overall accuracy: 75%
- High-risk identification: 83% F1-score
- Medium-risk identification: 55% F1-score
- Cross-validation score: 0.65 (±0.20)

## Data Generation
The synthetic data was generated to:
- Simulate real-world loan application scenarios
- Create a balanced dataset for testing
- Include various risk profiles and application types
- Maintain realistic distributions of key features