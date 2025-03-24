# G2++ Model Calibration and Credit Spread Simulation

**Author**:  
- Joudy Benkaddour  

## 📝 Overview

This project explores interest rate modeling using QuantLib, focusing on the calibration of the G2++ model to market cap and swaption volatilities, based on examples from Brigo & Mercurio’s reference book. Additionally, it simulates credit spread dynamics using the Black–Karasinski model and assesses calibration uncertainty under a simplified framework.

## 📊 Methodology

- **Caps and Swaptions Pricing**:  
  Replication of pricing and calibration workflows for cap and swaption instruments using the G2++ model  
- **Calibration Process**:  
  Utilization of QuantLib’s Tree and G2 engines; calibration using Levenberg-Marquardt optimization  
- **Credit Spread Simulation**:  
  Simulation of a lognormal mean-reverting process based on the Black–Karasinski model  
- **Tools Used**:  
  Python, QuantLib, NumPy, Matplotlib, Pandas  

## 📈 Key Highlights

- Built a yield curve from Bloomberg data and matched it to reference examples  
- Calibrated the G2++ model to both cap and swaption volatilities, achieving close alignment with theoretical values  
- Demonstrated the limitations of one-factor models and the strengths of two-factor models in yield curve dynamics  
- Simulated credit spreads for a pool of issuers and evaluated the accuracy and uncertainty of volatility re-estimations  

## 📂 Contents

- `Exercice_VIE_BNP_RMIR_Joudy.pdf`: Full technical report including methodology, code output, calibration results, and theoretical insights
