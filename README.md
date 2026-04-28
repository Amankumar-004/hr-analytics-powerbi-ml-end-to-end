**HR Attrition Predictive Analytics & Strategy Dashboard 🚀**

**📌 Project Overview**

This project addresses the critical business challenge of employee turnover. By leveraging the IBM HR Analytics dataset, I developed an end-to-end solution that transitions HR from reactive exit interviews to proactive AI-driven retention.

Using Machine Learning (SVM/Logistic Regression), the system assigns a Risk Score (0-100%) to every current employee. These insights are visualized in a 3-page interactive Power BI Dashboard, enabling stakeholders to identify high-risk individuals and the specific root causes (burnout, stagnation, or pay inequity) before they resign.

**🌟 Key Features**


Predictive AI Modeling: Achieved ~90% accuracy using a Support Vector Machine (SVM) classifier.

Interactive 3-Page Dashboard:

Page 1: Strategic Overview: High-level KPIs (Attrition Rate, Avg Risk Score, Total Employees).

Page 2: Root Cause Deep-Dive: Drill-down analysis into Overtime, Management Span, and Career Stagnation.

Page 3: Predictive Watchlist: An AI-powered "Watchlist" featuring neon-themed visuals to track specific high-risk Employee IDs.

Advanced DAX & Power Query: Custom measures and hierarchies (Management Span, Org Structure) for granular analysis.

Automated Risk Scoring: A Python pipeline that exports "Smart Data" directly for BI consumption.

**🛠 Tech Stack**


Data Analysis: Python (Pandas, NumPy)

Machine Learning: Scikit-Learn (Logistic Regression, SVM, Random Forest)

Visualization: Microsoft Power BI

Database: Flat CSV (IBM HR Analytics)

**📊 Dashboard Previews**


(Note: Replace these placeholders with your actual dashboard screenshots)

Page 1: Executive Overview

Page 2: Root Cause Drill-Down

Page 3: AI Predictive Watchlist






**🧪** Machine Learning Insights****

Our model identified the top four drivers of attrition:

Overtime: Employees working extra hours are 3.2x more likely to leave.

Promotion Stagnation: Risk spikes significantly after 3 years without a title change.

Manager Friction: New manager-employee relationships (< 1 year) show high "Veteran" resignation.

Income Stress: Entry-level roles earning <$3,000/month are the most volatile segment.


**🚀 Installation & Usage**


Clone the Repo:

git clone https://github.com/Amankumar-004/hr-analytics-powerbi-ml-end-to-end


Run the Analysis: Open the IBM_HR_Attrition_Analysis.ipynb in Jupyter Notebook to see the ML pipeline.

Open the Dashboard: Use Power BI Desktop to open HR_Attrition_Dashboard.pbix. Ensure the data source points to the HR clean dataset.csv.


**📈 Strategic Recommendations**


Proactive Stay Interviews: Engage the Top 10 High-Risk IDs from the Page 3 Watchlist.

Overtime Caps: Implement mandatory caps in high-burnout departments (Sales & R&D).

Leadership Handovers: Mandate a 30-day transition period for manager changes to ensure stability.


**🤝 Contributing**


Contributions are welcome! If you have suggestions for improving the model accuracy (e.g., SMOTE implementation) or the dashboard UI, feel free to open an issue or pull request.

Author: Aman K Prajapati

Connect with me: https://www.linkedin.com/in/amanprajapati004/
