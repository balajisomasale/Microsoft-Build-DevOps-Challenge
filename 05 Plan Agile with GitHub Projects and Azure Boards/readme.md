## Introduction


This module introduces you to GitHub Projects, GitHub Project Boards, and Azure Boards. It explores ways to link Azure Boards and GitHub, 
configure GitHub Projects and Project views, and manage work with GitHub Projects.

#### Learning objectives
After completing this module, students and professionals can:

- Describe GitHub Projects and Azure Boards.
- Link Azure Boards and GitHub.
- Configure and Manage GitHub Projects and boards.
- Customize Project views.

#### Prerequisites
- Understanding of what DevOps is and its concepts.
- Familiarity with version control principles is helpful but isn't necessary.
- Beneficial to have experience in an organization that delivers software.
- You need to create a GitHub account at GitHub.com and a project for some exercises. 
- If you don't have it yet, see: Join GitHub · GitHub. If you already have your GitHub account, 
- create a new repository Creating a new repository - GitHub Docs.

--------------------

## Introduction to GitHub Projects and Project boards

### Project Boards

During the application or project lifecycle, it's crucial to plan and prioritize work.
With Project boards, you can control specific feature work, roadmaps, release plans, etc.

Project boards are made up of issues, pull requests, and 
notes categorized as cards you can drag and drop into your chosen columns. 
The cards contain relevant metadata for issues and pull requests, like labels, assignees, the status, and who opened it.

