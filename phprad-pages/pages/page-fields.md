# Page Fields

## List page field

List is used for listing records from a database, list page contains five fields

![](<../../.gitbook/assets/ListPage Fields.png>)

* **Output** -**>** check the box pertaining to a particular field to display on the list page
* **Field name** -**>** Includes names of the fields as is from database and could be edited at the field properties section to suit user's project requirement
* **Group ->** Used to group records in a database together based on **`fieldname`**
* **Search ->** Used to select **data** to be displayed when end user searches
* **Search type ->** Active when search is selected, can used to select the type of search queries you want to make when end users search on an application

### Custom Field Expression

![](<../../.gitbook/assets/Custom Field Editor.png>)

This allow users to set a custom field that does not exist in the database table, that will be displayed as part of the fields in the **List Page**. This fields also gets all properties as your other Database column fields. You can read more about **MySQL functions** [Here](https://dev.mysql.com/doc/refman/8.0/en/functions.html).

**Field Expression->** The **Field Expression** enables users to use functions that are available in **MySQL** to format fields and use the result on the field being created. _E.g If we have two fields called **firstname** and **lastname** in our database table then the function **CONCAT(firstname, " ",lastname)** will result in a string that looks like this e.g **Williams Johnson**_.

**Field Alias->** **Field Alias** is the name you want **PHPrad** to reference that fields, that is, its virtual column name also known as the variable used to access its data. This name should be unique and it shouldn't contain spaces and special characters.

**Display Label->** The **Display Label** is the name that will be displayed on the List Page to help end-users understand what kind of data is displayed in it column.

## View page field

View is used for viewing a specific records from a database, view page contains **three** fields

![](<../../.gitbook/assets/View Page Fields.png>)

* **Output** -**>** check the box pertaining to a particular **field** to display on the **view page**
* **Field name** -**>** Includes names of the fields as is from database and could be edited at the field properties section to suit user's project requirement
* **Aggregate->** Used to choose the type of **function** to be applied in a current field.

### Custom Field Expression

![](<../../.gitbook/assets/Custom Field Editor.png>)

This allow users to set a custom field that does not exist in the database table, that will be displayed as part of the fields in the **View Page**. This fields also gets all properties as your other Database column fields. You can read more about **MySQL functions** [Here](https://dev.mysql.com/doc/refman/8.0/en/functions.html).

**Field Expression->** The **Field Expression** enables users to use functions that are available in **MySQL** to format fields and use the result on the field being created. _E.g If we have two fields called **firstname** and **lastname** in our database table then the function **CONCAT(firstname, " ",lastname)** will result in a string that looks like this e.g **Williams Johnson**_.

**Field Alias->** **Field Alias** is the name you want **PHPrad** to reference that fields, that is, its virtual column name also known as the variable used to access its data.This name should be unique and it shouldn't contain spaces and special characters.

**Display Label->** The **Display Label** is the name that will be displayed on the List Page to help end-users understand what kind of data is displayed in it column.

## Add page field

Add page is used for creating a new page for adding new records to a database

![](<../../.gitbook/assets/Add Page Fields.png>)

* **AddPage ->** check box to generate page for a particular field
* **EditPage ->** check box to generate page for a particular field
* **FieldName ->** Displays already created fields

{% hint style="info" %}
Changes made in **`Add page field`** automatically applies to the **`Edit page`** field and any changes made in the edit page field also applies to **`Add page field`** section automatically.
{% endhint %}

## Delete page

Delete page is not a detail page, but a default page button that displays on List and View page.

##
