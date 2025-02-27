Hi This project aimed to design and implement a custom application from servicenow studio to client rquirements.
The Project is focused on a company who sells AI Smart Devices. I build the tables for the AI Devices and then a Device Request table.
The request table are extended from the Task Table along with these different groups are created like release management, diapatch mangement, device management.
Along with the tables roles are created according to the requirement the access are controlled. like device management can CRUD the AI devices table, Release management can CRUD the device request table. dispatch mangement can read and update the device request table.
After the creation of tables and roles the tables are populated with the custom fields. several Ui policies and client scripts were implemented to enhance the information availability for the user.
As this company runs by selling product. I created a custoom catalog gettting referenced from pre bult service catalog. the ai devices subcategory consists of several question related to product like type of product, quantity, business requirement, pricing etc.
After creating the catalog to execute the next steps of ordering like dispatch and delivery created a flow
The flow gets triggered by the service catalog thats is the order placement. Created flows and flow logic to excecute the chain of events tot process the order. like creation of request item, request task etc.
Then creted the Schedule Scripting and Notification to update the customer about the progress of the order. like dispatchment,delivery, cancellation of order etc. 
The each step of creating the application changes were commited in new branches following the name. The initial tables, role,groups were commited in main branch. The flows,Scheduled scripts, notifications all were  commited in flow Designer.
