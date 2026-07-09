# Andrew Simons

MIT — Computer Science, Economics, and Data Science (6-14) + Mathematics (18)

I'm interested in machine learning, quantitative finance, optimization, and building software that solves practical problems. Most of my projects are either research-oriented or full-stack applications with a focus on real-world use.

## Featured Projects

### Botswana Climate Early Warning System
**Python · PyTorch · Google Earth Engine · XGBoost · ConvLSTM · FastAPI**

Developing a spatiotemporal machine learning pipeline for drought and flood early warning in Botswana. The system ingests 20+ years of satellite and climate reanalysis data to generate per-pixel drought and flood risk forecasts using deep learning and interpretable machine learning techniques.

Designed an end-to-end pipeline for large-scale geospatial data ingestion, preprocessing, feature engineering, and model training, progressing from statistical baselines to XGBoost, LSTM, and ConvLSTM architectures. The project is intended to power a FastAPI backend that serves risk predictions and SHAP explanations for citizens, government agencies, and NGOs.

**Repository:** https://github.com/andrew-simons/botswana-drought-flood

### QuestLog

**React · Node.js · Express · MongoDB · WebSockets · OAuth**

A full-stack multiplayer productivity platform that turns habit formation into a persistent game. Users complete quests, earn experience and in-game currency, customize shared rooms, and interact with friends in real time.

The backend uses a hybrid architecture: REST APIs manage persistent state (users, inventory, quests, rooms), while WebSockets synchronize real-time interactions such as movement, presence, and player actions. The system was designed with clear ownership rules to prevent state inconsistencies across concurrent users.

**Repository:** https://github.com/andrew-simons/QuestLog
**Live Demo:** https://questlog-hocl.onrender.com/
**Preview:** 
<p align="center">
  <img src="https://github.com/user-attachments/assets/8c96df9b-53d5-423f-a5aa-7a53244a8aaa" width="32%" />
  <img src="https://github.com/user-attachments/assets/63d77930-325d-40a2-bc43-dfe33a2675fd" width="32%" />
  <img src="https://github.com/user-attachments/assets/7952bc3e-e3b9-4e4d-8a92-647bbce510f9" width="32%" />
</p>

*MIT WebLab Final Project*

---

### Machine-Learned Volatility & Time-Varying Monte Carlo Pricing

**PyTorch · Python · NumPy · Pandas**

Built a neural network to predict 30-day forward realized volatility from historical market data and rolling volatility features. The model consistently outperformed a rolling-window baseline on out-of-sample data.

Integrated these forecasts into a Monte Carlo pricing engine that updates volatility throughout each simulated path, producing more realistic option pricing estimates and confidence intervals.

**Repository:** https://github.com/andrew-simons/montecarlo-ml

---

### Children's Music Brigade App

**Flutter · Firebase · Cloud Functions**

Cross-platform volunteer management application built for a nonprofit coordinating performances at hospitals and nursing homes. The platform handles event scheduling, attendance tracking, volunteer management, notifications, and automated service-hour reporting.

**Repository:** https://github.com/andrew-simons/Mobile_App_for_CMB_Inc./tree/main
**Demo:** https://www.youtube.com/watch?v=aPLsThLf-3E

---

### Market Sentiment ML Pipeline

**Python · LSTM · Random Forest · Logistic Regression**

Developed an end-to-end machine learning pipeline that predicts short-term market sentiment from more than 50,000 social media posts. The project includes data preprocessing, feature engineering, model training, comparison across multiple architectures, and evaluation.

---

### More Projects

I'm currently working on machine learning research, quantitative finance, climate modeling, and applied systems projects. I'll continue adding them here as they're completed.

If you're interested in AI, quantitative finance, systems, or machine learning, feel free to reach out.
