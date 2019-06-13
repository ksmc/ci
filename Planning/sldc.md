# Process for implementing change

The software development lifecycle (SLDC) is applicable to all forms of development projects whether that be making a change to a SQL reporting script, fixing a bug, or adding new content to your knowledge base. Each of these requires some form of effort to be expended and change to be made. 

For clarity, we are going to define these changes are issues. In many project management systems like JIRA, the term issues spans different changes that are needed or wanted. A issue may be a called a requirement, an epic, a defect, a test case, a task and more.

## Rule #1: All issues must follow a standard process.
In order to track change, we need a predictable path in which an issue can travel. Without predictability, traceability is overly complex, becomes antecdotal, and it unreliable.

## Issue Lifecycle

|ID|Step|Status|
|-----|-----|-----|
|1| Issue is logged in the system and added to a backlog | Not Started |
|2| Backlog grooming occurs and the issue is added to this sprint | Open |
|3| Slotted requests for Development and Assigned to a Lead | Open | 
|4| Lead then assigns to the dev | Under Development |
|5| Developer makes changes | Under Development |
|6| Developer determines changes are ready for review | In Review |
|7a| Changes are rejected | Under Development |
|7b| Changes are confirmed | Ready for Testing |
|8|  Changes are tested in batch | Testing |
|9a| Testing fails | Under Development |
|9b| Testing passes | Ready for Deployment |
|10| Once all issues status is Ready for Deployment, changes are ready to be deployed | Ready for Deployment |
|11| Deploy the changes | Closed |

## Rule #2: Small Batch Sizes
[Splitting Stories](https://blog.jbrains.ca/permalink/how-youll-probably-learn-to-split-features)

## Rule #3: Modularity in Design


