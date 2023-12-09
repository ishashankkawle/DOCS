---
description: This window is used to update Role of user in system.
---

# Role Assignment

You can navigate to Role Assignment window by clicking on **Role Assignment** tab in left navigation panel :one:.

{% hint style="warning" %}
**Note:**&#x20;

If you are not able to find **Role Assignment** tab on navigation panel, you do not have access to perform role assignment. Please reach out to Administration to get the necessary access.
{% endhint %}

<figure><img src="../../.gitbook/assets/Role Assignment window.jpg" alt=""><figcaption></figcaption></figure>

You can update Role of any user in system by using **Role Assignment** card.



### Update Role of User

* To update the role of the user select the project (or any one of project) to which user belongs.

{% hint style="info" %}
Project dropdown will contain list of project which are assigned to user who is performing Role Assignment. That means user who is performing role assignment can update role of user which belongs to same project which is assigned to user who is performing role assignment.
{% endhint %}

* Once you selected the project, next drop-down will get populated. Select the user from drop-down of which you want to update the role.

{% hint style="info" %}
User / Resource drop-down will contain list of users who have `small`role than the user who is performing role assignment.
{% endhint %}

* Once you selected the user, next drop-down will get populated with all the possible roles which can be applied to user.

{% hint style="info" %}
This is because user who is performing role assignment, can only assign the roles which is lower than his/her own role and higher than current role of selected user.&#x20;

```sql
SELECT "RoleId" , "RoleName" , "SecurityLevel" FROM role_master WHERE "SecurityLevel" > (
SELECT "SecurityLevel" FROM user_master WHERE "UserId" = <USER_ID OF CURRENT USER>
) AND "SecurityLevel" < (
SELECT "SecurityLevel" FROM user_master WHERE "UserId" = <USER_ID OF SELECTEd USER>
)
```

\
**Note:** Instead of this behavior, User should be able to assign any Role **`small` than the role of user who is performing role assignment**  &#x20;
{% endhint %}

* Once appropriate role is selected, click **Send**.

