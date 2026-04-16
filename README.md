# ldlt-synthetic-digital-twin
Liver Transplant Synthetic Data Generation
# LDLT Synthetic Digital Twin

A clinically grounded synthetic data generator for Living Donor Liver Transplantation (LDLT), built using literature-calibrated distributions and causal survival modeling.

## 🚀 Features

- Multi-stage clinical simulation (donor → surgery → outcomes)
- Literature-calibrated distributions
- Survival (Kaplan–Meier) modeling
- Donor-recipient matching engine
- Constraint-based clinical validation
- FastAPI backend + Streamlit UI
- 50K–1M scalable dataset generation

---

## 🧬 Clinical Model

This simulator models:

- Donor characteristics (age, BMI, blood group)
- Recipient severity (MELD score, diagnosis)
- Surgical complexity (blood loss, ischemia time)
- Outcomes (mortality, ICU stay, survival time)

---

## 📊 Output

- Synthetic clinical datasets (CSV / Parquet)
- Survival curves
- Correlation structure analysis
- Validation reports

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
