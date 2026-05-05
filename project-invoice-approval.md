# Project - Invoice Approval

* Create Project ⇒ Create Build Process
* Create Data Type
  * Name
  * Date
  * Filepath
* Create Data Type ⇒ To hold information for approval
  * ExtractedData ⇒ email, amount, course name, date
* Create Document Template
  * Create New Template
  *

      <figure><img src=".gitbook/assets/{E5B66BD8-EDF3-4407-8585-07093F71A3A9}.png" alt=""><figcaption></figcaption></figure>

      <figure><img src=".gitbook/assets/{9F22A2D7-71EA-45B9-B365-6554D3A1C809}.png" alt=""><figcaption></figcaption></figure>
* **SDK will get added, and we can also see that dependencies gets added**
* Annotate the document
* Add Automation Step
  * Add Extraction&#x20;
  * Map the fields coming from Extraction into our custom data types
  * Log&#x20;
  *

      <figure><img src=".gitbook/assets/{E1F8CDB2-CE62-45F5-B021-CF6C47B2F835}.png" alt=""><figcaption></figcaption></figure>
* Test the Automation by passing the file path
* Add condition step ⇒ if data matches then send for approval
*

    <figure><img src=".gitbook/assets/{331B796D-4126-4194-ABC9-E4176E6D05B4}.png" alt=""><figcaption></figcaption></figure>
*
