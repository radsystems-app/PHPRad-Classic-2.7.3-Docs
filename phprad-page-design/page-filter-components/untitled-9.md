# Nav Filter Menu

![](<../../.gitbook/assets/Nav Menu.png>)

## 01. Data Bind

### FieldName

Allows user to select the field in a database table by which the **Nav Filter Menu** will filter the records&#x20;

### SingleFilter

When set to **`True`**, filters only by the current **Nav Filter Menu** component, when set to **`False`**, filters by multiple filter components

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

### Header Title

This allows user to give the Nav Menu a defined name

### FilterTag

Allows user to name the tag of the filtered result after **Nav Filter Menu** have been selected and filtered&#x20;

### Reset Item Text

Shows as part of the drop down list, when selected, resets the filtered records to default state

### WrapperClass

Allows user to set the class for wrapping the **drop down** menu

### Justify

Centers records or the contents in the **Nav Filter Menu** component

### Fill



### Vertical

Arranges **Nav Filter Menu** component in a vertical order when set to **`True`**

### NavType

Allows user to choose the type of **Nav Filter Menu** component to be used
