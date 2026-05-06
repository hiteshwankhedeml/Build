# Steps

**Setting up cloud connector:**

1. Download SAP JVM from hana tools
2. Download Cloud connector from hana tools
3. Place the sapjvm in c drive inside java folder
4. Install cloud connector
5. Note the port number
6. Make sure to select the sap jvm folder during installation
7. Do localhost:8443 this will open cloud connector
8.

    <figure><img src=".gitbook/assets/{BB6218C3-313C-460D-A122-700FB636991C}.png" alt=""><figcaption></figcaption></figure>
9. Default credentials is Administrator/Manager



**Connect to SAP BTP:**

1.  Enter sub account details like account, username, password etc

    <figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>
2. Once connected, its visible in cloud connector in BTP

*

    <figure><img src=".gitbook/assets/{96FCCF4C-A30B-4831-AC9A-0639AF0269D0}.png" alt=""><figcaption></figcaption></figure>



**Connect SAP to On premise system:**

1. You need to provide IP, port etc, Same way we can do RFC connection also
2.  You also need to provide virtual host

    <figure><img src=".gitbook/assets/{4D491D4E-E0DD-4DAF-9C1B-7EE0D52591F6}.png" alt=""><figcaption></figcaption></figure>


3. This virtual host will be used in destination
4.

    <figure><img src=".gitbook/assets/{9853620A-E4FF-4CC1-9B0C-EC3CF8E2F71A}.png" alt=""><figcaption></figcaption></figure>


5. Configure which resource we want to expose, like odata path
6.

    <figure><img src=".gitbook/assets/{5572E29A-32F9-4EF8-9377-AB36EF8F4DBE}.png" alt=""><figcaption></figcaption></figure>



**Create Destination:**

* Subaccount ⇒ Connectivity ⇒ Destinations
* Add property sap.processautomationenabled = true
* WebIDEEnable= True
*

    <figure><img src=".gitbook/assets/{D49D66FB-5114-46F9-A115-D41B03846D88}.png" alt=""><figcaption></figcaption></figure>
