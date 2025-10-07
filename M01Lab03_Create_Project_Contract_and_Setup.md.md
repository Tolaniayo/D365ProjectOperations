# LAB[PO-101]_M01Lab03_Create_Project_Contract_and_Setup

**Module:** 01 — From Sales to Project Operations  
**Lab Title:** Creating a Project Contract & Project Setup  
**Estimated time:** 45–75 minutes  

## Lab overview
In this lab, you’ll convert the **Active Project Quote** into a **Project Contract**, then create a **Project** with a Work Breakdown Structure (WBS) and link it for execution and billing.

## Learning objectives
- Create a **Project Contract** from an **Active Quote**.
- Review/confirm **contract lines** and billing methods.
- Create a **Project** and build out **tasks/milestones** in the WBS.
- Associate the project to the contract.

## Prerequisites
- Completed **M01 Lab 02**.
- Security role: **Project Operations Project Manager** or **Salesperson**.

## Scenario
Contoso Pharma accepted the quote. You’ll generate the contract, verify lines, and build the delivery project.

---

## Exercise 1: Create the Project Contract
1. Navigate to **Sales Hub → Quotes**, open **Contoso ERP Implementation Quote (Active)**.  
2. Select **Create Contract**.  
3. Verify:  
   - **Name:** Contoso ERP Implementation Contract  
   - **Type:** Project-based  
   - **Currency:** USD  
   - **Customer:** Contoso Pharma  
4. **Save**.

**Validation:** Contract is created and linked back to the quote/opportunity.

---

## Exercise 2: Verify contract lines
1. Open **Contract → Contract Lines**.  
2. Confirm lines for **Project Manager**, **Functional Consultant**, **Technical Consultant** exist with **Time & Material** billing and correct rates/hours.  
3. **Save**.

**Validation:** **Total contract value ≈ $50,000** (varies by rates/discounts).

---

## Exercise 3: Create and structure the Project
1. On the **Contract**, go to **Projects** and select **+ Add New Project**.  
2. Enter:  
   - **Project Name:** Contoso ERP Implementation  
   - **Project Manager:** _Your user_  
   - **Start Date:** Today | **End Date:** +2 months  
   - **Calendar Template:** Standard 8-hour workday  
3. **Save**.

**Validation:** A new **Project** record is created and linked to the contract.

---

## Exercise 4: Build the WBS
1. Open the **Project**, go to **Tasks (WBS)**, and add:  
   - Project Kickoff — 1 day  
   - Requirements Gathering — 10 business days  
   - System Configuration — 20 business days  
   - User Training & UAT — 10 business days  
   - Go-Live & Handover — 5 business days  
2. Mark **Requirements Gathering Complete** and **Go-Live** as **Milestones**.  
3. **Save**.

**Validation:** WBS contains 5 tasks with two milestones.

---

## Results
You produced a **Project Contract** from the accepted quote and structured the **Project** for delivery with a clear WBS and milestones.
