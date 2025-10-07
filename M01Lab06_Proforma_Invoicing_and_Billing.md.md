# LAB[PO-101]_M01Lab06_Proforma_Invoicing_and_Billing

**Module:** 01 — From Sales to Project Operations  
**Lab Title:** Pro Forma Invoicing & Billing  
**Estimated time:** 45–60 minutes  

## Lab overview
In this lab, you will create a **Pro Forma Invoice** for approved time and expenses, review the billing details, and then generate a **Customer Invoice**. This demonstrates how Dynamics 365 Project Operations supports project-based billing.

## Learning objectives
- Generate a **Pro Forma Invoice** for approved project actuals.  
- Review and adjust invoice lines before posting.  
- Post the **Customer Invoice** to the customer account.  
- Understand how invoicing impacts project and financial records.  

## Prerequisites
- Completed **M01 Lab 05 (Time & Expense Tracking)**.  
- Security role: **Project Operations Project Manager** or **Billing Admin**.  
- Approved **time and expense entries** exist for the project.  

## Scenario
Contoso Pharma has requested an invoice for work completed. You will generate a **Pro Forma Invoice**, review details, and post the final invoice to the customer.

---

## Exercise 1: Generate a Pro Forma Invoice

### Task 1: Navigate to Pro Forma Invoices
1. Go to **Project Operations → Billing → Pro Forma Invoices**.  
2. Select **+ New Pro Forma Invoice**.  

### Task 2: Configure invoice details
1. Enter:  
   - **Customer:** Contoso Pharma  
   - **Project Contract:** Contoso ERP Implementation Contract  
   - **Invoice Date:** Today  
   - **Billing Method:** Time & Material  
2. Click **Generate Lines**.  

**Validation:** System pulls approved **time and expense entries** into invoice lines.  

---

## Exercise 2: Review and Adjust Invoice Lines

1. On the **Invoice Lines** tab, verify:  
   - John Smith (Functional Consultant) → 32 hours @ $120/hr  
   - Travel – Hotel Expense → $500  
2. Optionally adjust invoice line descriptions (e.g., "ERP Implementation – Requirements Gathering").  
3. Save changes.  

**Validation:** Totals match approved project actuals.  

---

## Exercise 3: Post Customer Invoice

1. On the command bar, select **Confirm Invoice**.  
2. Review summary and confirm.  
3. Status changes to **Ready to Post**.  
4. Select **Post** to create a final **Customer Invoice** record.  

**Validation:** Invoice now appears in **Customer Invoices** with status = Posted.  

---

## Exercise 4: Review Impact on Financials

1. Navigate to **Project Operations → Projects → Contoso ERP Implementation**.  
2. Open the **Actuals** tab.  
3. Verify:  
   - Billed actuals match the posted invoice.  
   - Revenue and costs updated accordingly.  

**Validation:** Project financials reflect invoice posting.  

---

## Results
You successfully:  
- Created a **Pro Forma Invoice** for approved time and expenses.  
- Reviewed and confirmed invoice lines.  
- Posted the **Customer Invoice** to Contoso Pharma.  
- Observed the financial impact on the project.  

## Next steps
Proceed to **Lab 7: Project Actuals & Financial Analysis** to analyze project profitability, utilization, and KPIs with reports and dashboards.
