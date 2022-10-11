# Dropdown Menu

![](<../../.gitbook/assets/DropDown Menu.png>)

## 01. Data Bind

### FieldName

Allows user to select the field in a database table by which the **Dropdown Menu** will filter the records&#x20;

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

### SingleFilter

When set to **`True`**, filters only by the current **Dropdown Menu**  component, when set to **`False`**, filters by multiple filter components

### Comparator

Used to validate the end-user input against the records in the database

### FilterTag

Allows user to name the tag of the filtered result after **Dropdown Menu** have been selected and filtered from the database

## 02. Component Design

### Reset Item Text

Shows as part of the drop down list, when selected, resets the filtered records to default state

### Button Text

Allows user to set or name the **drop down** menu button

### ButtonIcon

Allows user to select an icon to be displayed on the **drop down** menu button

### ButtonClasses

Allows user to selected to class(s) or style to be applied on the **drop down** menu button

### WrapperClass

Allows user to set the class for wrapping the **drop down** menu
