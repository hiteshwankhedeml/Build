# Guideline for UI Automation

* Whenever the DOM is changes in the provider application, you must capture it by clicking the capture button in the recoding widget
* The wait activity is required between consecutive clicks
* The clicks activity performs click asynchronously
* Effect of screen resolutions on the UI automation recorder
* The UI automation recorder works best with 100% DPI resolution
* It also works fine with other resolution scales for most windows application
* However, in a few applications, the UI automation framework gives the wrong element based on the mouse pointer, and this might interrupt the bot execution
* Therefore, its recommended to use the recorder for UI automation with a 100% DPI resolution

