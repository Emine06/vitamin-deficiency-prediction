
# Vitamin & Mineral Deficiency Disease Prediction System

## Project Overview
This project builds a machine learning-based clinical decision support system to predict vitamin and mineral deficiency diseases using:

- Patient symptoms
- Blood laboratory values
- Nutritional intake information

The system aims to simulate how a physician evaluates symptoms and laboratory results together.

## Dataset
The dataset contains **4,000 patient records** including:

- Demographic information
- Lifestyle factors
- Dietary intake levels
- Clinical symptoms
- Laboratory blood measurements

Target diseases include:

- Healthy
- Anemia
- Rickets / Osteomalacia
- Scurvy
- Night Blindness

## System Workflow

### 1. Disease Prediction
Disease is predicted using:

- Symptom indicators
- Blood test values

Model used:
- Random Forest Classifier

### 2. Dietary Intake Evaluation
After disease prediction, the system checks:

- Whether vitamin intake from diet is sufficient
- If intake is below recommended levels
Example checks:
- Vitamin B12 intake
- Vitamin D intake
- Iron intake

### 3. Absorption Problem Detection
If dietary intake is sufficient but blood levels are low, the system flags possible absorption issues.

Example:
- Adequate Vitamin D intake but low serum Vitamin D level.

### 4. Automatic Patient Report
The system produces an automatic report including:

- Predicted disease
- Risk probability
- Dietary deficiencies
- Possible absorption issues
- Nutritional recommendations

## Model Performance
Disease prediction accuracy:

