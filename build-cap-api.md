# Build CAP API

1. Create a new dev space for full stack development
2. Go to Projects folder
3. F1 ⇒ Explore and install generator ⇒ Search Anubhav training generator
4. Run generator ⇒ anubhav-buildcap generator
5. terminal ⇒ yo generator-buildcap
6. cds watch ⇒ to test the API locally ⇒ in tester.http we can run the APIs
7. To deploy the app to cloud ⇒ npm run cloud ⇒ this will create mta\_archive folder
8. Right click on folder ⇒ Deploy
9. It will ask for login and then it will deploy
10. We can open BTP cockpit ⇒ SubAccount ⇒ Dev Space ⇒ Check the deployed App
11. Subaccount ⇒ Destination ⇒ Create ⇒ Add URL and save
12. In our project there is spec.json ⇒ this will be needed
13. Control tower ⇒ Destination ⇒ Import the destination
14. Create action project ⇒ use spec.json for this
15. This action project can be used in Build
