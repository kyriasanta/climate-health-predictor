# Climate-Health Risk Predictor

ML-powered tool predicting heat-related ER visits using weather data.

## Project Overview
Predicts emergency room visits based on temperature patterns to inform public health interventions during heat events.

## Key Findings
- **Atlanta 2023**: 196 hot days (>25°C) requiring health alerts
- **ML Accuracy**: 56% variance explained, ±6 ER visits/day prediction error
- **Critical Threshold**: 25°C identified for heat alert activation

##  Technologies
- **Python**: Pandas, NumPy, Scikit-learn, XGBoost
- **ML Models**: Random Forest, XGBoost, LightGBM
- **Data Sources**: NOAA GSOD (real), Synthetic (for prototyping)
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Deployment**: Streamlit dashboard

## 📁 Project Structure


##  Quick Start
1. **Clone repo**: `git clone https://github.com/kyriasanta/climate-health-predictor.git`
2. **Install dependencies**: `pip install -r requirements.txt`
3. **Run dashboard**: `streamlit run app/dashboard.py`
4. **Explore notebooks**: Open `notebooks/` in Jupyter

##  Results Summary
| Dataset | Avg Temp | Hot Days | Model R² | MAE |
|---------|----------|----------|----------|-----|
| Synthetic | 15.1°C | 649 | 0.758 | 4.99 |
| Real Atlanta | 18.5°C | 196 | 0.560 | 6.00 |

##  Public Health Impact
- **Heat Alert Threshold**: 25°C
- **Annual Hot Days**: 196 days requiring intervention
- **Healthcare Planning**: ±6 visit/day fluctuations during heat

## 🔗 Links
- **GitHub Repo**: https://github.com/kyriasanta/climate-health-predictor.git
- **Data Source**: [NOAA GSOD](https://www.ncei.noaa.gov/data/global-summary-of-the-day/)