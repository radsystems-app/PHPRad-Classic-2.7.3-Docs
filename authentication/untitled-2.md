# Adding User Record Management

Allows user to configure access right on page data for end-users. This means that end-users can only see records they are permitted to see or assigned to.

## Database Table

This displays  the list of tables available in your **Database**. To configure, you have to click on the specific table you want end users to have limited access to. In the image below, it would be **post** database table.

![](<../.gitbook/assets/Settings User Record Management.png>)

We have three **User Roles and Permission;** **Administrator**, **User** and **Staff**. So, we will configure who can **view**, **edit** and **delete** a record on the **post** table.



## Select table field that match user records

The below configurations ensures that users only see data/record they added or was assigned to.

### Posted By Field

This is the field in the current database table that holds the details of the user who created/added the data to the table.

### Assign To Field

This is the field that holds the details of the user who the data or record has been assigned to.

### Match Record By User

Allows user to set the field that a user data from **Posted By Field** or **Assign To Field** will be validated against n the users **Database Table**.

If the **Posted By Field** or **Assign To Field** holds the id of a user, the **Match Record By User** should be set to **id.** this means that, it checks if the end-user currently logged in, and viewing the record matches the user who created it or it was assigned to.



## Allow Other Users With Roles to Access and Manage Records

This Allows user to set what actions (**List**, **Edit** & **Delete**) a specific **User Role** can take on the current page records/data.
