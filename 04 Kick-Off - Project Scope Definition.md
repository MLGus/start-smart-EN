# 📌 Project Scope Definition Template

## 📍 1. SMART Scope
> **Objective:** Define a clear and measurable scope.

- **Specific:** Develop a web system for scheduling medical appointments.
- **Measurable:** The system must support 10,000 users and process appointments in less than 2 seconds.
- **Achievable:** Use a scalable web technology with an optimized database.
- **Relevant:** Aligned with the company's strategy to digitize processes.
- **Time-bound:** Deliver the MVP within 6 months.

---
## 📍 2. MOSCOW Prioritization
> **Objective:** Define what is essential and what can be postponed.

- **Must-have (Essential)** ✅
  - Patient and doctor registration.
  - Appointment booking and cancellation.
  - Email notifications.

- **Should-have (Important but not essential)** 🔜
  - Chat between patients and doctors.
  - Appointment history reports.

- **Could-have (Nice to have, but optional)** 🤔
  - Multi-language support.
  - Dark mode for the UI.

- **Won’t-have (Out of scope)** ❌
  - Health insurance provider integration in this phase.

---
## 📍 3. User Stories + Acceptance Criteria (INVEST)
> **Objective:** Define user requirements in detail.

📌 **User Story:**  
*"As a patient, I want to schedule appointments online to avoid waiting in line and save time."*

✅ **Acceptance Criteria:**  
- The patient can select available doctors by date and time.  
- The system sends confirmation via email and SMS.  
- The patient can view their appointment history.  

---
## 📍 4. Responsibility Assignment Matrix (RACI)
> **Objective:** Clearly define project responsibilities.

| Activity                      | R (Responsible) | A (Accountable) | C (Consulted) | I (Informed) |
|--------------------------------|----------------|----------------|--------------|-------------|
| Frontend Development (UI/UX)  | Dev Team       | PM             | UX Designer  | Client      |
| Backend Development (APIs)    | Dev Team       | Tech Lead      | Architects   | Client      |
| Testing and QA                | QA Team        | PM             | Dev Team     | Client      |

---
## 📍 5. Scope Inclusions and Exclusions
> **Objective:** Clearly specify what is and isn’t included in the project.

✅ **Inclusions:**  
- Development of the appointment booking system.  
- Secure login implementation (OAuth).  
- Automatic notifications.  

❌ **Exclusions:**  
- Integration with legacy systems.  
- Online payments in this version.  

---
## 📍 6. Gelkwin Structure (Generate, Specify, Limit + Keep, Win, Improve, Negotiate)
> **Objective:** Structure the scope considering improvements and negotiations.

### **📌 GEL (Generate, Specify, Limit)**
- **Generate:** The system needs to allow fast and secure appointment scheduling.  
- **Specify:** The appointment will be validated via a token and stored in the database.  
- **Limit:** The system will not support multiple clinics initially.  

### **📌 KWIN (Keep, Win, Improve, Negotiate)**
- **Keep:** Maintain the login structure already used in other company systems.  
- **Win:** Reduce appointment cancellations by 30% through notifications.  
- **Improve:** Enhance the user experience for easier mobile appointment scheduling.  
- **Negotiate:** Health plan integration may be included in a future phase.  

---
## 📍 7. Consolidated Example (Integrating the 7 Techniques)
### 🔷 Complete Scope Definition for the "Medical Appointment System" Project
> **Objective:** Create a scalable system for medical appointment scheduling.

### 🎯 **SMART Scope**
- **Objective:** Create a web system for scheduling medical appointments.
- **Metrics:** 10,000 users, response time < 2s.
- **Relevance:** Digital transformation of processes.
- **Time-bound:** MVP delivery in 6 months.

### 📊 **MOSCOW Prioritization**
- **Must-have:** Login, scheduling, notifications.
- **Should-have:** Chat, reports.
- **Could-have:** Dark mode, multi-language support.
- **Won’t-have:** Insurance provider integration in this phase.

### 👤 **User Story + Acceptance Criteria**
- "As a patient, I want to schedule appointments online to avoid waiting in line and save time."
- **Criteria:** Select doctors, receive notifications, access appointment history.

### 🏗 **RACI Matrix**
| Activity                 | R | A | C | I |
|--------------------------|---|---|---|---|
| Frontend (UI/UX)        | Dev Team | PM | UX | Client |
| Backend (APIs)          | Dev Team | Tech Lead | Architects | Client |
| Testing (QA)            | QA Team | PM | Dev Team | Client |

### ⚖ **Scope Inclusions and Exclusions**
✅ **Inclusions:** Appointment scheduling, notifications, secure login.  
❌ **Exclusions:** Online payments, insurance provider integration.  

### 🔄 **Gelkwin Structure**
**GEL:**  
- Generate: Develop an online appointment scheduling system.  
- Specify: Booking and cancellation functionality.  
- Limit: No integration with other hospitals initially.  

**KWIN:**  
- **Keep:** Google OAuth login.  
- **Win:** Reduce appointment cancellations by 30%.  
- **Improve:** Better mobile UX.  
- **Negotiate:** Future health insurance integration.  

---
### 🚀 **Conclusion**
This template provides a **complete model** for defining project scope using multiple complementary techniques. It can be adapted as needed, combining the clarity of **SMART**, the prioritization of **MOSCOW**, the structuring of **INVEST**, the organization of **RACI**, the transparency of **Inclusions/Exclusions**, and the strategic flexibility of **Gelkwin**.
