# Multi-Choice List Field

![](<../../.gitbook/assets/Multi Choice List Field.png>)

## 01. Data Bind

### FieldName

Allows user to select the field in a database table by which the **Multi-Choice List Field** will filter the records&#x20;

### SingleFilter

When set to **`True`**, filters only by the current single **Multi-Choice List Field** component, when set to **`False`**, filters by multiple filter components

### Datasource

Allows user to select where to pull data from; from a database, from a table etc&#x20;

* **Quick List:** Allows user select list of preferred data, and add more if necessary&#x20;
* **Enter Value:** Allows user to enter the values in a field and select preferred label&#x20;
* **Data Table:** Enables user to select table, its value and label&#x20;
* **Custom SQL:** Allows user to enter their custom query&#x20;
  * Query Builder&#x20;
    * **Designer**: Allows user to select tables, fields, sort, sort order, group, aggregate, operand, comparator and value that will be used to build queries&#x20;
    * **Code**: This is where you view generated queries&#x20;
    * **Result**: Allows user to observe query results and apply changes in the designer section if needed

## 02. Component Design

### Label

This is the title of the Multi-Choice List Field component

### CheckboxClass

This is where user adds custom class name created, to be applied on the **checkbox**

### WrapperClass

This is where user adds custom class name created, to be applied on the **Multi-Choice List Field**

## Misc

### Filter Tag

Allows user to name the tag of the filtered result after **Multi-Choice List Field** have been selected and filtered
