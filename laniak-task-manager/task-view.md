---
description: You can see history of updates on any particular task on task view page.
---

# Task View

There are multiple ways to navigate to Task View. You can open any task from [TaskBoard](task-board.md) or [Assignment & Verification](assignments-and-verification/) Page. You can also navigate to Task View from table on [Task action window](action-windows/task.md) while creating new task.

<figure><img src="../.gitbook/assets/Task View window.jpg" alt=""><figcaption></figcaption></figure>

In top-left corner you can see the Task Id , Title and below that will be the Task Description :one:.

{% hint style="warning" %}
**Note:**

* You cannot update TaskId , Title or Description of the task.
{% endhint %}

On the right of Title, you will be able to see quick action button panel for quick task updates :two:.

On the right hand side, you can see all the details of tasks :three:.

Below the Task details, you will find the list of file attachments which have been added through out the timeline of the task :four:.

In the **Activity** section, you will get to see timeline including list of all the updates  performed on the task including added comments.



### Action Button Panel Operations

Action buttons panel has been divided in two sections.&#x20;

<figure><img src="../.gitbook/assets/Task View action buttons.jpg" alt=""><figcaption></figcaption></figure>

Left section primarily indicates below workflow related operations.

![](<../.gitbook/assets/ac 2.png>)  :  This will migrate Task workflow state to next workflow state. Below workflow migrations are possible.

<table><thead><tr><th width="209">Current State</th><th>Next State</th><th>Comment</th></tr></thead><tbody><tr><td><code>New</code></td><td><code>In_Progress</code></td><td></td></tr><tr><td><code>In_Progress</code></td><td><code>Self_Commit</code></td><td>Migration from <code>In_Progress</code> to <code>Self_Commit</code> is default behavior</td></tr></tbody></table>

![](<../.gitbook/assets/ac 3.png>)  :  This will move tasks from `New` or `In_Progress` to `Self_Commit` workflow state.

![](<../.gitbook/assets/ac 4.png>)  :  This will move task from `New` or `In_Progress` to `Self_Delete` workflow state.

***

Right section of action button panel will have all other possible operations apart from workflow operations. These include below operations.&#x20;

![](<../.gitbook/assets/ac 1.png>)  :  This will navigate you to [Task Action Window](action-windows/task.md) which will allow you to create new task. This will not update Task.

![](<../.gitbook/assets/ac 5.png>)  :  This will reload entire Task view.

![](<../.gitbook/assets/ac 6.png>)  :  This will allow you to add attachments to the task.

{% hint style="warning" %}
**Note:**

* Since LTM is running on free subscription of Uploadcare CDN, all uploaded files will be retained for 7 days.
* Since free tier of Uploadcare CDN supports only image files, only image files is allowed.
{% endhint %}

![](<../.gitbook/assets/ac 7.png>)  :  This will allow you to update any of the below task fields.

* Project : This will transfer task from current project to new selected project
* Sprint
* Resource (User) : This will update **TaskOwner** of the task to selected User
* Module
* Type
* Priority



### Operations

#### Change Workflow

To change the workflow state of the task, use the left section of Action Button panel as specified in [Action Button](task-view.md#action-button-panel-operations) Section.

#### Add New comment

* To add new comment in Task Activity, first enter your comment in the text box under the **Activity** section on the Task View.
* Once you added your comment, Click Add.

#### Add file attachment

* To add file attachment in Task, click attachment button from the right section of action button panel. A below popup will open.

<figure><img src="../.gitbook/assets/Task view attachment popup.jpg" alt=""><figcaption></figcaption></figure>

* In this popup window, if you want to display any comment along with your popup file, enter your comment in text-box.
* Click on **Choose File** button and select the file attachment from your system.
* Click Send.
* Refresh the Task View using Refresh button from Action button panel and verify if new attachment is getting displayed in Activity timeline. These attachments will also get listed in **Attachment** section on the Right side.



#### Open attachments

You can find attachments in Activity timeline or in **Attachment** section on the Right side.

* To open any attachment, you can click on the attachment button in timeline or click on the attachment from Attachment section on the right. This will open respective attachment in new tab.

<figure><img src="../.gitbook/assets/Attachment open.jpg" alt=""><figcaption></figcaption></figure>

#### Update Task Fields

You can update task fields of the the task by using **Edit** button from Action button panel.

* Click on **Edit** button from Action button panel. A popup with the list of drop downs will open.

<figure><img src="../.gitbook/assets/Task View edit popup.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
As Resources (Users), Sprint, Module , Type & Priority are mapped with Project Level; Selection of the Project first is necessary to fetch its respective items.
{% endhint %}

* Select appropriate project from Project drop down.

{% hint style="warning" %}
**Note:**

* If you selected any different project other than the current project to which task is mapped, it will get migrated to that other project upon update.
* To update any other field apart from project, select the project with which task is currently mapped.
{% endhint %}

* Once you selected the project, other drop downs will get populated with appropriate Users, Sprints and other assets mapped with selected project.
* If you want to update only some of the fields of task,\
  select new values from the those drop downs only. No need to select values from other drop downs.&#x20;

> Example:
>
> If you want to update only Module and Sprint of the task, you will need to select new values from Module ad Sprint drop downs.

* Once you selected new values, click Send.
* Next, refresh the view using Refresh button from Action button panel and verify your updates.

#### Assign task to different user

* Click on **Edit** button from Action button panel. A popup with the list of drop downs will open.
* Select appropriate project , which is mapped with the user you want to assign the task.
* Once all the assets from selected project got populated, select the desired user from Resource drop down.
* Click Send. &#x20;
