# Edit Page Properties

## 01. Page Design

### SubmitButtonText

Allows user to name the submit button.

![](<../../../.gitbook/assets/Edit Page Properties SubmitButtonText.png>)



## 02. General

### Redirect To After Update

Allows user to set the page to navigate the browser to, after updating a record.

![](<../../../.gitbook/assets/Edit Page Properties Redirect To After Update.png>)

### Action After Update

Enables user to write a **PHP** statement that will be executed after updating a record.

![](<../../../.gitbook/assets/Edit Page Properties Action After Update.png>)

### Action Before Update

Enables user to write a **PHP** statement that will be executed before updating a record.

![](<../../../.gitbook/assets/Edit Page Properties Action Before Update.png>)

### MessageAfterUpdate

Allows user to enter a message that will be displayed after the data have been updated.

![](<../../../.gitbook/assets/Edit Page Properties MessageAfterUpdate.png>)

### Mail Action Settings

{% hint style="warning" %}
Make sure you have configured the mail settings. if you haven't, click the **Mail Settings** button; On the popup window, click the email tab and configure the mail settings.
{% endhint %}

![](<../../../.gitbook/assets/Edit Page Properties Mail Action Settings.png>)

**SendMail**: When set to `True` sends a mail when a record is updated.

**Mail Title**: Enables user to set the mail title also know as the subject of the mail.

**Mail Body**: Enables user to set a message that will be sent.

**ReceipientEmail**: Enables user to set the email that would receive the notification when a record is updated.



## 03. Page Components

### Load Indicator Settings

![](<../../../.gitbook/assets/Edit Page Properties Load Indicator Settings.png>)

* **IndicatorType**: Allows user to choose the type of loader that will be used.
* **IndicatorColor**: Enables user to set the color of the loader.
* **IndicatorSize**: Enables user to set the size of the loader .
* **IndicatorPosition**: Allows user to set the position of the loader on the screen.
* **IndicatorText**: Allows user to add a text that will appear along side the loader.



## Misc

### FormLayoutType

Enables user to set how the **edit page** form should appear.

![](<../../../.gitbook/assets/Edit Page Properties FormLayoutType.png>)

### ServerSideValidation

If set to `True` enables server side form validation and if `False`, disables server side validation.

![](<../../../.gitbook/assets/Edit Page Properties ServerSideValidation.png>)
