# Delete Page Properties

## 01. General

### Record Delete Settings

Allows user to configure how deleting **Records** or **Data** will be handled.

![](<../../../.gitbook/assets/Delete Page Properties Record Delete Settings.png>)

#### Delete Record From Database

If selected, records will be deleted from the database when the delete button is clicked.

#### Update Table Field Value

When selected, it is flags a record as deleted or as any string entered in the **`Update Value`** when the delete button is clicked. This means the data will still be retained in the database.

* **Update Field Name**: This is the database **table field name**, where the flag `deleted` or whatever custom delete flag you choose to use will be stored.
* **Update Value**: Allows user to enter a delete flag, that will be used to flag records as deleted.

### PromptMessageBeforeDelete

Allows user to enter a message that will be displayed to confirm if the delete action should be proceeded with or canceled.

![](<../../../.gitbook/assets/Delete Page Properties Prompt Message Before Delete (1).png>)

### MessageAfterDelete

Allows user to enter a message that will be displayed after the data have been deleted.

![](<../../../.gitbook/assets/Delete Page Properties MessageAfterDelete.png>)

### Redirect To After Delete

Allows user to set the page to navigate the browser to, after deleting a record.

![](<../../../.gitbook/assets/Delete Page Properties Redirect To After Delete.png>)

### Action After Delete

Enables user to write a **PHP** statement that will be executed after deleting a record.

![](<../../../.gitbook/assets/Delete Page Properties Action After Delete.png>)

### Action Before Delete

Enables user to write a **PHP** statement that will be executed before deleting a record.

![](<../../../.gitbook/assets/Delete Page Properties Prompt Message Before Delete.png>)



## 02. General

### Mail Action Settings

{% hint style="warning" %}
Make sure you have configured the mail settings. if you haven't, click the **Mail Settings** button; On the popup window, click the email tab and configure the mail settings.
{% endhint %}

![](<../../../.gitbook/assets/Delete Page Properties Mail Action Settings.png>)

**SendMail**: When set to `True` sends a mail when a record is deleted.

**Mail Title**: Enables user to set the mail title also know as the subject of the mail.

**Mail Body**: Enables user to set a message that will be sent.

**ReceipientEmail**: Enables user to set the email that would receive the notification when a record is deleted.

