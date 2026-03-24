# Azure DevOps Essentials

## Lesson 3

+ **What is DevOps?**  
  It is fundamentally about delivering value by streamlining the software development and delivery process.

    + With DevOps, teams can manage solutions that require:
        + Configurations
        + Data Migration
        + Reporting
        + Integrations
        + Processes

### First versions

+ **Team Foundation Server (TFS)**  
    + Introduced in 2005, it is an ALM (Application Lifecycle Management) solution that provided tools for source control, project management, build automation, and bug tracking.

+ **Team Foundation Service**  
    + Launched in 2011, it was the preview of the cloud-based version of TFS, which later became Visual Studio Team Services (VSTS).

### Rebranded versions

+ In 2018, **VSTS** was renamed to **Azure DevOps Services** and **TFS** was rebranded as **Azure DevOps Server**.

### Azure DevOps (ADO) Services:

+ Azure Boards (teamwork)
+ Azure Repos (git)
+ Azure Pipelines (automated builds and tests)
+ Azure Test Plans
+ Azure Artifacts (create, host, and share software packages)

---

## Lesson 5

### Organization Settings  

#### General
+ **Name:** Represents the company or division.
+ **Privacy URL:** Used for the management of internal and external data privacy.
+ **Projects:** Lists all projects in the organization.
+ **Users:** Lists all users in the organization.
+ **Billing:** Shows project expense details and Azure subscription information.
+ **Global Notifications:** Management of alerts to notify users across the platform.
+ **Usage:** Provides an audit log of user activities.
+ **Extensions:** Provides additional functionality.
+ **Microsoft Entra:** Connects the company directory to Azure DevOps.

#### Others
+ **Security**
    + Permissions: Covers user-level and group-level permissions.
+ **Boards**
    + Process: Selection of the default process type.

## Lesson 6

### Project Settings  
The Azure DevOps user can manage project teams, notifications, auxiliary tools, pipelines, and GitHub connections.

## Lesson 7

### Access Levels
+ **Basic:** Provides access to most features. Cannot be assigned for free.
+ **Stakeholder:** Can be assigned to an unlimited number of users for free. Provides partial access to private projects.
+ **Visual Studio Subscriber:** Assigned to users who already have a Visual Studio subscription.

## Lesson 8

### Permissions Groups

#### Project
+ **Contributors** (Can add, modify, and delete items)
+ **Project Administrators** (All operations)
+ **Readers** (Read-only access – Analytics and Test)
+ **Custom groups**

#### Project Collection
Includes more categories such as: Service Accounts, Repos, Pipelines, Auditing, and Policies.

## Lesson 9

### Profile Customization  
In the top right corner, we have the following buttons:

- **My Work:** Work Items, Pull Requests, Favorites
- **Marketplace:** Browse and manage extensions
- **Help:** Contact Azure DevOps support, check service status, Privacy Policy, and Keyboard Shortcuts
- **User settings**
    - Preview Features selection
    - Account configurations: Profile, Time and Locale, Permissions
    - Preferences: Notifications, Theme, Usage

## Lesson 10

### Taxonomy (Hierarchical Classification System)

+ **Epic:** A large body of work that can be broken down into smaller, manageable tasks or user stories to facilitate planning and tracking.
+ **Feature:** A high-level requirement that provides business value and can be broken down into user stories.
+ **User Story:** A high-level requirement based on the user experience that provides business value and is broken down into tasks.
+ **Task:** A specific unit of work that represents an actionable item to be completed, usually associated with a user story.

### Processes

+ **Basic:** The simplest model. Uses Issue, Task, and Epic work item types.
+ **Agile:** Designed for iterative and user-focused development. In addition to the basic items, it allows tracking of bugs and their tasks.
+ **Scrum:** Designed for tracking Product Backlog Items and bugs.
+ **CMMI:** Uses a formal project management method that requires a framework for process improvement and an auditable record of decisions. It is possible to track *Change Requests*, *Reviews*, and *Risks*.

##### Note
Each project has its own collection of workflow states for each work item type.

##### Work Item States
+ **New:** The work item has just been created.
+ **Active:** Under development and testing.
+ **Resolved:** Development is complete and the item is ready for acceptance testing.
+ **Closed:** The work item has passed all required validations.
+ **Removed:** The work item is no longer needed and has been removed from the backlog.

---

<div style="position: fixed; bottom: 30px; right: 30px; z-index: 1000;">
  <a href="session_02.md" 
     style="background-color: #0078D4; color: white; padding: 12px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; 
            box-shadow: 0 4px 12px rgba(0,0,0,0.15); display: inline-flex; 
            align-items: center; gap: 8px;">
    ➡️ Next Session (Lesson 11+)
  </a>
</div>