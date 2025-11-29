# IT7009 - Network Threat Detection System
## Project Roadmap

**Course:** Artificial Intelligence (IT7009)  
**Due Date:** 15-Dec-2025  
**Project Type:** Group Project (35% of final grade)

---

## Project Overview

**Goal:** Build an intelligent threat detection pipeline using machine learning to classify network flows and identify potential cybersecurity threats.

**Dataset:** 21,185 network flow sessions with 84 features including:
- Network identifiers (IPs, ports, protocols)
- Traffic behavior (packet counts, bytes, flow rates)
- Temporal indicators (duration, inter-arrival times)
- Protocol signals (TCP flags)
- Threat labels (Benign, DoS, Exploits, Generic, etc.)

---

## Phase 1: Data Preparation ✓ (COMPLETED)

**Objective:** Load, explore, and clean the dataset

### Tasks:
- [x] Load the dataset
- [x] Display and explore data structure
- [x] Check data quality (missing values, duplicates, infinite values)
- [x] Clean the data
- [x] Document findings

**Deliverable:** `Step1_Data_Preparation.ipynb`

---

## Phase 2: Feature Development (NEXT)

**Objective:** Identify, transform, and select relevant features for modeling

### Tasks:
- [ ] Exploratory Data Analysis (EDA)
  - [ ] Statistical analysis of numerical features
  - [ ] Correlation analysis
  - [ ] Distribution plots and visualizations
  - [ ] Identify patterns between features and threat labels

- [ ] Feature Engineering
  - [ ] Handle any remaining missing values (if created during cleaning)
  - [ ] Feature scaling/normalization
  - [ ] Handle categorical variables (if needed)
  - [ ] Create new features (if beneficial)

- [ ] Feature Selection
  - [ ] Identify important features
  - [ ] Remove redundant/irrelevant features
  - [ ] Document feature selection rationale

**Deliverable:** `Step2_Feature_Development.ipynb`

**Estimated Time:** 2-3 days

---

## Phase 3: Supervised Learning - Threat Classification

**Objective:** Build and evaluate supervised ML models to classify network flows into threat categories

### Tasks:
- [ ] Data Splitting
  - [ ] Train-test split
  - [ ] Handle class imbalance (if needed)

- [ ] Model Implementation
  - [ ] Implement multiple algorithms:
    - [ ] Logistic Regression (baseline)
    - [ ] Decision Trees
    - [ ] Random Forest
    - [ ] Gradient Boosting (XGBoost/LightGBM)
    - [ ] Support Vector Machines (optional)
    - [ ] Neural Networks (optional)

- [ ] Model Training & Tuning
  - [ ] Train each model
  - [ ] Hyperparameter tuning
  - [ ] Cross-validation

- [ ] Model Evaluation
  - [ ] Calculate metrics: Accuracy, Precision, Recall, F1-Score
  - [ ] Confusion matrix
  - [ ] ROC curves (if applicable)
  - [ ] Compare model performance

**Deliverable:** `Step3_Supervised_Learning.ipynb`

**Estimated Time:** 3-4 days

---

## Phase 4: Unsupervised Learning - Anomaly Detection

**Objective:** Use unsupervised learning to identify unusual network patterns/anomalies

### Tasks:
- [ ] Algorithm Selection & Implementation
  - [ ] K-Means Clustering
  - [ ] DBSCAN
  - [ ] Isolation Forest
  - [ ] One-Class SVM (optional)
  - [ ] Autoencoders (optional)

- [ ] Anomaly Detection
  - [ ] Define anomaly criteria
  - [ ] Identify outliers
  - [ ] Analyze detected anomalies

- [ ] Evaluation
  - [ ] Compare with actual labels
  - [ ] Assess detection accuracy
  - [ ] Interpret results

**Deliverable:** `Step4_Unsupervised_Learning.ipynb`

**Estimated Time:** 2-3 days

---

## Phase 5: Feature Analysis & Interpretability

**Objective:** Understand which features are most important and how models make decisions

### Tasks:
- [ ] Feature Importance Analysis
  - [ ] Extract feature importance from models
  - [ ] SHAP values (optional but recommended)
  - [ ] Permutation importance

- [ ] Visualization
  - [ ] Feature importance plots
  - [ ] Decision boundaries (if applicable)
  - [ ] Model behavior analysis

- [ ] Interpretation
  - [ ] Explain key findings
  - [ ] Relate to cybersecurity context
  - [ ] Document insights

**Deliverable:** `Step5_Feature_Analysis.ipynb`

**Estimated Time:** 1-2 days

---

## Phase 6: Critical Evaluation & Comparison

**Objective:** Compare all approaches and provide comprehensive analysis

### Tasks:
- [ ] Model Comparison
  - [ ] Compare supervised models
  - [ ] Compare unsupervised approaches
  - [ ] Supervised vs. Unsupervised comparison

- [ ] Critical Analysis
  - [ ] Strengths and weaknesses of each approach
  - [ ] Practical applicability
  - [ ] Limitations encountered
  - [ ] Areas for improvement

- [ ] Final Recommendations
  - [ ] Best model(s) for deployment
  - [ ] Future work suggestions
  - [ ] Lessons learned

**Deliverable:** `Step6_Evaluation_Comparison.ipynb`

