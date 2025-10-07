# LAB[PO-101]_M01Lab01_Extend_Sales_to_Project_Opportunity

**Module:** 01 — From Sales to Project Operations  
**Lab Title:** Extending a Sales Opportunity into a Project Opportunity  
**Estimated time:** 30–45 minutes  

## Lab overview
In this lab, you’ll start with the Dynamics 365 Sales pipeline (Lead → Opportunity) and extend it to the **Project Operations** lifecycle by converting a Sales Opportunity into a **Project Opportunity** and capturing high-level project attributes.

## Learning objectives
- Create and qualify a **Lead** to an **Opportunity** in Sales.
- Convert an Opportunity to **Project-based** and complete project fields.
- Capture early **requirements** and **effort estimates** that flow into a Project Quote.

## Prerequisites
- Access to a **Dynamics 365 Project Operations** environment.
- App access to **Sales Hub**.
- Security role: **Salesperson** or **Project Operations Project Manager**.

## Scenario
You work for **TopRock Consulting**, a professional services firm. **Contoso Pharma** requested a 2-month ERP implementation. You will capture the lead, qualify it to an opportunity, and extend it to a **Project Opportunity**.

---

## Exercise 1: Qualify a Lead to an Opportunity

### Task 1: Create a lead
1. Navigate to **Sales Hub → Leads**.  
2. Select **+ New** and enter:  
   - **Topic:** ERP Implementation for Contoso Pharma  
   - **First Name:** Alex  
   - **Last Name:** Lee  
   - **Company:** Contoso Pharma  
   - **Business Phone:** (555) 123-4567  
3. **Save**.

**Validation:** The lead appears in **Open Leads**.

### Task 2: Qualify the lead
1. Open the lead and select **Qualify**.  
2. Confirm the system created and linked:  
   - **Account:** Contoso Pharma  
   - **Contact:** Alex Lee  
   - **Opportunity** (opens automatically)

**Validation:** An **Opportunity** record is open and linked to the Account and Contact.

---

## Exercise 2: Extend Opportunity into a Project Opportunity

### Task 1: Mark the opportunity as project-based
1. On the **Opportunity** form, set:  
   - **Opportunity Type** = **Project-based**  
   - **Est. Revenue** = **50,000**  
   - **Est. Close Date** = `+30 days` from today  
2. Go to the **Project Information** tab. Complete:  
   - **Project Name:** Contoso ERP Implementation  
   - **Project Manager:** _Your user_  
   - **Est. Effort (hours):** 320  

**Validation:** The Opportunity now shows **Project Information** fields and is flagged **Project-based**.

### Task 2: Capture initial requirements
1. In **Timeline / Notes**, add:  
   - 2-month ERP implementation  
   - Finance modules in-scope  
   - Go-live by end of next quarter  
2. **Save** the Opportunity.

**Validation:** Requirements are saved on the Opportunity’s timeline.

---

## Results
You created and qualified a lead, extended an Opportunity into a **Project Opportunity**, and captured early project details that will feed the **Project Quote** in the next lab.
