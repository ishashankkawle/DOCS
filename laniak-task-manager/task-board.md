---
description: Find all tasks assigned to you
---

# Task Board

You can find all tasks assigned to you in TaskBoard window.

You can navigate to TaskBoard window by clicking Search icon on upper navigation bar :one:.&#x20;

{% hint style="info" %}
**Note:**

* Icons in top navigation bar will be displayed even if user has no access to those pages.
* Upon clicking on those icons, if user has no access to that page, an error message will be displayed on screen as below.

<img src="../.gitbook/assets/No Access error.jpg" alt="" data-size="original">
{% endhint %}

{% hint style="warning" %}
**Note:**&#x20;

If you are getting error stating that you do not have access to TaskBoard, please reach out to Administration to get the necessary access.
{% endhint %}

<figure><img src="../.gitbook/assets/Task Board window.jpg" alt=""><figcaption></figcaption></figure>

You can see all tasks assigned to you in main board :two:.

TaskBoard will have action button panel attached to it on top right corner :three:. These action buttons can be used to quickly perform operations on selected task.

TaskBoard will have static adjustable headers columns:four:.  Each column in TaskBoard will have column level filter :five:.

At the bottom of TaskBoard you can see number of displayed items on one page of TaskBoard :six:.  Also you will be able to see and navigate different pages of TaskBoard using page navigation :seven:.

You can see list of tasks wil some of the fields displayed in tables columns as in picture above :eight:. &#x20;

{% hint style="info" %}
* Task in the TaskBoard will be fetched based on `TaskOwner = <UserId of logged in user>`  filter.
* Once all tasks are fetched, they will be filtered only for `New` & `In_Progress` workflow states
{% endhint %}

For performing any operation on TaskBoard, you will need to first select the task from the board. For this purpose, you can use check boxes available for each tasks of table level checkbox

<figure><img src="../.gitbook/assets/Task Board Checkbox.jpg" alt=""><figcaption></figcaption></figure>

* To select all tasks in TaskBoard , check the table level checkbox :one:.
* To select individual task, select the checkbox on the task row :two:.



### Action Button Panel Operations

Once you selected any task, you can use action button panel to quickly update the task.

![](<../.gitbook/assets/ac 1.png>)  :  This will navigate you to [Task Action Window](action-windows/task.md) which will allow you to create new task. This will not update any selected task(s).

![](<../.gitbook/assets/ac 2.png>)  :  This will migrate Task workflow state of any selected task(s) to next workflow state. Below workflow migrations are possible.

<table><thead><tr><th width="209">Current State</th><th>Next State</th><th>Comment</th></tr></thead><tbody><tr><td><code>New</code></td><td><code>In_Progress</code></td><td></td></tr><tr><td><code>In_Progress</code></td><td><code>Self_Commit</code></td><td>Migration from <code>In_Progress</code> to <code>Self_Commit</code> is default behavior</td></tr></tbody></table>

![](<../.gitbook/assets/ac 3.png>)  :  This will move any selected task(s) from `New` or `In_Progress` to `Self_Commit` workflow state.

![](<../.gitbook/assets/ac 4.png>)  :  This will move any selected task(s) from `New` or `In_Progress` to `Self_Delete` workflow state.

![](<../.gitbook/assets/ac 5.png>)  :  This will reload entire TaskBoard table without loading entire view.



***

You can open details or timeline of any task by clicking arrow button on task row as shown below

<figure><img src="../.gitbook/assets/Task Details button.jpg" alt=""><figcaption></figcaption></figure>

This will open Task details in new tab in browser.
