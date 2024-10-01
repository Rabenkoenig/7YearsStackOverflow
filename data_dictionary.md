### Data Dictionary

---

### **Question 1: Developer Satisfaction and Stack Overflow Engagement**

#### **Variables:**
- **`JobSat`** (QID336):
  - **Question**: "How satisfied are you in your current professional developer role?"
  - **Type**: MC (Multiple Choice)
  - **Selector**: NPS (Net Promoter Score)
  - **Values**: Responses reflecting the satisfaction level of the developer in their current role (e.g., Highly satisfied, Somewhat satisfied, Dissatisfied).
  
- **`SOVisitFreq`** (QID100):
  - **Question**: "How frequently would you say you visit Stack Overflow?"
  - **Type**: MC (Multiple Choice)
  - **Selector**: SAVR (Single Answer Value Required)
  - **Values**: Frequency of visits to Stack Overflow (e.g., Daily, Weekly, Monthly).

- **`SOAccount`** (QID101):
  - **Question**: "Do you have a Stack Overflow account?"
  - **Type**: MC (Multiple Choice)
  - **Selector**: SAVR (Single Answer Value Required)
  - **Values**: Whether the respondent has a Stack Overflow account (e.g., Yes, No).

- **`SOPartFreq`** (QID102):
  - **Question**: "How frequently would you say you participate in Q&A on Stack Overflow? By participate, we mean ask, answer, vote for, or comment on questions."
  - **Type**: MC (Multiple Choice)
  - **Selector**: SAVR (Single Answer Value Required)
  - **Values**: Frequency of participation in Stack Overflow Q&A activities (e.g., Frequently, Occasionally, Rarely).

---

### **Question 2: AI Tool Usage and Perceptions**

#### **Variables:**
- **`AISelect`** (QID314):
  - **Question**: "Do you currently use AI tools in your development process?"
  - **Type**: MC (Multiple Choice)
  - **Selector**: SAVR (Single Answer Value Required)
  - **Values**: Whether the respondent uses AI tools in their development process (e.g., Yes, No, but I plan to, No, and I don't plan to).

- **`AIAcc`** (QID316):
  - **Question**: "How much do you trust the accuracy of the output from AI tools as part of your development workflow?"
  - **Type**: MC (Multiple Choice)
  - **Selector**: SAVR (Single Answer Value Required)
  - **Values**: Level of trust in AI tool output accuracy (e.g., Highly trust, Somewhat trust, Neither trust nor distrust, Somewhat distrust, Highly distrust).

- **`AIChallenges`** (QID346):
  - **Question**: "What are the challenges to your company/whole team using AI code assistants or GenAI tools? Select all that apply."
  - **Type**: MC (Multiple Choice)
  - **Selector**: MAVR (Multiple Answer Value Required)
  - **Values**: Challenges related to AI tool adoption (e.g., Data privacy concerns, Lack of training data, High cost, Limited trust).

- **`AIThreat`** (QID338):
  - **Question**: "Do you believe AI is a threat to your current job?"
  - **Type**: MC (Multiple Choice)
  - **Selector**: SAVR (Single Answer Value Required)
  - **Values**: Perception of AI as a job threat (e.g., Yes, No, I'm not sure).

---

### **Question 3: Professional Coding Experience and Compensation**

#### **Variables:**
- **`YearsCodePro`** (QID34):
  - **Question**: "NOT including education, how many years have you coded professionally (as a part of your work)?"
  - **Type**: MC (Multiple Choice)
  - **Selector**: DL (Drop-Down List)
  - **Values**: Number of years of professional coding experience (e.g., Less than 1 year, 1-2 years, 3-5 years, 6-10 years, 11+ years).

- **`Country`** (QID6):
  - **Question**: "Where do you live?"
  - **Type**: MC (Multiple Choice)
  - **Selector**: DL (Drop-Down List)
  - **Values**: Respondent's country of residence (e.g., United States, Canada, India, Germany, etc.).

- **`CompTotal`** (QID51):
  - **Question**: "What is your current total annual compensation (salary, bonuses, and perks, before taxes and deductions)?"
  - **Type**: TE (Text Entry)
  - **Selector**: SL (Single Line)
  - **Values**: Numeric entry representing annual compensation in the respondent’s local currency.

---
