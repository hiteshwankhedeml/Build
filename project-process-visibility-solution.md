# Project - Process Visibility - Solution

* Create Project ⇒ Create Process
* Create form trigger ⇒ Design form ⇒ Input order number on screen
* Add action&#x20;
* Creation destination variable
* Map input
* Create custom variable
* Output we will map to this custom variable
* Create a data type for Approver
* Create decision, determine approver based on sales org
* Create rule for this
*   In the process, add attributes ⇒ This will be used in visibility

    <figure><img src=".gitbook/assets/{AA53D594-5231-485A-8FC1-2000C20E33A4}.png" alt=""><figcaption></figcaption></figure>
* Now create a visibility scenario
*   Add process here,&#x20;

    <figure><img src=".gitbook/assets/{AE64CEC5-4969-452E-8357-E1F28A109C09}.png" alt=""><figcaption></figcaption></figure>
*

    <figure><img src=".gitbook/assets/{A68729D8-EA34-4737-B702-A10542B3CCDE}.png" alt=""><figcaption></figcaption></figure>
* Go into workzone
* Content Manager ⇒ Process trigger
* Create a local copy of it
* GIve Application tile name
* In navigation, enter uri ⇒ this we will be getting from form of deployed process
* Similarly we also Visibility scenario ⇒ copy it
* Enter scenario id ⇒ this we will get from control tower
*   We also need to schedule job (Need paid plan) or do process data then only data will refresh in visibility

    <figure><img src=".gitbook/assets/{9DC68D09-71F2-4BE5-BCF3-AF10A7D566EC}.png" alt=""><figcaption></figcaption></figure>
* Add this tiles in Catalog
* Add in everyone role
*

    <figure><img src=".gitbook/assets/{5DB58875-322F-42BD-B0F0-E99935B8E9FB}.png" alt=""><figcaption></figcaption></figure>
*

    <figure><img src=".gitbook/assets/{8A7BDFD4-9B46-4954-AC1C-1A328D1328F5}.png" alt=""><figcaption></figcaption></figure>
