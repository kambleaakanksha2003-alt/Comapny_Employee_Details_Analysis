# Comapny_Employee_Details_Analysis

<img src="https://beyondtheory.co.uk/storage/uploads/2016/08/Beyond-Theory-Data-Analysis-Landing-Page-graphic.png" width=800>

**By Akanksha Kamble**
## 🚀 Overview
This project involves an Exploratory Data Analysis (EDA) of employee data to uncover patterns related to demographics, job satisfaction, attrition, education level, and other HR factors. The dataset is analyzed using Python libraries to generate visual insights that help understand workforce trends and aid in decision-making for HR policies.

---

## 🎯 Project Goal

To analyze employee data in order to:
- Identify trends in age, education, and experience.
- Understand the factors affecting employee retention and attrition.
- Visualize patterns in benching, payment tiers, gender distribution, and domain expertise.
- Derive insights to help improve HR decision-making.

---

## 🛠️ Tools & Technologies Used

- **Python**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  
- **Plotly Express**


---

## 🔍 Features & Analysis

- ✅ Null Value Handling  
- 📈 Age Distribution & Average Age Analysis  
- 🧠 Education Level & Stream Analysis  
- 🎓 City-wise & Year-wise Employee Joining Trends  
- 💸 Payment Tier Distributions  
- 👨‍💼 Gender & Bench Status Relationships  
- ⌛ Experience in Current Domain vs. Attrition  
- 📉 Leave or Not – with respect to education and experience

---

## Employee Distribution

<img width="1108" height="650" alt="Age Distribution" src="https://github.com/user-attachments/assets/54ef02a9-e86e-4308-a27f-5cfd04b02519" />

## Experience Domain

<img width="1095" height="686" alt="Experience Domain" src="https://github.com/user-attachments/assets/25fa0c86-6ca7-4648-aced-2aef76e56864" />



## 📊 Key Insights (based on expected chart outputs)

1. **Age Distribution**:
   - Most employees fall within a specific age range.
   - Outliers can be observed via boxplot, indicating very young or older employees.

2. **Education Level**:
   - One or two education levels dominate the employee base.
   - Pie chart clearly shows proportions of streams.

3. **Gender vs EverBenched**:
   - Visual difference between male and female employees benched.
   - May highlight if one gender is disproportionately affected.

4. **Payment Tiers**:
   - Tier 2 or Tier 3 might be more populated.
   - Useful for budgeting and compensation strategies.

5. **Experience in Current Domain**:
   - Employees with zero domain experience show higher attrition.
   - Indicates need for better onboarding or training programs.

6. **Joining Year & City**:
   - Specific years or cities may have higher onboarding trends.
   - Can reflect company growth in certain regions.

---

## ✅ Recommendations

1. **Retention Programs**:
   - Focus on employees with 0 domain experience; they show higher attrition rates.
   - Mentorship or early engagement strategies recommended.

2. **Balanced Hiring Across Education Streams**:
   - If one education stream dominates, diversify hiring to improve team versatility.

3. **Payment Tier Assessment**:
   - Review compensation models if Tier 1 employees are leaving more often.

4. **City-specific Strategies**:
   - Cities with lower hiring trends might benefit from localized recruitment campaigns.

5. **Gender Inclusion**:
   - Address any imbalance in benching or project assignment between genders.

6. **Young Talent Support**:
   - If younger employees show more churn, provide growth and development opportunities.

---

## 📂 Dataset
All analysis was based on the following dataset: 
- File name: `Employee.csv`
- Fields: `Age`, `Gender`, `Education`, `City`, `PaymentTier`, `JoiningYear`, `ExperienceInCurrentDomain`, `EverBenched`, `LeaveOrNot`

---













