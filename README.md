# Infosys Springboard Virtual Internship 7.0
## Individual Contribution & Work Summary Report

---

### **1. Executive Summary**
* **Project Title:** Agentic AI for Maritime Freight Pricing and Route Optimization (**FreightAI**)
* **Domain:** Artificial Intelligence & Maritime Logistics
* **Batch Details:** Batch 7.0 / Group 1
* **Duration:** July 2026 – September 2026 (12 Weeks / 3 Months)
* **Primary Tech Stack:** React 19, Django REST Framework, Python 3.14, Scikit-Learn, Pytest

---

### **2. Individual Role & Core Contributions**

As a key contributor to the **FreightAI** platform, my core responsibilities spanned across **Frontend Development (UI/UX & Authentication)**, **Architectural Implementation of Milestones 1 & 2**, and **Pricing Engine Integration (Formula-Based & Machine Learning-Based)**. 

Below is the detailed breakdown of my contributions across the project lifecycle:

---

#### **A. UI/UX, Design System & Theme Development**
* **Theme & UI Layout:** Designed and implemented responsive, glassmorphism-inspired UI layouts and component libraries using React 19.
* **Multi-Role Portals:** Built interactive interface layouts tailored for multiple roles within the freight ecosystem (Shipper, Agent, Customs Officer, and Administrator Command Centers).
* **Data Visualization & Dashboards:** Created interactive route visualizers, cost distribution charts, status trackers, and live action queues to make complex maritime logistics metrics easily actionable.

---

#### **B. Authentication & Security Workflow**
* **Login & Signup Auth:** Implemented end-to-end user signup and login authentication flows.
* **JWT Stateless Authentication:** Integrated JWT-based secure authentication workflows with password hashing on the backend.
* **Role-Based Access Control (RBAC):** Configured route guard middleware on the client-side and role-based access checks to restrict platform permissions according to assigned user roles.

---

#### **C. Milestone 1 (M1): Foundational Routing & Formula-Based Pricing**
* **Core Logistics Entities:** Contributed to setting up key freight entities including `Shipment`, `Route`, `Cargo`, and `BaseRate`.
* **Formula-Based Pricing Calculator:** Engineered deterministic rule-based rate calculation engines incorporating:
  * Base ocean freight rates
  * Bunker Adjustment Factors (BAF) fuel surcharges
  * Peak Season Surcharges (PSS)
* **Chargeable Weight Resolver:** Built logic for dimensional/volumetric weight conversion against actual gross weight based on maritime standards ($1\text{ CBM} = 167\text{ kg}$).

---

#### **D. Milestone 2 (M2): AI/ML Freight Price Prediction**
* **Machine Learning Pricing Integration:** Integrated a Scikit-Learn Gradient Boosted Regression model ($R^2 = 0.874$) into the pricing pipeline alongside the formula-based engine.
* **Side-by-Side Pricing Comparison:** Built the interactive UI/UX components for side-by-side comparison of **Deterministic Rule-Based Rates vs. ML-Predicted Spot Rates**.
* **Explainable AI (XAI) UI:** Added visual explainability features (Gini feature importance indicators) so users can analyze key pricing drivers such as chargeable weight, route distance, bunker index, and seasonality.

---

### **3. Key Deliverables Summary**

| Area | Deliverables Handled |
| :--- | :--- |
| **Authentication & Access** | Login, Signup, JWT token handling, and RBAC route guards. |
| **UI/UX & Theme** | Dark glassmorphism theme, multi-role dashboard layouts, responsive design. |
| **Milestone 1 (M1)** | Seaport route setup, chargeable weight logic, formula-based rate engine (BAF/surcharges). |
| **Milestone 2 (M2)** | ML price prediction integration, Rule vs. ML comparison card UI, pricing explainability view. |

---

### **4. Conclusion**

Through my direct contributions to UI design, security, and both deterministic and AI-driven pricing engines (M1 & M2), I helped transition FreightAI into an end-to-end, sub-3-second automated quotation platform. All modules delivered met strict testing and quality standards as part of our successful virtual internship completion with Infosys Springboard.
