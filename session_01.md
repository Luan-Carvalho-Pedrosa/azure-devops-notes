# Azure Devops Essentials

## Lesson 3

+ **What is DevOps?** Is fundamentally about delivering value by streamlining the  
                        the software developmen and delivery process.
    + With DevOps, teams can manage solutions that require:
        + Configurations
        + Data Migration
        + Reporting
        + Integrations
        + Process
### First versions
+ **Team Foundation Server (TFS)**
    + Introduced in 2005, is a ALM solution that provided tools for
        source control, project management, build automation, and bug tracking.
+ **Team Foundation Service**
    + Lauched in 2011, is a preview of the cloud-based version of TFS, wHich later
        became Visual Studio Team Services (VSTS).

### Rebranded versios
+ In 2018, **VSTS** turned into **Azure DevOps Services** and **TFS** was rebranded
    as **Azure DevOps Server**.

### Azure DevOps (ADO) Services:
+ Azure Boards (teamwork)
+ Azure Repos (git)
+ Azure Pipelines (automatic build and test)
+ Azure Test Plans
+ Azure Artifacts (create, host and share software packages)

## Lesson 5

### Organization Settings  

#### General
+ **Name:** Represents the company our division.
+ **Privacy URL:** For management of internal and external data privacy.
+ **Projects:** List all organization projects.
+ **Users:** List of organization projects.
+ **Billings:** Project expense details with Azure functionalities.
+ **Global Notifications:**  Management of alerts to notify user across the plattform.
+ **Usage:** Provides an audit log of user activies.
+ **Extensions:** Provides addictional funtionality.
+ **Microsoft Entra:** Connect company directory to ADO.

#### Others
+ Security
    + Permissions: Cover user level and group leve permissions.
+ Boards
    + Process: Selection of default type of process.

## Lesson 6

### Project Setings  
The ADO user can manage projects teams, notifications, auxiliar tools, pipelines 
and connections with github.

## Lesson 7


### Acess Level
+ **Basic:** Provides access to most features. Canot assing user for free
+ **Stakeholder:**  Can assign to unlimited users for free. Provides partial access
                    to private projects.
+ **Visual Studio Subscriber:** Assing to users who already have a VS subscription.

## Lesson 8


### Permissions Groups

#### Project
+ Contributors (Can add, modify, and delete items)
+ Project Admnistrators (All operations)
+ Reader (Only Analytics and Tes)
+ Customized group 

#### Project Collection
Have more categories like, Service Account, Repos, Pipelines, Auditing and Policies.


## Lesson 9

### Profile customization  
In the top right corner, we have that bottons:
- MyWork: Work Itens, Pull Request, Favorites
- Marketplace: Browse, Manage Extensions
- Help: Contact with ADO suport, Service status check, Private Policy
        Keyboard Shotcourts.
- User settings
    - Preview Features selection
    - Account configurtations: Profile, Time and Locale, Permissions
    - Preferences: Notifications, Theme, Usage


## Lesson 10

### Taxonomy (hierarchical classification system)

+ **Epic:** Large body of work to be broken down into smaller, manageable tasks
             or user stories to facilitate planning and tracking within a project.
+ **Feature:** Is a high-leve requirement that provides business value and can be
                broken down into user stories.
+ **Stories:** Is a high-level requirement based on the user experience that provides business value
                and is broken down into tasks.
+ **Task**: Is a specific unit of work that represents an actionable item to be completed within a 
            project, often associated with a user story.


### Process

+ **Basic:** Simplest model that use Issue, Task and Epic work item types.
+ **Agile:** Designed for iterative and user focused development. In addition to the surveying items,
                we can track bugs and his tasks.
+ **Scrum:** Designed for tracking product backlog items and bugs.
+ **CMMI:** Formal project methods that require a framework for process improvement and an auditable
            record of decisions. It is possible to track *Changes Request*, *Reviews* and *Risk*.

##### Note
Each project have a collection of different workflow states for each item. 

##### Item states
+ **New:** Work item is logged as a new item.
+ **Active:** Development and tests.
+ **Resolved:** Development is complete and it go to acceptance tests.
+ **Closed:** Work item has passed al required validations.
+ **Removed:** Work item is no longer required and is taken out of the backlog.



