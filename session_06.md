# ADO Dashboards and Queries

## Lesson 54

In Azure DevOps, it is possible to create dynamic dashboards to track project data.

- Go to **Overview → Dashboard**, click on the **New Widget** button, then select the widgets that best match your goals.

---

## Lesson 59

### Velocity Metrics

Velocity metrics provide valuable insights that help teams plan and forecast sprints more effectively.

---

## Lesson 60

### Burndown Chart

Shows the remaining work of a project over time.

#### Sprint Burndown
Displays a burndown chart for the work of a team in a single sprint.

#### Scope
Original estimate.

#### Negative Burndown (Below Ideal Line)

- **What it means:** The team is ahead of schedule.  
- **Interpretation:** The blue line (actual work) is below the gray line (ideal trend).  
- **Significance:** The team is completing tasks faster than expected, or the work was overestimated during planning.  
- **Action:** If consistent, consider increasing the scope for future sprints or taking on more work, as team velocity is higher than estimated.

#### Positive/Higher Burndown (Above Ideal Line)

- **What it means:** The team is behind schedule.  
- **Interpretation:** The blue line (actual work) is above the gray line (ideal trend).  
- **Significance:** Work is not being completed at the planned rate, or there has been an increase in scope (scope creep).  
- **Action:** Analyze potential bottlenecks, reduce scope, or adjust expectations for the final sprint goal.

---

## Lesson 61

### Flow Diagram

Shows the history of work progressing through various workflow stages (represented by swim lanes).

---

## Lesson 62

You can create queries across multiple projects.

---

## Lesson 63

### Export and Import

It is possible to export and import work item queries using **.csv** format.

#### Import Process
- Go to **Boards → Queries** and click **Import work items**.

#### Export Process
- Go to **Boards → Queries** and click **Export to CSV**.

#### Important Notes

- If you import a work item file containing states that are not defined in the project process, an error will appear in red in the backlog and the import will fail.
- Test cases cannot be imported/persisted through this method.

---

<!-- Navigation Buttons -->
<div style="position: fixed; bottom: 30px; right: 30px; z-index: 1000;">
  <a href="session_05.md" 
     style="background-color: #0078D4; color: white; padding: 12px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; 
            box-shadow: 0 4px 12px rgba(0,0,0,0.15); display: inline-flex; 
            align-items: center; gap: 8px; margin-right: 10px;">
    ← Previous (session_05.md)
  </a>
  <a href="session_07.md" 
     style="background-color: #0078D4; color: white; padding: 12px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; 
            box-shadow: 0 4px 12px rgba(0,0,0,0.15); display: inline-flex; 
            align-items: center; gap: 8px;">
    Next (session_07.md) →
  </a>
</div>