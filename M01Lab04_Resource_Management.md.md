# LAB[PO-101]_M01Lab04_Resource_Management

**Module:** 01 — From Sales to Project Operations  
**Lab Title:** Resource Management  
**Estimated time:** 45–60 minutes  

## Lab overview
In this lab, you will learn how to manage project resources in Dynamics 365 Project Operations. You’ll identify required roles, search for resources by skills and availability, and assign them to project tasks.

## Learning objectives
- Identify **resource requirements** from a project contract/project tasks.  
- Search for resources by **role, skills, and availability**.  
- Assign resources to project tasks.  
- Resolve allocation conflicts.  

## Prerequisites
- Completed **M01 Lab 03**.  
- Security role: **Project Operations Project Manager**.  
- An existing **Project Contract** and **Project** with tasks (from Lab 3).  

## Scenario
With the project contract in place for **Contoso Pharma’s ERP Implementation**, you need to staff the project. You will define resource requirements, search for available consultants, and assign them to tasks in the WBS.

---

## Exercise 1: Define Resource Requirements

### Task 1: Open the Project
1. Navigate to **Project Operations → Projects**.  
2. Open **Contoso ERP Implementation**.  
3. Go to the **Team** tab.  

### Task 2: Add resource requirements
1. Select **+ Add Team Member** → **New Requirement**.  
2. Enter the following:  
   - **Role:** Project Manager | **Required Hours:** 40 | **Booking Type:** Proposed  
   - **Role:** Functional Consultant | **Required Hours:** 160 | **Booking Type:** Proposed  
   - **Role:** Technical Consultant | **Required Hours:** 120 | **Booking Type:** Proposed  
3. **Save**.  

**Validation:** Resource requirements appear in the **Team** grid with status = Proposed.  

---

## Exercise 2: Search for Resources

### Task 1: Open requirement details
1. In the **Team** grid, select the **Functional Consultant** requirement.  
2. Click **Find Resources**.  

### Task 2: Filter by skills & availability
1. In the **Resource Search** window, filter by:  
   - **Role:** Functional Consultant  
   - **Skill:** Dynamics 365 Finance  
   - **Availability:** Next 2 months  
2. Review the results (e.g., John Smith – 80% available).  

**Validation:** Matching resources appear with utilization %, location, and skills.  

---

## Exercise 3: Assign Resources

### Task 1: Book a resource
1. From the search results, select **John Smith**.  
2. Choose **Book** → **Full Capacity**.  
3. Confirm the requirement changes from **Proposed** to **Committed**.  

### Task 2: Assign to WBS task
1. Navigate to the **Schedule (WBS)** tab.  
2. Select **Requirements Gathering → Assign Resource**.  
3. Assign **John Smith** (Functional Consultant).  
4. **Save**.  

**Validation:** Resource now appears under the task in WBS view.  

---

## Exercise 4: Resolve Conflicts (Optional)

1. Create a second requirement for **Technical Consultant** with overlapping allocation.  
2. Attempt to assign **Jane Doe**, who is already 90% booked.  
3. System prompts a **booking conflict**.  
4. Adjust booking to **Partial Capacity** (50%).  

**Validation:** Conflict resolved, and Jane is partially allocated.  

---

## Results
You created **resource requirements**, searched for consultants by role and skills, booked them to the project, and assigned them to WBS tasks. You also learned how to handle allocation conflicts.

## Next steps
Continue with **Time & Expense Tracking (M01 Lab 05)** to simulate team members entering time and expenses against the project.
