---
description: Update the security permissions for the roles
---

# Security

Once you created the role in system, you can update security permissions related to that role in Security window.

<figure><img src="../../.gitbook/assets/Security window.jpg" alt=""><figcaption></figcaption></figure>

You can navigate to Security window by clicking **Security** tab in left navigation panel :one:.

{% hint style="warning" %}
**Note:**&#x20;

If you are not able to find **Security** tab on navigation panel, you do not have access to modify security permissions of roles. Please reach out to Administration to get the necessary access.
{% endhint %}

You can use **Role Security Permissions** card to modify permissions of specific role



### Modify Security Permissions

* To modify security permissions for specific role, first select that role from Role drop-down menu.

{% hint style="info" %}
Role drop-down menu will contain all the roles in system without any filter.
{% endhint %}

* Next, enable the switches of permissions which you want to assign to user. Please refer below mapping table for better understanding. Once everything is finalized, click **Send**.



### Permission to Window Mapping

<table data-full-width="true"><thead><tr><th>Description</th><th>Permission Name</th><th>Screens</th><th>Comments</th></tr></thead><tbody><tr><td>N/A (All switches on screen are off)</td><td><pre><code>PERM_NO_ACCESS
</code></pre></td><td>N/A</td><td>This is the default permission which get assigned to all users when they get created in system</td></tr><tr><td>Can create new project and its assets</td><td><pre><code>PERM_ALL_PROJECT
</code></pre></td><td><ul><li>Project</li><li>Assets</li><li>Sprint</li></ul></td><td></td></tr><tr><td>Can create new Tasks in project</td><td><pre><code>PERM_ALL_TASK
</code></pre></td><td><ul><li>Dashboard</li><li>Task</li><li>TaskBoard</li><li>Assignment &#x26; Verification</li></ul></td><td></td></tr><tr><td>Can manage User Accounts , User Allocations &#x26; User-Role management</td><td><pre><code>PERM_ALL_USER
</code></pre></td><td><ul><li>Users</li><li>User Management</li><li><p>Role Assignment</p><ul><li>Delete User</li></ul></li></ul></td><td></td></tr><tr><td>Can view Reports and Insights</td><td><pre><code>PERM_ALL_REPORT
</code></pre></td><td><ul><li>Insights</li></ul></td><td></td></tr><tr><td>Can create new Roles and Manage Role Security permissions</td><td><pre><code>PERM_ALL_ORG_SECURITY
</code></pre></td><td><ul><li>Role</li><li>Security</li></ul></td><td><ul><li>This is Organisation Level access which can be used to get access to other screens as well.</li><li><strong>Please make sure that this access is only assigned to ADMIN user of the system only</strong>.</li></ul></td></tr></tbody></table>
