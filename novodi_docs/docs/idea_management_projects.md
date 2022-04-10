# Project (any role)

Projects are approved (project) [Sketches](idea_management_sketches.md) which are going to be implemented. Projects are used to plan a project based on the Sketch, track the implementation and evaluate the performance during and after the project.

The [Innovation Manager](idea_management_roles.md) uses Projects to review and govern the overall implementation of projects in cooperation with the assigned project manager.

## Project Attributes

|Attribute|Possible Value |Explanation|
|---|---|---|
|Title| *short text* ||
|Assigniee|*User*||
|Summary|*paragraph*||
|Status|*string*: Planning, Budget approval, Budget declined , In progress, Halted, Finished, Stopped||
|Started on| *date* ||
|Created on|*date*||
|Milestones*|*cards*||
|Benefits - Cost Saved Monthly|*number*|Estimated upside in costs|
|Benefits - Hours Saved Monthly|*number*|Estimated upside in man-hours|
|Budget Cost|*number*|Amount of money allocated for the project|
|Budget Hours|*number*|Amount of man-hours allocated for the project|
|Spent - Costs|*number*||
|Spent - Hours|*number*||

### *Milestone Attributes
|Attribute|Possible Value|Explanation|
|---|---|---|
|Title|*short text*||
|Assignee|*User*||
|Descrition|*short paragraph*||

## Add a Project

A Project can only be added by starting a project from an approved [Sketch](idea_management_sketches.md). Learn how to approve Sketches [here](/idea_management_sketches/#approving-a-sketch-innovation-manager).

## Edit a Project

1. Go to the Project tab in your organization.
2. Click on the Project which you would like to edit and click on the field you wish to edit.
3. Save the Project after editing.

## Submit a Budget

The budget is subdivided in three parts which are explained in [Project Score Card](#the-project-score-card). Complete the Benefits and Budget fields, click save and *Submit* to mark the project as *Budget Approval Pending*. The Project and budget can be reviewed and started by the Innovation Manager.

## Approve a Budget (Innovation Manager)

The Innovation Manager can select *Approve & start project* under the Project Score Card which automatically enables the [milestone tracking](#use-project-tasks) and *Spent* section of the Project Score Card for editing by the project manager.

## Reject a Budget

A submitted Budget can be declined and will be marked as such. The project manager can edit and submit the budget again.

## Control a Project

A Project which is *in progress* can be changed to three different statuses:

- Stop (indefinit). A project which is cancelled before it is completed. A stopped project cannot be continued later.
- Halt (temporary). A project can be put on hold and continued later if the priorities have changed.
- Finished (indefinit). A project is successfully completed.

## Use Project Tasks

Novodi provides very simple project management tools which allow an Innovation Manager and project stakeholders to effectively communicate the status of a project.

Project Tasks are such a tool. Initially Milestones from the Sketch are converted to Tasks and placed as cards in the *Todo* list.

Before starting a Project, Tasks can only be edited and added to the the *Todo* list.

Once a Project is *in progress* Tasks can be dragged and dropped to *In progress* and *Done*.

## The Project Score Card

The Project Score Card provides simple metrics to track and evaluate a project and compare it to other projects. Three categories are covered:

### Benefits

The intially estimated impact or upside of implementing the project can be tracked and changed as the project evolves and the impact becomes more obvious.

The two leading metrics are monthly savings of Costs and therefore actual funds which are currently spent but are going to be available after the project is completed and monthly Hours which can be allocated to other tasks.

We recommend to carefully estimate and average the benefits to have a comparable metrics across different projects.

### Budget

The Budget is split into two fields:

Cost is the montetary budget which is required for the implementation and Hours are the employee hours which are needed to implement the project.

### Spent

Spent relates to Budget metric above and can be updated as the project is progressing. The percentage value is relative to the Budget.
