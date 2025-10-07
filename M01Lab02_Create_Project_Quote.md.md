# LAB[PO-101]_M01Lab02_Create_Project_Quote

**Module:** 01 — From Sales to Project Operations  
**Lab Title:** Creating a Project Quote  
**Estimated time:** 40–60 minutes  

## Lab overview
In this lab, you will create a **Project Quote** from the project opportunity and define pricing via roles, estimated effort, and discounts.

## Learning objectives
- Create a **Project Quote** linked to a Project Opportunity.
- Add **project-based quote lines** for roles with hours and rates.
- Review totals and apply a **discount**.
- **Activate** the quote for customer submission.

## Prerequisites
- Completed **M01 Lab 01**.
- Security role: **Salesperson** or **Project Operations Project Manager**.

## Scenario
Contoso Pharma requested a formal quote. You’ll create a quote with Project Manager, Functional Consultant, and Technical Consultant roles and prepare it for approval.

---

## Exercise 1: Create the Project Quote
1. Navigate to **Sales Hub → Opportunities** and open **Contoso ERP Implementation**.  
2. Select **+ New Quote**.  
3. Enter:  
   - **Quote Name:** Contoso ERP Implementation Quote  
   - **Currency:** USD  
   - **Quote Type:** **Project-based**  
   - **Customer:** Contoso Pharma  
4. **Save**.

**Validation:** Quote status = **Draft**, linked to the opportunity.

---

## Exercise 2: Add project-based quote lines
1. On **Quote → Quote Lines**, select **+ New Project-based Quote Line** and create:  
   - **Role:** Project Manager | **Hours:** 40 | **Rate:** 150/hr  
2. Repeat for:  
   - **Functional Consultant | Hours:** 160 | **Rate:** 120/hr  
   - **Technical Consultant | Hours:** 120 | **Rate:** 130/hr  
3. **Save** each line.

**Validation:** Total **estimated hours = 320**; line amounts roll up to the quote.

---

## Exercise 3: Review totals and activate
1. Go to **Summary** and verify totals.  
2. Optionally add a **5% discount**.  
3. Select **Activate Quote**.  

**Validation:** Quote status = **Active**, locked for editing.

---

## Results
You created and activated a **Project Quote** with roles and pricing and (optionally) applied a discount.
