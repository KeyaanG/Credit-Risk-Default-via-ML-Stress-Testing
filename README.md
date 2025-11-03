# Credit-Risk-Default-via-ML-Stress-Testing
Calculate the risk taken up by a lender while giving out a loan given specific conditions. Utilize ML via Linear Regression and more. 

Below is the formal proposal given to me:

Project F1: Credit Risk Modeling and Stress Testing

Project Overview: Develop statistical and machine-learning models to quantify credit risk and assess portfolio resilience under adverse scenarios.  We will build predictive models (e.g. logistic regression, tree-based learners) for borrower default using historical loan data, and then perform stress testing by simulating macroeconomic shocks.  Stress testing is a forward-looking evaluation of extreme scenarios (e.g. recession, market shocks) to check capital adequacy ￼ ￼.  Our models will estimate key risk parameters like Probability of Default (PD), Exposure at Default (EAD), and Loss Given Default (LGD) to calculate expected loss (EL = PD×EAD×LGD) ￼.  In short, the project integrates data-driven credit analysis with regulatory-style scenario testing to ensure a loan portfolio can withstand potential crises.

Objectives:
	•	Build a credit-scoring model to predict default probability on loans.
	•	Construct stress scenarios (macro indicators, downturn effects) and translate them into stressed PD/EAD/LGD estimates ￼.
	•	Validate model performance and quantify impacts on portfolio loss and capital.
	•	Document assumptions, methodology, and include error analyses and scenario results.

Technical Stack: Python, R, or similar for data science; key libraries like scikit-learn, XGBoost, PyTorch/TensorFlow for models.  Use pandas/SQL for data prep, and libraries such as statsmodels or SciPy for statistical analysis.  (For example, existing credit-risk projects use Python with scikit-learn and XGBoost for model building ￼.)  Tools for visualization (Matplotlib/Seaborn) and report generation (e.g. Jupyter notebooks, Streamlit) will be used.  Version control (Git) and cloud resources (AWS/GCP) may be employed.

Project Timeline (12 weeks):
	1.	Weeks 1–2: Data collection/cleaning (loan performance, borrower features, macro data).
	2.	Weeks 3–4: Exploratory analysis; feature engineering (credit scores, financial ratios).
	3.	Weeks 5–6: Build initial credit scoring model (logistic regression, decision trees); baseline metrics.
	4.	Weeks 7–8: Develop stress testing framework: define macro scenarios; map to stressed PD/LGD parameters (through-the-cycle to point-in-time) ￼.
	5.	Weeks 9–10: Train advanced models (e.g. Random Forest/XGBoost) and incorporate Monte Carlo simulation or dynamic portfolios.
	6.	Weeks 11–12: Validate models under stress scenarios, finalize analyses; prepare final report and presentation.

Deliverables:
	•	Trained credit risk models (code and saved artifacts).
	•	Stress-test scenario tool (scripts or a simple app) that applies scenarios to portfolio.
	•	Analysis report summarizing methods, results, model validation, and regulatory implications.
	•	Documentation of data pipeline and modeling assumptions.
	•	Presentation for stakeholders summarizing findings.

Learning Outcomes:
	•	Mastery of credit risk concepts (PD, LGD, EAD) and regulatory context (Basel/IFRS-9 provisions).
	•	Hands-on experience in predictive modeling for finance (training/classifying borrower default).
	•	Skills in scenario analysis and stress-testing frameworks ￼.
	•	Improved data handling, feature engineering, and model validation techniques for financial data.

Career Relevance:
	•	Risk Management Expertise: Building credit risk models and stress tests gives interns skills highly sought by banks, regulators, and consulting firms.  Demand for risk analysts is strong – banks plan hiring across risk teams driven by new technologies and regulations ￼.  Understanding risk metrics and models (EL, capital ratios) is directly applicable to careers in credit analysis and risk management.
	•	Quantitative Skills: Experience with statistical and ML models enhances quantitative finance credentials.  Many fintech and quant roles (e.g. credit quant, risk modeler) value programming and analytical proficiency ￼ ￼.
	•	Regulatory Familiarity: Learning how to simulate macroeconomic shocks and assess capital needs prepares interns for roles in regulatory compliance (Basel/CECL/IFRS9) and in firms’ stress testing functions.
	•	AI/Tech Readiness: Using Python/ML tools for finance projects signals tech-savviness.  Coupled with domain knowledge, this makes an intern more employable in areas like financial data science and digital banking.
