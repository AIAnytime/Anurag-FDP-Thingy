Build a modern healthcare web application called **MediScore Pro**.

## Objective

Create a professional clinical risk calculator suite for healthcare professionals. The application should work completely on the frontend with no API keys, backend services, authentication, or external integrations.

The application should have a clean hospital-grade UI suitable for doctors, pharmacists, medical students, and healthcare educators.

---

## Core Features

Create a dashboard with the following calculators:

### 1. BMI Calculator

Inputs:

* Height (cm)
* Weight (kg)

Outputs:

* BMI value
* BMI category:

  * Underweight
  * Normal Weight
  * Overweight
  * Obesity Class I
  * Obesity Class II
  * Obesity Class III
* Color-coded risk indicator
* Brief lifestyle recommendation

---

### 2. Type 2 Diabetes Risk Calculator

Inputs:

* Age
* Gender
* BMI
* Family history of diabetes (Yes/No)
* Physical activity level
* Smoking status

Outputs:

* Risk Score
* Low / Moderate / High Risk
* Visual gauge meter
* Prevention recommendations

Use a simplified educational risk scoring model.

---

### 3. eGFR Calculator (Kidney Function)

Inputs:

* Age
* Gender
* Serum Creatinine

Outputs:

* Estimated GFR
* CKD Stage:

  * G1
  * G2
  * G3a
  * G3b
  * G4
  * G5
* Kidney health interpretation
* Recommended monitoring guidance

---

### 4. NEWS2 Early Warning Score

Inputs:

* Respiratory Rate
* Oxygen Saturation
* Temperature
* Systolic Blood Pressure
* Heart Rate
* Consciousness Level
* Supplemental Oxygen (Yes/No)

Outputs:

* NEWS2 Score
* Clinical Risk Category:

  * Low
  * Medium
  * High
* Color-coded alert card
* Suggested clinical response

---

### 5. CHADS-VASc Calculator

Inputs:

* Congestive Heart Failure
* Hypertension
* Age
* Diabetes
* Stroke/TIA History
* Vascular Disease
* Sex

Outputs:

* Total Score
* Stroke Risk Category
* Anticoagulation Consideration Summary

---

### 6. ASCVD/Cardiovascular Risk Estimator

Inputs:

* Age
* Gender
* Total Cholesterol
* HDL Cholesterol
* Systolic BP
* Diabetes Status
* Smoking Status

Outputs:

* Estimated 10-Year Risk
* Low / Borderline / Intermediate / High Risk
* Cardiovascular Prevention Recommendations

Use an educational approximation model suitable for demonstrations.

---

## Dashboard Features

Add a homepage dashboard containing:

### Overview Cards

* Total Calculators Available
* Last Calculation
* High-Risk Alerts
* Quick Actions

### Clinical Summary Panel

Display:

* Recent scores
* Risk trends
* Visual indicators

### Calculator Search

Allow users to search calculators instantly.

---

## UI Requirements

Design style:

* Modern healthcare SaaS
* Clean white interface
* Professional medical blue accents
* Responsive design
* Mobile friendly
* Glassmorphism cards where appropriate
* Smooth animations
* Dark mode toggle

---

## Visualization

Include:

* Gauge charts
* Progress bars
* Risk meters
* Clinical score cards
* Trend charts using sample data
* Color-coded risk indicators

Risk colors:

* Green = Low Risk
* Yellow = Moderate Risk
* Orange = Elevated Risk
* Red = High Risk

---

## Educational Section

Add a tab called:

"Clinical Reference"

For each calculator include:

* Purpose
* Clinical use case
* Interpretation guide
* Limitations
* Disclaimer

---

## Demo Data

Provide a button:
"Load Sample Patient"

Sample patient:

* Age: 55
* Female
* Height: 165 cm
* Weight: 82 kg
* BP: 145/90
* Creatinine: 1.2
* Diabetes: Yes
* Smoker: No

Automatically populate all relevant calculators.

---

## Disclaimer

Display clearly:

"This application is intended for educational and demonstration purposes only and is not a substitute for professional medical judgment."

---

Generate production-quality React code with excellent UX, reusable components, clean architecture, and realistic clinical styling.
