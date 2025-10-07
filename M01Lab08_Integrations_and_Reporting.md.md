# LAB[PO-101]_M01Lab08_Integrations_and_Reporting

**Module:** 01 — From Sales to Project Operations  
**Lab Title:** Integrations & Reporting  
**Estimated time:** 45–75 minutes  

## Lab overview
In this lab, you will explore how Dynamics 365 Project Operations integrates with **Power BI**, **Dataverse reporting**, and **Excel** for advanced analytics. You will connect project financial data to Power BI dashboards, export project data to Excel, and build simple visualizations.

## Learning objectives
- Connect Project Operations to **Power BI dashboards**.  
- Explore **standard reports** (Profitability, Utilization).  
- Export and analyze project data in **Excel**.  
- Understand **Dataverse integration** for custom reporting.  

## Prerequisites
- Completed **M01 Lab 07 (Project Actuals & Financial Analysis)**.  
- Security role: **Project Operations Project Manager** or **Executive**.  
- Access to **Power BI service or desktop**.  

## Scenario
The leadership team at **TopRock Consulting** wants consolidated reporting across multiple projects. You will use built-in dashboards and Power BI to provide insights for the **Contoso ERP Implementation** project.

---

## Exercise 1: Explore Built-in Reports

1. Navigate to **Project Operations → Analytics → Reports**.  
2. Open **Project Profitability**.  
3. Filter by **Contoso ERP Implementation**.  
4. Review metrics:  
   - Total Revenue, Total Cost, Margin %  
   - Invoiced vs. Non-invoiced actuals  

**Validation:** Data matches results from Lab 7.  

---

## Exercise 2: Power BI Integration

### Task 1: Connect Power BI to Project Operations
1. Open **Power BI Desktop**.  
2. Select **Get Data → Dataverse**.  
3. Enter the environment URL.  
4. Authenticate with your D365 credentials.  

### Task 2: Import project tables
1. Select the following tables:  
   - **msdyn_projects** (Projects)  
   - **msdyn_projectcontracts** (Contracts)  
   - **msdyn_actuals** (Actuals)  
   - **msdyn_invoice** (Invoices)  
2. Load data into Power BI.  

**Validation:** Tables load successfully into Power BI model.  

---

## Exercise 3: Create Visualizations in Power BI

1. In **Power BI**, create visuals:  
   - **Clustered Column Chart:** Revenue vs. Cost by Project.  
   - **Line Chart:** Monthly invoicing trend.  
   - **Table:** Resource utilization by role.  
2. Save as **Project Ops Financial Dashboard.pbix**.  

**Validation:** Visuals display project financial KPIs.  

---

## Exercise 4: Export Data to Excel

1. In **Project Operations → Projects → Contoso ERP Implementation**, select **Export to Excel**.  
2. Choose **Static Worksheet** or **Dynamic PivotTable**.  
3. Analyze:  
   - Actual hours by resource.  
   - Expenses by category.  
   - Invoice totals.  

**Validation:** Excel reflects the same data from the system.  

---

## Results
You successfully:  
- Explored built-in reports in Project Operations.  
- Connected **Power BI** to Dataverse and built dashboards.  
- Exported project data to **Excel** for analysis.  

## Next steps
This concludes **Module 01: From Sales to Project Operations**. You have completed the full lifecycle:  
1. Opportunity → 2. Quote → 3. Contract → 4. Project Setup → 5. Resource Management → 6. Time & Expense → 7. Billing → 8. Reporting.  

For extended learning, proceed to advanced labs on:  
- **Resource Scheduling Optimization (RSO)**  
- **Multi-currency and global billing**  
- **Integration with Dynamics 365 Finance** for accounting and GL posting.  
