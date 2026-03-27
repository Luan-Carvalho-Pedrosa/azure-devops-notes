# Starting with the Basics: Creating ADO Work Items

## Lesson 12

### Azure Boards
- Helps teams plan, track, and manage their work in an organized way.
- Its default columns have the same name as the **Work Item States**.
- You can fully customize the board for any workflow.

#### Ways of Use

+ **Kanban:**  
    + Work is managed as a continuous flow.  
    + There are no defined deadlines or formal ceremonies.  
    + Best suited for Support Teams and Operations.

+ **Scrum:**  
    + A structured framework designed to help teams work more effectively.  
    + Divides the workflow into set time periods called **sprints** (typically 1 to 4 weeks).  
    + Ideal for product development or projects with evolving requirements that need frequent feedback.  
    + Core values: collaboration, transparency, and continuous improvement.

#### Column Limits (WIP)
+ Called **WIP** (Work In Progress).  
+ Controls how many work items can be in a certain stage at one time.  
+ When the limit is exceeded, the column is highlighted in red.

---

## Lesson 13

### Epic
Represents the big picture — the overarching initiative that guides a program or project.

#### How to Create an Epic?
+ Boards → Work Items → New Work Item  
+ Boards → Backlogs → New Work Item  
+ Boards → Boards → + New Item

#### Item Properties
+ **ID**
+ **Title**
+ **Assigned To** (usually the Product Owner or Manager)
+ **Comments**
+ **Tags**
+ **State → Reason**
+ **Area**: Functional area or team responsible for the epic.
+ **Iteration**: Timeline or sprint for the epic.

#### Item Details Fields
+ Description
+ Discussion
+ Planning
    + Priority
    + Risk
    + Effort
    + Business Value
    + Time Criticality
    + Dates (Start, Target)
+ Classification
+ Deployment
+ Development
+ Related Work

#### Item Tabs
Details | History | Links | Files | Configurations

#### Follow Button
Enables notifications for any changes to this work item.

---

## Lesson 14

### Feature Creation
- Select an Epic card on the Board → **Add Feature**

### INVEST Criteria (for User Stories)
+ **I:** Independent  
+ **N:** Negotiable  
+ **V:** Valuable  
+ **E:** Estimable  
+ **S:** Sized Appropriately  
+ **T:** Testable

---

## Lesson 15

### Anatomy of a User Story (US)
A User Story describes a feature or functionality from the end user’s perspective.

**Standard Format:**
- **As a** [Persona]  
- **I want** [desired capability]  
- **So that** [business value or purpose]

### Acceptance Criteria
Confirms that we built the right thing, for the right user, delivering the expected value.

---

## Lesson 16

### User Story Creation
- Select a Feature card on the Board → **Add User Story**

---

## Lesson 17

### Task Creation
- Select a User Story card on the Board → **Add Task** (or Test Case / Bug)

---

## Lesson 18

### Generation of Work Items with AI
See the definitions in this file: [AI Project Work Item Definitions.xlsx](files/AI+Project+Work+Item+Defintitions.xlsx)

---

## Lesson 19

### Creation of Iterations
Go to **Project Settings** → **Project Configuration** → **New child**

### Make Iterations Visible
Go to **Project Settings** → **Team Configuration** → **Iterations** → Select the desired iteration.

You can move a work item from one iteration to another by dragging it or editing its Iteration field.

---

<!-- Navigation Buttons -->
<div style="position: fixed; bottom: 30px; right: 30px; z-index: 1000;">
  <a href="session_01.md" 
     style="background-color: #0078D4; color: white; padding: 12px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; 
            box-shadow: 0 4px 12px rgba(0,0,0,0.15); display: inline-flex; 
            align-items: center; gap: 8px; margin-right: 10px;">
    ← Previous (session_01.md)
  </a>
  <a href="session_02.md" 
     style="background-color: #0078D4; color: white; padding: 12px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; 
            box-shadow: 0 4px 12px rgba(0,0,0,0.15); display: inline-flex; 
            align-items: center; gap: 8px;">
    Next (session_02.md) →
  </a>
</div>