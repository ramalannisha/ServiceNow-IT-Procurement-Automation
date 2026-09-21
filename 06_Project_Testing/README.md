# Project Testing

## Project Title
Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Testing Objective
The objective of testing is to verify that the Standard Laptop procurement workflow works as expected after implementing the Flow Designer automation.

## Test Cases

| Test Case | Test Action | Expected Result |
|---|---|---|
| TC01 | Open Flow Designer | Flow Designer should open successfully |
| TC02 | Create the Standard Laptop Task flow | Flow should be created with the required name |
| TC03 | Configure Service Catalog trigger | Service Catalog should be configured as the trigger |
| TC04 | Configure Create Catalog Task action | Catalog Task action should be added successfully |
| TC05 | Configure task fields | Required description, approval, and assignment values should be configured |
| TC06 | Save and activate the flow | Flow should be saved and activated |
| TC07 | Assign the flow to Standard Laptop | Standard Laptop catalog item should use the created flow |
| TC08 | Place Standard Laptop order | Standard Laptop request should be created |
| TC09 | Approve the request | Requested Item should show the approval |
| TC10 | Check Catalog Tasks | Catalog Task should be generated after approval |
| TC11 | Verify task details | Short description and Hardware assignment group should be displayed |

## Verification

The following details should be verified in the generated Catalog Task:

- Short Description: Laptop need to Configured
- Assignment Group: Hardware
- Approval: Approved

## Expected Testing Outcome

The testing should confirm that the Standard Laptop request is connected to the Flow Designer workflow and that the required Catalog Task is generated after approval and assigned to the Hardware group.
