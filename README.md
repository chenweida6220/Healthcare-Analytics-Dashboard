# Healthcare Analytics Dashboard
This project analyzes a healthcare center’s financial performance by visualizing total and average costs (e.g., treatment, medication, room charges, insurance) across key dimensions in a multi-table dataset. It highlights billing trends by city/state, medical department, diagnosis/service type, and procedure, providing clear insights into cost drivers and operational efficiency for data-informed decision-making.

# Dataset
## Healthcare Provider Dataset
* **Author:** Data with Decision
* **Source:** [YouTube Link](https://www.youtube.com/watch?v=hm4Iq2Mm2pQ&pp=ygUfbXMgcG93ZXJiaSBoZWFsdGhjYXJlIGRhc2hib2FyZA%3D%3D)
* **About:** This synthetic multi-table dataset models the operations of a healthcare center, containing relational information across patients, providers, visits, diagnoses, procedures, insurance, and departments. It is designed for financial and operational analysis, including fields such as visit dates, treatment costs, medication costs, insurance coverage, room charges, patient satisfaction, and provider details. The dataset enables analysis of billing trends, cost drivers, department performance, and provider efficiency in a realistic healthcare management context.

# Objectives
| # | Completion | Objective | Description |
|---|---|---|---| 
| 1 | [x] | Assess Overall Financial Health | Calculate and visualize key financial metrics such as total billing, average treatment cost, medication cost, room charges, and insurance coverage. |
| 2 | [x] | Analyze Cost and Revenue Distribution | Identify how billing amounts are distributed across geographic regions, departments, diagnoses, procedures, and service types. |
| 3 | [x] | Evaluate Provider and Department Performance | Measure efficiency and financial contribution by department and provider type using metrics like total billing per department and cost per procedure. |
| 4 | [x] | Analyze Patient Demographics and Financial Impact | Explore how patient age, gender, insurance type, and race relate to treatment costs and billing outcomes. |
| 5 | [x] | Create an Interactive and User-Friendly Dashboard | Develop a multi-page Power BI dashboard with clear visualizations, filters, and drill-through capabilities for ease of use. |

# Dashboard
<table>
  <tr>
    <th>Light Mode</th>
    <th>Light Mode (With Filter)</th>
  </tr>
  <tr>
    <td>
      <img src="/images/Healthcare%20Provider%20Dashboard_light%20mode.png" width="400"/>
    </td>
    <td>
      <img src="/images/Healthcare%20Provider%20Dashboard_light%20mode%20(filter).png" width="400"/>
    </td>
  </tr>
  <tr>
    <th>Dark Mode</th>
    <th>Dark Mode (With Filter)</th>
  </tr>
  <tr>
    <td>
      <img src="/images/Healthcare%20Provider%20Dashboard_dark%20mode.png" width="400"/>
    </td>
    <td>
      <img src="/images/Healthcare%20Provider%20Dashboard_dark%20mode%20(filter).png" width="400"/>
    </td>
  </tr>
</table>
<!-- ![Healthcare Analytics Dashboard - Light Mode](/images/Healthcare%20Provider%20Dashboard_light%20mode.png)
![Healthcare Analytics Dashboard - Light Mode (with filter)](/images/Healthcare%20Provider%20Dashboard_light%20mode%20(filter).png)
![Healthcare Analytics Dashboard - Dark Mode](/images/Healthcare%20Provider%20Dashboard_dark%20mode.png)
![Healthcare Analytics Dashboard - Dark Mode (with filter)](/images/Healthcare%20Provider%20Dashboard_dark%20mode%20(filter).png) -->

# Key Findings
### 1. Financial Overview
- Total Billing Amount is £3 million, with an average of £35,120 per visit.
- Treatment costs account for the largest share of total costs (£3M), nearly equal to total billing, indicating high procedural expenses.
- Insurance coverage is significant (£2M), but out-of-pocket expenses remain notable at £1M.
- Medication costs are relatively low (£546K), while room charges are minimal (£180K).
### 2. Geographic Analysis
- OScotland leads in billing, driven by Edinburgh, which has the highest total billing among cities.
- England, Northern Ireland, and Wales follow in billing contribution, with major cities like Birmingham, Sheffield, and Leeds showing substantial activity.
### 3. Diagnosis & Service Breakdown
- Hypertension and Appendicitis generate the highest billing, primarily through outpatient services (53.92% and 56.13%).
- Emergency services contribute significantly across diagnoses, especially for Asthma and Fracture.
- Inpatient care is consistently the smallest contributor across all diagnoses.
### 4. Procedure Costs
- X-Ray is the highest-billing procedure (£1.05M, 31%), followed by CT Scan (£805K, 24%) and MRI Scan (£600K, 18%).
- Imaging services (X-Ray, CT, MRI, Ultrasound) collectively account for 87% of total procedural billing.
### 5. Department Performance
- Cardiology leads in billing contribution (25.24%), closely followed by Orthopedics (24.23%) and General Surgery (23.34%).
- Neurology and Pediatrics contribute smaller but notable shares (14.25% and 12.95%).

# Technologies
* Excel
* Microsoft Power BI

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](/raw%20data/) within this repo.    
