# PGA Tour Data Science Project

A data science and machine learning application for analyzing and predicting PGA Tour player performance, deployed via Streamlit.



**Preface**: The data used for this model was acquired through a subscription to a PGA tour API, which has since expired, meaning this project is inactive at this time.

---

## Overview

This project was developed during my undergraduate studies to explore how machine learning can be applied to professional golf performance data. The system integrates data analysis, predictive modeling, and interactive visualization into one cohesive pipeline.

Using historical PGA Tour data, the project builds and deploys models that forecast player outcomes such as total strokes or finishing positions, and presents these insights through a Streamlit web application. The app allows users to explore tournament schedules, player fields, and performance metrics dynamically.

---

## Project Structure

| File/Folder        | Description                                                                                       |
| ------------------ | ------------------------------------------------------------------------------------------------- |
| `data/`            | Contains historical and current tournament data, including player stats and results.              |
| `model.py`         | Defines the data preprocessing and machine learning pipeline used to model player performance.    |
| `app.py`           | The main Streamlit application that integrates data, model, and visualization components.         |
| `pages/`           | Additional Streamlit pages for specific views, such as tournament insights or player comparisons. |
| `requirements.txt` | Python package dependencies required to run the app.                                              |
| `README.md`        | Documentation file (this file).                                                                   |

---

## Core Features

- Historical Data Analysis: Ingests and processes multi-year PGA Tour data from 2015–2022.
- Predictive Modeling: Uses machine learning algorithms (e.g., Random Forest, Gradient Boosting) to estimate player performance metrics.
- Interactive Visualization: Deploys insights via an easy-to-use Streamlit dashboard with tournament and player-level interactivity.
- Modular Design: Cleanly separates data, model, and application layers for flexibility and scalability.

---

## Tools & Technologies

| Category                   | Tools Used         |
| -------------------------- | ------------------ |
| Programming Language       | Python             |
| Web Interface / Deployment | Streamlit          |
| Data Processing            | Pandas, NumPy      |
| Machine Learning           | Scikit-learn       |
| Visualization              | Plotly, Matplotlib |
| Version Control            | Git, GitHub        |
| Environment Management     | pip / virtualenv   |

Streamlit enables the data science results to be shared interactively through a web interface, turning a research project into an accessible, visually engaging tool for exploring golf analytics.

---

## Getting Started

### Prerequisites

- Python 3.8+
- A virtual environment
- Dependencies installed via:
  ```bash
  pip install -r requirements.txt
  ```

### Running the Streamlit App

To launch the interactive dashboard:

```bash
streamlit run app.py
```

Then open the local URL displayed in your terminal (typically `http://localhost:8501`) to explore the app.

---

## Example Use Cases

- View the schedule of PGA Tour tournaments.
- Load player fields dynamically for a selected tournament.
- Compare actual vs. predicted leaderboard outcomes.
- Explore player-level performance metrics such as strokes gained and total strokes.

---

## Future Expansion

### 1. Data Enhancements

- Incorporate live data feeds or APIs for real-time updates.
- Expand to additional seasons or tours.
- Add contextual features such as weather, course layout, and field strength.

### 2. Model Development

- Experiment with advanced ML algorithms.
- Implement model explainability (feature importance, SHAP values).
- Add time-series forecasting for tracking player form over time.

### 3. Streamlit Improvements

- Add interactive filters and dynamic visualizations for more detailed exploration.
- Enhance caching and state management for performance.
- Deploy on Streamlit Cloud or AWS EC2 for public access.

### 4. Productionization

- Add testing, CI/CD, and version control for models (MLOps).
- Containerize with Docker for reproducibility.
- Automate data ingestion and pipeline scheduling.

---

## Academic Context

This project was created  as part of an undergraduate data science and machine learning coursework project.\
It demonstrates applied skills in:

- Data wrangling and preprocessing
- Machine learning model development and evaluation
- Interactive data visualization
- End-to-end application deployment with Streamlit

---

## Author

**Zach Burge**\
[GitHub Profile](https://github.com/ZachBurge)\
Data Scientist | Software Developer | Golf  Enthusiast

