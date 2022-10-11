# Range Field

![](<../../.gitbook/assets/Range Field.png>)

## 01. Data Bind

### FieldName

Allows user to select the field in a database table by which the range field will filter the records&#x20;

### DoubleRange

When set to `True`, makes the range field double and when set to `False` makes it a single range field.

### SingleRangeComparator

Use to filter the type of data or record from database needed to be displayed .

e.g "<=" 1000 : Queries database for data value which is **less** or **equal** to 1000. ">=" 1000 : Queries database for data value which is **greater** or **equal** to 1000

### MinValue

This is the minimum value for the range, allow user to set minimum value for the range. Example: 0

### MaxValue

This is the minimum value for the range, allow user to set minimum value for the range. Example: 100

### LabelPrefix

This is the name attached to the **MinValue** and **MaxValue**  of a range button. This comes before the value

### LabelSuffix

This is the name attached to the **MinValue** and **MaxValue**  of a range button. This comes after the value&#x20;

### ValueStep

Allows user set the range button movement, user defines the value limit by which the range moves between two values&#x20;

### MaxInterval

This is the maximum value for the range, allows user to set maximum value **in between** a range.&#x20;

### MinInterval

This is the minimum value for the range, allows user to set minimum value **in between** a range.&#x20;

### DefaultSelected

This is the initial range of value that will be displayed at the load of the page



## 02. Component Design

### Header Title

Allows user give a name to the the range input

### ShowLabel

When set to true, displays the range values beneath the range rule, when set to false, value does not display

### FilterTag

Allows user to name the tag of the filtered result after range has been selected and filtered

### WrapperClass

This is where user adds custom class name created, to be applied to the range field
