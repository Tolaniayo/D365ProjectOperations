# LAB[PO-101]_M01Lab10_Master_Data_Setup

**Module:** 01 — From Sales to Project Operations  
**Lab Title:** Master Data Setup for Project Operations  
**Estimated time:** 60–90 minutes  

## Lab overview
In this lab, you will configure the **core master data** required to run Dynamics 365 Project Operations. You will follow a recommended sequence, starting with organizational setup and ending with financial integration, to ensure downstream processes (projects, time, invoicing) function correctly.

## Learning objectives
- Configure **business units, calendars, and currencies**.  
- Set up **resource roles, resources, and skills**.  
- Define **price lists and cost lists** for billing.  
- Create **expense categories**.  
- Link master data into a **project contract**.  
- Validate the setup by creating a test project.  

## Prerequisites
- Access to a Dynamics 365 Project Operations environment.  
- Security role: **System Administrator** or **Project Operations Project Manager**.  

## Scenario
You are implementing Project Operations for **TopRock Consulting**. Before creating opportunities, quotes, and projects, you must configure the **foundation master data** that drives the system.

---

## Recommended Setup Sequence
1. Organizational Setup → Legal entities, business units, calendars, currencies.  
2. Resources & Roles → Bookable resources, roles, skills.  
3. Pricing & Costing → Price lists, cost lists, expense categories.  
4. Sales → Link price lists to opportunities and contracts.  
5. Projects → Create test project linked to contract.  
6. Execution → Validate time/expense entries.  

---

## Exercise 1: Organizational Setup

### Task 1: Configure business unit
1. Navigate to **Settings → Business Management → Business Units**.  
2. Create new:  
   - **Name:** TopRock Consulting BU  
   - **Parent:** Root  
3. Save.  

**Validation:** Business unit appears in the hierarchy.  

### Task 2: Define calendar & currency
1. Navigate to **Calendars → New**.  
   - **Name:** Standard 8-hour Calendar  
   - **Working Hours:** 9 AM–5 PM Mon–Fri  
2. Navigate to **Settings → Business Management → Currencies**.  
   - Confirm **USD** exists.  

**Validation:** Calendar and currency available for projects.  

---

## Exercise 2: Resources & Roles

### Task 1: Create roles
1. Go to **Resource Roles → New**.  
   - Project Manager  
   - Functional Consultant  
   - Technical Consultant  
2. Save each.  

### Task 2: Create bookable resources
1. Go to **Resources → New Bookable Resource**.  
   - **Name:** John Smith  
   - **Role:** Functional Consultant  
   - **Calendar:** Standard 8-hour Calendar  
   - **Resource Type:** User  
2. Save.  

**Validation:** John Smith is bookable with a role and calendar.  

---

## Exercise 3: Pricing & Costing

### Task 1: Create sales price list
1. Navigate to **Sales Hub → Settings → Price Lists → New**.  
   - **Name:** TopRock Sales Price List  
   - **Currency:** USD  
2. Add entries:  
   - Project Manager → $150/hr  
   - Functional Consultant → $120/hr  
   - Technical Consultant → $130/hr  

### Task 2: Create cost price list
1. Navigate to **Project Operations → Settings → Cost Price Lists → New**.  
   - **Name:** TopRock Cost Price List  
   - **Currency:** USD  
2. Add entries:  
   - Project Manager → $100/hr  
   - Functional Consultant → $80/hr  
   - Technical Consultant → $90/hr  

### Task 3: Create expense categories
1. Navigate to **Expense Categories → New**.  
   - Travel – Hotel  
   - Travel – Meals  
   - Travel – Flights  
2. Save.  

**Validation:** Both sales & cost price lists exist with roles and rates, plus expense categories.  

---

## Exercise 4: Sales & Contracts Setup

1. Navigate to **Opportunities → New**.  
   - **Topic:** Master Data Test Opportunity  
   - **Customer:** Contoso Pharma  
2. Qualify to create opportunity → Create **New Project Quote**.  
3. On quote, select **Price List = TopRock Sales Price List**.  
4. Add project-based line for Functional Consultant → 40 hours.  
5. Activate quote → Create contract.  

**Validation:** Contract lines reflect roles and rates from master data.  

---

## Exercise 5: Test Project Creation

1. From contract, create **New Project**.  
   - **Name:** Master Data Validation Project  
   - **Manager:** Your User  
   - **Calendar:** Standard 8-hour  
2. Add WBS task → Requirements Gathering (5 days).  
3. Assign John Smith (Functional Consultant).  

**Validation:** Project links to contract, role, price list, and resource.  

---

## Results
You successfully:  
- Set up **organizational units, calendars, currencies**.  
- Created **roles, resources, skills**.  
- Configured **price & cost lists, expense categories**.  
- Linked everything into an **opportunity, quote, contract, and project**.  

## Next steps
This lab completes the **foundational setup** required before real projects can run in Project Operations. Continue to Module 02 for advanced labs on **multi-currency billing, integrations, and portfolio reporting**.
