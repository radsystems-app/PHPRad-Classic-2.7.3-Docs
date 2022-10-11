# List Page Properties

## 01. Page Design

![](<../../../.gitbook/assets/List Page Properties Page Design.png>)

### PageTitle

This enables users to set a preferred title name for a page.

![](<../../../.gitbook/assets/List Page Properties PageTitle.png>)

### DisplayType

Choose between Table List or Custom view in other to set how records are displayed on a particular page.&#x20;

![](<../../../.gitbook/assets/List Page Properties DisplayType.png>)

### ReloadOnNavigate

If set to `True` reloads and clears whatever data the page holds on navigation. This is useful in a single page application like [vue.js](https://vuejs.org)

![](<../../../.gitbook/assets/List Page Properties ReloadOnNavigate.png>)

### EmptyRecordMessage

This is the message you want users to see when the page record is empty.

![](<../../../.gitbook/assets/List Page Properties EmptyRecordMessage.png>)



## 02. Default Query Configuration

![](<../../../.gitbook/assets/List Page Properties Default Query Configuration.png>)

### Join

This helps in retrieving data from two or more database tables.

![](<../../../.gitbook/assets/List Page Properties Join.png>)

#### Select Tables

This displays the list of tables available in your database, that will be selected for the join statement.

#### Joined Tables

This are the list of database tables that have been selected for the join statement.

#### Join Condition

* **Join Type**: Enables user to chose the type of joining that will take place between the tables.
  * `INNER JOIN`: This is used to return rows from both tables that satisfy the given condition.
  * `LEFT JOIN`:  This returns all the rows from the table on the left even if no matching rows have been found in the table on the right. **Where no matches have been found in the table on the right, NULL is returned.**
  * `RIGHT JOIN`: This returns all the columns from the table on the right even if no matching rows have been found in the table on the left. **Where no matches have been found in the table on the left, NULL is returned.**
* **Left Field**: Enables user to select a table field for the **Join Type** left field.
* **Right Field**: Enables user to select a table field for the **Join Type** right field.

#### Sample SQL statement structure

This displays a sample of the generated **SQL** statement based on the **Join Condition** configuration.

### Where

Enables user to enter the **Where** condition. _e.g `id=1 AND cus_id=1`_

> &#x20;A `WHERE` clause in [SQL](https://en.wikipedia.org/wiki/SQL) specifies that a SQL [Data Manipulation Language (DML)](https://en.wikipedia.org/wiki/Data\_Manipulation\_Language) statement should only affect rows that meet specified criteria. The criteria are expressed in the form of predicates.

![](<../../../.gitbook/assets/List Page Properties Where.png>)

### Having

Enables user to enter the **Having** condition. _e.g `sum_of_price > 2000` or `SUM(Amount) > 500`_

> &#x20;A **`HAVING`** clause in [SQL](https://en.wikipedia.org/wiki/SQL) specifies that an SQL [`SELECT`](https://en.wikipedia.org/wiki/Select\_\(SQL\)) statement should only return rows where aggregate values meet the specified [conditions](https://en.wikipedia.org/wiki/Condition\_\(SQL\)). It was added to the SQL language because the [`WHERE`](https://en.wikipedia.org/wiki/Where\_\(SQL\)) keyword could not be used with [aggregate functions](https://en.wikipedia.org/wiki/Aggregate\_function).

![](<../../../.gitbook/assets/List Page Properties Having.png>)

### Order By

Enables user to select the field for the data to be sorted by and if it should be sorted in `ASC`(Ascending order) or `DESC`(Descending order).

> An **`ORDER BY`** clause in [SQL](https://en.wikipedia.org/wiki/SQL) specifies that a SQL [`SELECT`](https://en.wikipedia.org/wiki/Select\_\(SQL\)) statement returns a [result set](https://en.wikipedia.org/wiki/Result\_set) with the rows being sorted by the values of one or more columns.

![](<../../../.gitbook/assets/List Page Properties Order By.png>)

### RecordLimit

Enables the user to limit the number of record to queried.

![](<../../../.gitbook/assets/List Page Properties RecordLimit.png>)



## 03. Page Components

![](<../../../.gitbook/assets/List Page Properties Page Components.png>)

### ActionButtonDisplayStyle

Allows user to choose how to display the action buttons on the table view. Styles are (`Icons`, `Dropdown`).

![](<../../../.gitbook/assets/List Page Properties ActionButtonDisplayStyle.png>)

### DeleteButton

Allows user to add a delete button for deleting records on **List Page**.

![](<../../../.gitbook/assets/List Page Properties DeleteButton.png>)

### EditButton

Allows user to add an edit button for editing records on **List Page**.

![](<../../../.gitbook/assets/List Page Properties EditButton.png>)

### ViewButton

Allows user to add a view button for viewing records on **List Page**.

![](<../../../.gitbook/assets/List Page Properties ViewButton.png>)

### EditButtonText

Allows user to name the edit button.

![](<../../../.gitbook/assets/List Page Properties EditButtonText.png>)

### ViewButtonText

Allows user to name the view button.

![](<../../../.gitbook/assets/List Page Properties ViewButtonText.png>)

### DeleteButtonText

Allows user to name the delete button.

![](<../../../.gitbook/assets/List Page Properties DeleteButtonText.png>)

### ExportButton

Allows user to add an export button for exporting records on **List Page**.

![](<../../../.gitbook/assets/List Page Properties ExportButton.png>)

### ExportButtonText

Allows user to name the export button.

![](<../../../.gitbook/assets/List Page Properties ExportButtonText.png>)

### ImportDataSettings

![](<../../../.gitbook/assets/List Page Properties ImportDataSettings.png>)

#### 01 JSON Import

* EnableJSONImport: Enables user to import a **JSON** file type when set to `True`

#### 02 CSV Import

* EnableCSVImport: Enables user to import a **CSV** file type when set to `True`
* QuoteChar: Allows user to set the type of code character that an imported **CSV** file contains.
* SeparatorChar: Allows user to select the type of data separator the imported **JSON** file contains.

#### Misc

* SaveFile: Enables user to save the file to the server after importing the records to the database.
* UseTransactional: This database concept when set to `True`, allows for a data importation process to be **aborted** when an error is encountered.

### ImportButtonText

Allows user to name the import button.

![](<../../../.gitbook/assets/List Page Properties ImportButtonText.png>)

### ListSequence

When set to `True`, numbers the record sequentially on the page.

![](<../../../.gitbook/assets/List Page Properties ListSequence.png>)

### IncludeCheckbox

When set to `True`, displays a checkbox for each record, allowing for multiple action to be taken on selected records.

![](<../../../.gitbook/assets/List Page Properties IncludeCheckbox.png>)

### Pagination

When set to `True`,  displays a number of records based on user **PaginationSettings**.

![](<../../../.gitbook/assets/List Page Properties Pagination.png>)

### PaginationSettings

![](<../../../.gitbook/assets/List Page Properties PaginationSettings.png>)

When **`Numeric PrevNext` ** is selected, includes a numeric numbering between the Previous and Next buttons in the pagination;&#x20;

When **`PrevNext Only` ** is selected, removes the numeric numbering between the Previous and Next buttons in the pagination.

* **Record Count**: When checked, adds record counting to the page pagination.
* **Page Count**: When checked, adds page counting to the page pagination.
* **Record Limit**: When checked, adds record limiting to the page pagination.
* **Apply Current Settings to All Pages**: when Checked, adds the current pagination settings to all pages.

### SearchField

When set to `True` display the page search field and if set to `False`, hides the page search field.

![](<../../../.gitbook/assets/List Page Properties SearchField.png>)



## 04. Table Design

![](<../../../.gitbook/assets/List Page Properties Table Design.png>)

### WrapperClass

Allows user to set the wrapper class for current page, either a custom class is added by typing or selected from the drop down list.

![](<../../../.gitbook/assets/List Page Properties WrapperClass.png>)

### TableBorderStyle

Allows user to select how the table border should be styled.

![](<../../../.gitbook/assets/List Page Properties TableBoarderStyle.png>)

* **None**: When selected hides the table border.
* **Horizontal**: When selected adds the horizontal table border.
* **Both**: When selected adds both vertical and horizontal borders.

### TableStriped

When set to `True` adds a gray color to the odd number rows in the table. And if `False`, removes the gray color on the odd number rows.

![](<../../../.gitbook/assets/List Page Properties TableStriped.png>)

### TableDark

When set to `True` changes the table color to black and if `False` is selected, sets the table color to white.

![](<../../../.gitbook/assets/List Page Properties TableDark.png>)

### TableCompact

This displays the table in smaller padded cells if set to True but does not compact the table when set to `False`.

![](<../../../.gitbook/assets/List Page Properties TableCompact.png>)

### TableHeaderBackground

This sets the table header color.

![](<../../../.gitbook/assets/List Page Properties TableHeaderBackground.png>)

### TableHeaderTextColor

This sets the table header text color.

![](<../../../.gitbook/assets/List Page Properties TableHeaderTextColor.png>)

### TableHoverable

When set to `True`, adds highlight when the mouse hovers over the table records.

![](<../../../.gitbook/assets/List Page Properties TableHoverable.png>)

### TableResponsive

When set to `True` adds responsiveness to the table, which makes it adjust to different screen size.

![](<../../../.gitbook/assets/List Page Properties TableResponsive.png>)



## 05. Page Modal

![](<../../../.gitbook/assets/List Page Properties Page Modal.png>)

### ModalEdit

When set to True, makes the **Edit Page** display as a modal.

![](<../../../.gitbook/assets/List Page Properties ModalEdit.png>)

{% hint style="info" %}
**Note**: ModalEdit does not support old browsers like **Internet Explorer**.
{% endhint %}

### ModalView

When set to True, makes the **View Page** display as a modal.

![](<../../../.gitbook/assets/List Page Properties ModalView.png>)

{% hint style="info" %}
**Note**: ModalView does not support old browsers like **Internet Explorer**.
{% endhint %}
