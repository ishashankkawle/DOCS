---
description: You can perform change review on any task in Verification page.
---

# Verification

Whenever you assign any task to a developer, a task gets created with workflow status as `New`

Whenever developer finalizes their changes from their end, they move task to either `Self_Commit` or `Self_Delete` workflow state.

Once developer moved any of the task that you assigned to them to Self\_Commit or Self\_Delete state, it will get listed under the Verification window for you to verify and finalize the updates.

You can navigate to Verification page by clicking Verification tab in the Assignment and Verification window :one:.

<figure><img src="../../.gitbook/assets/Verification page.jpg" alt=""><figcaption></figcaption></figure>

Once you navigated to verification page, you will see two tables.

Table on the left will list all the tasks assigned by you to different user and in `Self_Commit` state :two:.

Table on the left will list all the tasks assigned by you to different user and in `Self_Delete` state :three:.

Each table will have its own Action Button panel for quick task updates :one:. These action buttons will also be available on individual task level :two:.

<figure><img src="../../.gitbook/assets/Verification Action Buttons.jpg" alt=""><figcaption></figcaption></figure>

### Completing the task

{% hint style="warning" %}
**Note:**

* Once task is moved to `Complete` or `Delete` state, you will not be able to access the task.
{% endhint %}

<figure><img src="../../.gitbook/assets/Verification Complete task.jpg" alt=""><figcaption></figcaption></figure>

* If you want to move any individual task to `Complete` state, you can directly move it by clicking task level Complete button :one:.
* If you want to move multiple / all tasks to Completed state at once, select the tasks using the checkbox :two:.
* Once selected, click on the Complete button from table level Action button panel :three:.



### Deleting the task

<figure><img src="../../.gitbook/assets/Verification task delete.jpg" alt=""><figcaption></figcaption></figure>

* If you want to move any individual task to `Delete` state, you can directly move it by clicking task level Delete button :one:.
* If you want to move multiple / all tasks to Deleted state at once, select the tasks using the checkbox :two:.
* Once selected, click on the Delete button from table level Action button panel :three:.



### Reverting the Task

If you are not  satisfied with the changes on task, you can revert the task. Reverting the task will change the workflow status of task from either `Self_Commit` or `Self_Delete` to `In_Progress` .

This workflow change will remove that task from your verification window and will displayed in TaskBoard of the user to which that task was assigned to.

<figure><img src="../../.gitbook/assets/Verification revert task.jpg" alt=""><figcaption></figcaption></figure>

* If you want to revert any individual task, you can directly revert it by clicking task level Revert button :one:.
* If you want to revert multiple / all tasks to Completed state at once, select the tasks using the checkbox :two:.
* Once selected, click on the Revert button from table level Action button panel :three:.



### Open Task details

You can open any individual task by clicking task level Open button.

<figure><img src="../../.gitbook/assets/Open task.jpg" alt=""><figcaption></figcaption></figure>



### Refreshing tables

You can refresh Verification Self\_Commit or Verification Self\_Delete table by clicking Refresh button from Action button panel above the table. This will reload the respective table with reloading entire page.

<figure><img src="../../.gitbook/assets/Verification Refresh.jpg" alt=""><figcaption></figcaption></figure>