**Estimated Time:** 1-2 days

---

## Phase 7: Project Report

**Objective:** Write comprehensive project report

### Report Structure:
1. **Introduction**
   - [ ] Problem statement and real-world relevance
   - [ ] Project objectives
   - [ ] AI-based approach overview

2. **Data Description**
   - [ ] Dataset overview
   - [ ] Data preparation steps
   - [ ] Challenges and solutions

3. **Methodology**
   - [ ] Feature development process
   - [ ] Supervised learning approach
   - [ ] Unsupervised learning approach
   - [ ] Rationale for all choices

4. **Results**
   - [ ] Model performance metrics
   - [ ] Comparison tables and charts
   - [ ] Feature importance findings

5. **Interpretation**
   - [ ] Model behavior analysis
   - [ ] Decision-making patterns
   - [ ] Feature influence

6. **Discussion**
   - [ ] Practical implications
   - [ ] Challenges encountered
   - [ ] Limitations
   - [ ] Possible improvements

7. **Conclusion**
   - [ ] Summary of findings
   - [ ] Final reflections
   - [ ] Future work

**Deliverable:** `Project_Report.docx` (with cover page including all group member names and IDs)

**Estimated Time:** 2-3 days

---

## Phase 8: Final Submission Preparation

**Objective:** Package and submit all deliverables

### Tasks:
- [ ] Code Review & Documentation
  - [ ] Ensure all notebooks are well-commented
  - [ ] Add markdown explanations
  - [ ] Clean up code
  - [ ] Test all notebooks run without errors

- [ ] Report Finalization
  - [ ] Proofread report
  - [ ] Add cover page with all group members
  - [ ] Format properly
  - [ ] Check references

- [ ] Submission Package
  - [ ] Create ZIP folder
  - [ ] Name: `[StreamNumber]_[GroupLeaderID].zip`
  - [ ] Include all .ipynb files
  - [ ] Include report.docx
  - [ ] Verify NO RAR format

- [ ] Final Check
  - [ ] Review submission instructions
  - [ ] Ensure all requirements met
  - [ ] Submit on Moodle

**Estimated Time:** 1 day

---

## Timeline (Suggested)

| Phase | Duration | Completion Date |
|-------|----------|-----------------|
| Phase 1: Data Preparation | ✓ DONE | ✓ |
| Phase 2: Feature Development | 2-3 days | Dec 1 |
| Phase 3: Supervised Learning | 3-4 days | Dec 5 |
| Phase 4: Unsupervised Learning | 2-3 days | Dec 8 |
| Phase 5: Feature Analysis | 1-2 days | Dec 10 |
| Phase 6: Evaluation | 1-2 days | Dec 12 |
| Phase 7: Report Writing | 2-3 days | Dec 14 |
| Phase 8: Final Submission | 1 day | Dec 15 |

**Total Estimated Time:** 12-18 days

---

## Key Project Requirements Checklist

### Technical Requirements:
- [ ] Supervised classification models implemented
- [ ] Unsupervised anomaly detection implemented
- [ ] Feature analysis completed
- [ ] Evaluation metrics calculated
- [ ] Models compared and contrasted
- [ ] All code well-documented with comments

### Deliverables:
- [ ] Multiple Jupyter Notebooks (.ipynb)
- [ ] Project Report (.docx format)
- [ ] Cover page with all group member details
- [ ] ZIP folder (NOT RAR) properly named
- [ ] Submitted on Moodle

### Report Requirements:
- [ ] Problem explanation and relevance
- [ ] Project objectives stated
- [ ] Data description and preparation
- [ ] ML methods explained with rationale
- [ ] Performance evaluation and comparison
- [ ] Feature interpretation
- [ ] Discussion of implications and limitations
- [ ] Summary and reflections

---

## Important Notes

⚠️ **Submission Rules:**
- Only team leader submits
- Due: 15-Dec-2025 (11:55 PM)
- Late submission capped at 60%
- Two days after deadline = 0%
- NO RAR format allowed = 0 marks
- ZIP folder naming: `StreamNumber_GroupLeaderID`

📝 **Best Practices:**
- Comment every code section
- Explain every decision
- Use appropriate metrics
- Compare multiple approaches
- Document challenges and solutions
- Professional formatting

🎯 **Success Criteria:**
- All 4 objectives addressed
- Code runs without errors
- Models evaluated properly
- Report is comprehensive and professional
- Submission follows all guidelines

---

## Resources & References

**Python Libraries:**
- pandas, numpy - Data manipulation
- matplotlib, seaborn - Visualization
- scikit-learn - ML algorithms
- xgboost/lightgbm - Gradient boosting (optional)

**Key Concepts:**
- Classification metrics
- Feature importance
- Cross-validation
- Clustering algorithms
- Anomaly detection methods

**Tips:**
- Start early
- Test code frequently
- Document as you go
- Keep backups
- Communicate with team regularly

---

## Current Status

**Phase 1:** ✓ **COMPLETED**
- Dataset loaded and explored
- Data cleaned and prepared
- Ready for feature development

**Next Steps:**
1. Begin Phase 2: Feature Development
2. Perform EDA and visualization
3. Select and engineer features

---

*Good luck with your project! Follow this roadmap step by step for successful completion.*