![image](https://github.com/balajisomasale/Microsoft-Build-DevOps-Challenge/assets/35003840/63133c8a-cca7-4306-8e20-c79d34fea004)

There are different types of project boards:

- User-owned project boards: Can contain issues and pull requests from any personal repository.
- Organization-wide project boards: Can contain issues and pull requests from any repository that belongs to an organization.
- Repository project boards: Are scoped to issues and pull requests within a single repository.
- To create a project board for your organization, you must be an organization member.

It's possible to use templates to set up a new project board that will include columns and cards with tips.
The templates can be automated and already configured.

![image](https://github.com/balajisomasale/Microsoft-Build-DevOps-Challenge/assets/35003840/d54be55b-5b76-4e1f-904d-e927bf04a555)

Creating a project board : https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/creating-a-project-board 

Editing a project board : https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/editing-a-project-board

Copying a project board : https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/copying-a-project-board

Adding issues and pull requests to a project board : https://docs.github.com/en/issues/organizing-your-work-with-project-boards/tracking-work-with-project-boards/adding-issues-and-pull-requests-to-a-project-board

Project board permissions for an organization : https://docs.github.com/en/organizations/managing-access-to-your-organizations-project-boards/project-board-permissions-for-an-organization

## Projects
Projects are a new, customizable and flexible tool version of projects for planning and tracking work on GitHub.

A project is a customizable spreadsheet in which you can configure the layout by filtering, sorting, grouping your issues and PRs, and adding custom fields to track metadata.

You can use different views such as Board or spreadsheet/table.

![image](https://github.com/balajisomasale/Microsoft-Build-DevOps-Challenge/assets/35003840/398647b7-84db-4ea4-913b-fcf68b83e67f)

If you change your pull request or issue, your project reflects that change.

You can use custom fields in your tasks. For example:

- A date field to track target ship dates.
- A number field to track the complexity of a task.
- A single select field to track whether a task is Low, Medium, or High priority.
- A text field to add a quick note.
- An iteration field to plan work week-by-week, including support for breaks.

----------------------------------


## Introduction to Azure Boards : 

Azure Boards is a customizable tool to manage software projects supporting Agile, Scrum, and Kanban processes by default. Track work, issues, and code defects associated with your project. Also, you can create your custom process templates and use them to create a better and more customized experience for your company.

You have multiple features and configurations to support your teams, such as calendar views, configurable dashboards, and integrated reporting.

## Link GitHub to Azure Boards

Use GitHub, track work in Azure Boards

Use Azure Boards to plan and track your work and GitHub as source control for software development.

Connect Azure Boards with GitHub repositories, enabling linking GitHub commits, pull requests, and issues to work items in Boards.

## Configure GitHub Projects

#### Create a project

To start working with GitHub Projects, you first need to create an organization or user project.

![image](https://github.com/balajisomasale/Microsoft-Build-DevOps-Challenge/assets/35003840/13f9e734-4d05-481b-9a85-2811f298a1ca)

## Manage work with GitHub Project boards

GitHub Projects allow you to control project deliverables, release dates, and iterations to plan upcoming work.

You can create an iteration to:

- Associate items with specific repeating blocks of time.
- Set to any length of time.
- Include breaks.

It's possible to configure your project to group by iteration to visualize the balance of upcoming work.

When you first create an iteration field, three iterations are automatically created. You can add other iterations if needed.

![image](https://github.com/balajisomasale/Microsoft-Build-DevOps-Challenge/assets/35003840/47116da2-fbf5-4f56-ae63-e53b276ca5e6)


Iteration field
You can use the command palette or the project's interface to create an iteration field.

 Tip

To open the project command palette, press Ctrl+K (Windows/Linux) or Command+K (Mac).

Start typing any part of "Create new field". When "Create new field" displays in the command palette, select it.

Or follow the steps using the interface:

1. Navigate to your project.
2. Click in the plus (+) sign in the rightmost field header. A drop-down menu with the project fields will appear.
3. Click in the New field.
4. Enter a name for the new iteration field.
5. Select the dropdown menu below and click Iteration.
6. (Optional) Change the starting date from the current day, select the calendar dropdown next to Starts on, and click on a new starting date.
7. To change the duration of each iteration, type a new number, then select the dropdown and click either days or weeks.
8. Click Save and create.


![image](https://github.com/balajisomasale/Microsoft-Build-DevOps-Challenge/assets/35003840/e89274b3-33e8-4765-822e-af923742f0a2)

## Customize Project views

Using Projects views, you can organize information by changing the layout, grouping, sorting, and filtering your work.

You can create and use different visualizations, for example, Board view:

![image](https://github.com/balajisomasale/Microsoft-Build-DevOps-Challenge/assets/35003840/f88cf268-3985-4f85-9235-2fdf4a920d14)

### Project command palette
Use the project command palette to change settings and run commands in your project.

Open the project command palette by pressing Command + K (Mac) or Ctrl + K (Windows/Linux).
Type any command part or navigate through the command palette window to find a command.

You have multiple commands to apply, such as:

Switch layout: Table.
Show: Milestone.
Sort by: Assignees, asc.
Remove sort-by.
Group by: Status.
Remove group-by.
Column field by: Status.
Filter by Status.
Delete view.

## Creating a project view
Project views allow you to view specific aspects of your project. Each view is displayed on a separate tab in your project.

For example, you can have:

- A view that shows all items not yet started (filter on Status).
- A view that shows the workload for each team (group by a custom Team field).
- A view that shows the items with the earliest target ship date (sort by a date field).

To add a new view:

To open the project command palette, press Command + K (Mac) or Ctrl + K (Windows/Linux).
Start typing New view (to create a new view) or Duplicate view (to duplicate the current view).
Choose the required command.
The new view is automatically saved.

## Collaborate using team discussions

GitHub discussions can help make your team plan together, update one another, or talk about any topic you'd like in discussion posts on your team's page in an organization.

You can use team discussions for conversations that span across projects or repositories (issues, pull requests, etc.). Instead of opening an issue in a repository to discuss an idea, you can include the entire team by having a conversation in a team discussion.

![image](https://github.com/balajisomasale/Microsoft-Build-DevOps-Challenge/assets/35003840/c164efe2-7f11-41da-ac1a-c3d54f2090c8)

With team discussions, you can:

- Post on your team's page or participate in a public discussion.
- Link to any team discussion to reference it elsewhere.
- Pin important posts to your team's page.
- Receive email or web notifications.
- Team discussions are available in organizations by default.

You can also use organization discussions to facilitate conversations across your organization.

-------------------


## Agile plan and portfolio management with Azure Boards

Scenario
In this lab, you'll learn about the agile planning and portfolio management tools and processes provided by Azure Boards and 
how they can help you quickly plan, manage, and track work across your entire team.

You'll explore the `product backlog`, `sprint backlog`, and `task boards` that can track the flow of work during an iteration. 

We'll also look at the enhanced tools in this release to scale for larger teams and organizations.

Objectives
After completing this lab, you'll be able to:

- Manage teams, areas, and iterations.
- Manage work items.
- Manage sprints and capacity.
- Customize Kanban boards.
- Define dashboards.
- Customize team process.

Requirements
- This lab requires Microsoft Edge or an Azure DevOps-supported browser.
- Set up an Azure DevOps organization: If you don't already have an Azure DevOps organization that you can use for this lab, create one by following the instructions available at Create an organization or project collection.

### Exercises
During this lab, you'll complete the following exercises:

- Exercise 0: Configure the lab prerequisites.
- Exercise 1: Manage an Agile project.
- Exercise 2 (optional): Define dashboards.


Exercises are done and is about the above objections - easy ones 

-------- 
