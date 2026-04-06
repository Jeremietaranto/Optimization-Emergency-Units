# Optimization of Emergency Department Operations

## Overview

This project focuses on optimizing resource allocation in hospital emergency departments using mathematical modeling and data-driven simulation.

The goal is to minimize patient waiting costs while efficiently allocating physicians under operational constraints. The model captures real-world dynamics such as patient arrivals, treatment durations, and capacity limitations.

This project allowed us to improve our applied skills in optimization, stochastic modeling, and healthcare analytics.

---

## Key Contributions

* Designed a mathematical optimization model for emergency department operations
* Modeled patient flow using queue dynamics and time-dependent arrivals
* Incorporated cost structures that penalize long waiting times
* Implemented simulations using real-world inspired datasets
* Explored trade-offs between staffing levels and patient outcomes

---

## Problem Statement

Emergency departments face two competing challenges:

* Minimizing patient waiting time and associated risks
* Operating under limited medical staff and resources

This project formulates the problem as a constrained optimization model that balances both objectives.

---

## Model Summary

The model minimizes total system cost, including:

* Waiting cost, increasing with time and severity
* Staffing cost, based on physician allocation

### Decision Variables

* Patients treated per time, condition, and waiting duration
* Number of physicians allocated per time period

### Constraints

* Patient queue evolution over time
* Incoming patient arrivals
* Treatment capacity limitations
* Maximum available physicians

This leads to a dynamic, multi-period optimization problem.

---

## Data

The project uses multiple datasets to simulate emergency department activity:

* Patient arrival rates
* Treatment times
* Disease categories and prevalence
* Historical hospital data (USA-based)

---

## Implementation

Main components:

* `ER_model_1.ipynb`: Core optimization model
* `clean_us_hospital.ipynb`: Data preprocessing
* `creation_ED_arrivals_2.ipynb`: Synthetic arrival generation
* CSV datasets for simulation inputs

Technologies used:

* Python (NumPy, Pandas)
* Jupyter Notebook
* Optimization modeling techniques

---

## Results & Insights

* Identified optimal staffing strategies under varying demand levels
* Quantified the cost impact of delayed treatment
* Demonstrated how dynamic allocation improves system efficiency

---

## Why This Project Matters

This project reflects real-world operational challenges in healthcare systems and shows the ability to:

* Translate complex systems into mathematical models
* Work with imperfect, real-world data
* Build decision-support tools with tangible impact

---

## Authors

**Jérémie Taranto**
Originally developed under another student account; this repository consolidates and continues the work.

****Elie Juvenspan**


