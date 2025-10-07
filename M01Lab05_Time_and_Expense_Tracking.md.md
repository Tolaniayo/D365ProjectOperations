# LAB[PO-101]_M01Lab05_Time_and_Expense_Tracking

**Module:** 01 — From Sales to Project Operations  
**Lab Title:** Time & Expense Tracking  
**Estimated time:** 45–60 minutes  

## Lab overview
In this lab, you will simulate how project team members record **time** and **expenses** against project tasks, and how managers review and approve them.

## Learning objectives
- Enter **time entries** for project tasks.  
- Submit **expense reports** with receipts.  
- Approve or reject time and expenses.  
- Understand how actuals flow into **project financials**.  

## Prerequisites
- Completed **M01 Lab 04 (Resource Management)**.  
- Security role: **Project Operations Project Manager** or **Team Member**.  
- Project with tasks and resources assigned.  

## Scenario
Your team members on the **Contoso ERP Implementation** project are now executing tasks. You’ll log time for a consultant, submit an expense report, and process approvals.

---

## Exercise 1: Record Time Entries

### Task 1: Open Time Entry
1. Navigate to **Project Operations → Time Entries**.  
2. Select **+ New Time Entry**.  

### Task 2: Enter time for project tasks
1. Fill in details:  
   - **Resource:** John Smith (Functional Consultant)  
   - **Date:** Today  
   - **Project:** Contoso ERP Implementation  
   - **Task:** Requirements Gathering  
   - **Hours:** 8  
2. Save the entry.  
3. Repeat for 3 additional days (total 32 hours).  

**Validation:** Time entries appear in the grid, linked to project/task.  

---

## Exercise 2: Submit Time for Approval

1. From **Time Entries**, select all entries created.  
2. Click **Submit**.  
3. Status changes from **Draft** → **Submitted**.  

**Validation:** Entries now show status = Submitted.  

---

## Exercise 3: Approve Time (Manager Role)

1. Switch role to **Project Manager** (or user with approval rights).  
2. Navigate to **Project Approvals → Time**.  
3. Select the submitted entries.  
4. Click **Approve**.  

**Validation:** Status changes to **Approved**; actual costs/revenue recorded in project financials.  

---

## Exercise 4: Record Expenses

### Task 1: Create an expense report
1. Navigate to **Project Operations → Expenses**.  
2. Select **+ New Expense Report**.  
3. Enter:  
   - **Resource:** John Smith  
   - **Project:** Contoso ERP Implementation  
   - **Expense Category:** Travel – Hotel  
   - **Amount:** 500 USD  
   - **Date:** Today  
4. Upload a receipt (use placeholder PDF/JPG).  
5. Save.  

### Task 2: Submit and approve
1. Submit the expense report.  
2. Switch to **Manager** role → Approvals → Expenses.  
3. Review and **Approve**.  

**Validation:** Expense appears as an approved actual against the project.  

---

## Results
You successfully:  
- Entered and submitted **time entries** for project tasks.  
- Submitted and approved an **expense report**.  
- Observed how approved entries flow into **project actuals** for financial tracking.  

## Next steps
Proceed to **Pro Forma Invoicing & Billing (M01 Lab 06)** to generate draft invoices for client billing based on approved time and expenses.
