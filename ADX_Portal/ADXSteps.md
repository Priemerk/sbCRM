##Service Request
1. Check if the Service Request Type is installed as CRM solution. If not, install the required Service Request type from the Adxstudio Solution Gallery.
2. Add the Respective Service Request webform to the Service Request web page.
3. Cache Invalidation setup in your browser - http://community.adxstudio.com/products/adxstudio-portals/documentation/developers-guide/cache/cache-invalidation-utility/

4.	Follow this documentation to setup the Duplicate Detection for Service Requests https://community.adxstudio.com/products/adxstudio-portals/documentation/end-users-guide/portal-application-guide/government-features/the-3-1-1-scenario-for-government/enabling-duplicate-detection-on-service-requests/

5.	Open Adoxio Customizations solution to add the entity you would like to add fields to.

6.	Modify the respective CRM Form show as to show all the fields on the portal.

7.	Add the JS code to show/hide the fields in the portal.

8.	Setup the workflow in order to send out an email.

9.	Open the "Service Request List" weblinkset and modify the name of the Service Request if required.

10.	Modify the "Web Details" CRM form that is used to provide a summary of the request status to include all the necessary fields.

11.	Modify the ServiceRequestDetails page in order to add the logic to retrieve the selected value.

12.	Modify the name of the web pages and the home page for the service request in CRM if required.

13.	Modify the Name field of the "Service Request Type" so as to show the customized name in the Service Request entity list. In CRM, navigate to Settings -> Service Request Types and open the service request you are currently developing. Modify the “Name” field of the Service Request.

Note: For creating custom Service Request, please follow this documentation
