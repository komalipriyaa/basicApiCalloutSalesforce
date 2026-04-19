# basicApiCalloutSalesforce
A sample api integration in salesforce.

endpoint: https://global-warming.org/api/temperature-api
action: GET

Step1: Add the url in the All sites to enable integration to Salesforce with the external System.
* Go to Setup.
* Type 'Remote Site Setting' in the quick find box and click on it.
* Click on 'New Remote Site' button.
* Add the details.
    - Remote Site Name: testAPI_globalWarming
    - Remote Site URL: https://global-warming.org
* Click on 'Save'.
  <img width="2076" height="780" alt="image" src="https://github.com/user-attachments/assets/3ca346b3-dd22-415e-aed5-ad66b84435e8" />

Step2: Write the apex code to make the callout and process the response. - BasicCallout.cls

Step3: Execute the code.
* Go to Developer Console and opn the Anonymous Window.
* Type: BasicCallout.makeCallout();
* Check the 'Open Log' checkbox.
* Click on 'Execute'.

