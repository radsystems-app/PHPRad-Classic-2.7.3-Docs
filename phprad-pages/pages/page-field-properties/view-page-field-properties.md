# View Page Field Properties

### **Display Type**

Allows user to select the type of data from a **field** to be displayed

![](<../../../.gitbook/assets/View Page FieldProperties DisplayType.png>)

1. **Plain Text:** Select to display normal text
2. **Image:** Select to display images
3. **Custom:** Select to add a custom code

### **Sortable**

Enables data in a particular field to be sorted when selected

![](<../../../.gitbook/assets/View Page FieldProperties Sortable.png>)

* **True:** Select true to make field sortable
* **False:** Select false to make field non-sortable&#x20;

### **Field Link**

Used to link a particular field record to a page

![](<../../../.gitbook/assets/View Page FieldProperties Field Link.png>)

* **`--CurrentRecordDetails--:` ** connects a **field's record** to a **detail page** or **view page**
* **`--CurrentFieldCategory--`:** filters **record** based on the field
* **`--CurrentFieldvalue--`:** Used to link a particular **field data** to a file or an attachment
* **`--CurrentFieldValueSearch--:` ** Used to search current **field**&#x20;
* **`--CurrentFieldMailTo--:` ** Adds **mailto** link to the current field's data
* /`menuexample`/list: used to link the current **field record** or **data** to the **list page**
* **/**`menuexample`**/**add**:** used to link the current **field record** or **data** to the **add page**

### **FormatRecordField**

Allows user to format the field's record data for example; `human_date`, `human_time`, `human_datetime`, `relative_date`, `to_currency('en_US')`, `ucwords`, `ucfirst`, `strtolower`, `strtoupper`, `str_truncate(50,'...')`, `approximate(2)`, `to_number, number_to_words('en')`.

![](<../../../.gitbook/assets/View Page FieldProperties FormatRecordField.png>)

* **human\_date:** convert the current field record to human readable date
* **human \_time:** converts the current field record to human readable time
* **human\_datetime:** converts the current field record to human readable date and time
* **relative\_date:** converts the current field record to relative date for example; few seconds ago
* **to\_currency('en\_US'):** converts the current field record to currency
* **ucwords:** converts the **first lette**r of every word in the current **field** **record** or data to uppercase
* **ucfirst:** converts the first letter of every string in the current field record to uppercase
* **strtolower:** converts the current field record to lowercase
* **strtoupper:** converts the current field record to uppercase
* **str\_truncate(50,'...'):** intercepts the length of data in the current field record, to the specified value &#x20;
* **approximate(2):** Approximates data in the current field record according to specified value
* **to\_number:** formats the data in a current field record. For example: **1988665545 to 1,988,665,545**&#x20;
* **number\_to\_words('en'):** formats a given data in a current field record to words. For example: 1 2 3 4 to one two three four

### **FieldHeaderIcon**

Adds an icon to the current field title, there several icons to choose from

![](<../../../.gitbook/assets/ListPage ColumnWidthOrClass.png>)



### **ColumnWidthOrClass**

Allow you to define a fixed or dynamic column width or a custom class.

![](<../../../.gitbook/assets/View Page FieldProperties ColumnWidthOrClass.png>)

* **Fixed:** Here you define a fixed width using the **`CSS`** measurements. For example; 1px
* **Dynamic:** Here you define the with in percentage For example; 5%
* **Custom:** form You add your custom class by adding double hyphen to the beginning and ending of your class name in the field. For example; --customclassname--

### **Display Label**

Allows user to input or edit each list field title or name.

![](<../../../.gitbook/assets/View Page FieldProperties Display Label.png>)

### **Master Detail Relation**

Set detail relationship of the field record

![](<../../../.gitbook/assets/View Page FieldProperties Master Detail Relation.png>)

![](<../../../.gitbook/assets/Master Detail Relation.png>)



#### Master table

* Master table: Maintains the current database table name&#x20;
* Master Field: Enables user select the value that will query the detail Table

#### Detail Table

* Detail Table: This is the field that contains the value to be used for query on the **`Details Page`**
* Detail Field: Contains the data or record that will be used to compare against the **`Master Field`** record/ table

#### **Detail Page Display**

Allows user to choose how data will presented on the Master Detail page

* **Detail page:** Allows user to select how data will appear (List/ View)
* **Page Display Style:** Choose how the view page will be present (Modal/ View Page/ Inline)
* **Record Display Text:** This is the text that will be displayed on the column of each field, such that when clicked on will display details in that record

### **ImageResizeDimension**

Allows user to set image size in the current field when display type is set to image. This size can be modified to meet user's need.

![](<../../../.gitbook/assets/View Page FieldProperties ImageResizeDimenssion.png>)

### **Custom Code**

Allows user to provide a custom view code to customize a current field view.

![](<../../../.gitbook/assets/View Page FieldProperties CustomCode.png>)
