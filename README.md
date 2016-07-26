# apexconvertlead

This is an Apex class with a corresponding test class that enables SFDC lead conversion from the Salesforce REST API

To deploy this, you must have Salesforce administrator privilege:

1 - Create classes in SFDC Sandbox environment\n
2 - Update test class with valid AccountId, OwnerId and LeadId\n
3 - Run tests in SFDC development console\n
4 - Test the function from the SFDC sandbox REST API\n
5 - Modify the test class with valid AccountId, OwnerId and LeadId from production environment\n
6 - Ensure sandbox environment has proper access to send change set to production\n
7 - Add restleadconvert and restleadconverttest to change set and deploy to production\n
8 - Test REST API in production by converting 1 lead\n
