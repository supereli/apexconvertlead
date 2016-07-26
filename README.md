# apexconvertlead

This is an Apex class with a corresponding test class that enables SFDC lead conversion from the Salesforce REST API

To deploy this, you must have Salesforce administrator privilege:

1 - Create classes in SFDC Sandbox environment
2 - Update test class with valid AccountId, OwnerId and LeadId
3 - Run tests in SFDC development console
4 - Test the function from the SFDC sandbox REST API
5 - Modify the test class with valid AccountId, OwnerId and LeadId from production environment
6 - Ensure sandbox environment has proper access to send change set to production
7 - Add restleadconvert and restleadconverttest to change set and deploy to production
8 - Test REST API in production by converting 1 lead
