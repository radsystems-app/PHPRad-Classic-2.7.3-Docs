# Date Field

![](<../../.gitbook/assets/Date Field.png>)

## 01. Data Bind

### FieldName

Allows user to select the field in a database table by which the **Date field** will filter the records&#x20;

### SingleFilter

When set to **`True`**, filters only by the current single date component, when set to **`False`**, filters by multiple filter components

### DateMode

* Single: Allows for the selection of a single date
* Multiple: Allows for selection of multiple date to be filtered by
* Range: Allows for filtering of database records between two selected dates

### Comparator

Used to validate the end-user input against the records in the database

### Selection Type

* **DateOnly:** Displays only date component  when selected
* **TimeOnly:** Displays only time component when selected
* **DateTime:** Displays both date and time component when selected



## 02. Component Design

### PLaceholder

Allows user to enter a default text in the date component when there's no input

### Label

This is the title of the Date field component

### InlineDisplay

When set to **`True`**, displays the date component in the current page, when set to **`False`** does not display in line

### FilterTag

Allows user to name the tag of the filtered result after **date** has been selected and filtered

### WrapperClass

This is where user adds custom class name created, to be applied to the **date** field
