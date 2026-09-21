# Project Development

## Project Title
Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Development Platform
ServiceNow

## Development Tool
Flow Designer

## Development Process

### Step 1: Create the Flow
A new Flow is created in ServiceNow Flow Designer.

- Flow Name: Standard Laptop Task
- Application: Global
- Run As: System User

### Step 2: Configure the Trigger
The flow is configured with a Service Catalog trigger.

### Step 3: Add the Action
The "Create Catalog Task" action is added to the flow.

### Step 4: Configure the Catalog Task
The Catalog Task is configured using the following values:

- Request Item: Requested Item Record
- Table: Catalog Task
- Short Description: Laptop need to Configured
- Description: Laptop need to Configured
- Assignment Group: Hardware
- Approval: Approved

### Step 5: Save and Activate the Flow
The configured flow is saved and activated so that it can process the Standard Laptop service request.

### Step 6: Assign the Flow to Standard Laptop
The Standard Laptop service catalog item is opened under Maintain Items.

The existing process engine automation is replaced with the newly created "Standard Laptop Task" flow.

### Step 7: Place a Standard Laptop Order
The Service Catalog is opened and the following options are selected:

1. Service Catalog
2. Hardware
3. Standard Laptop
4. Order Now

### Step 8: Approve the Request
The generated request is opened and the Approvers section is accessed. The request is then approved.

### Step 9: Verify the Catalog Task
After approval, the Requested Item is opened and the Catalog Tasks section is checked.

The generated task should show:

- Short Description: Laptop need to Configured
- Assignment Group: Hardware

## Development Outcome

The developed workflow automates the creation and assignment of a Catalog Task after approval of a Standard Laptop request. The task is assigned to the Hardware group for laptop configuration.
