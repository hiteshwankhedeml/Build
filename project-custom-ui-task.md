# Project - Custom UI Task

* Create a Process
* Click on Import Form
* Give the Application Id of form created and id
*

    <figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>
* Create Data Type HiringInfo
  * name
  * employerName
  * workexperience
  * email
  * country
  * budgest
  * skills ⇒ List of string
  * comment
* Add Variables ⇒ Process Input
* Create API trigger
* Add Approval Form ⇒ Here our custom form will be visible
* On submit, it will go for approval
*

    <figure><img src=".gitbook/assets/{2E3EA7ED-8A26-4962-96C0-5745491B6710}.png" alt=""><figcaption></figcaption></figure>
* Save, Release, Deploy
* From Control tower, get the API and trigger by passing the payload
* When triggered, candidate will 1st get the form to fill in his My Inbox
