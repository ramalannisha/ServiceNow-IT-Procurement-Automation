# Project Documentation

## Project Title
Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Project Overview
This project automates the procurement and configuration process for standard laptops using ServiceNow Flow Designer.

## Problem
The existing IT procurement process involves manual effort and may cause delays in configuring standard laptops.

## User Story
As a member of the IT procurement team, I want a streamlined process for ordering standard laptops so that tasks are automatically generated and assigned to the Hardware team for configuration.

## Objective
The project aims to:

1. Provide a seamless experience for users requesting standard laptops.
2. Reduce manual intervention and potential errors.
3. Improve resource utilisation within the IT department.
4. Enhance efficiency and productivity in IT procurement operations.

## Technology Used

- ServiceNow
- Flow Designer
- Service Catalog

## Implementation

The implementation consists of the following major steps:

1. Create the "Standard Laptop Task" flow.
2. Configure Service Catalog as the trigger.
3. Add the "Create Catalog Task" action.
4. Configure the Catalog Task details.
5. Assign the task to the Hardware group.
6. Set the approval condition to Approved.
7. Assign the flow to the Standard Laptop service catalog item.
8. Place a Standard Laptop order.
9. Approve the request.
10. Verify the generated Catalog Task.

## Catalog Task Details

| Field | Value |
|---|---|
| Short Description | Laptop need to Configured |
| Description | Laptop need to Configured |
| Assignment Group | Hardware |
| Approval | Approved |

## Workflow

Service Catalog  
↓  
Standard Laptop  
↓  
Order Now  
↓  
Approval  
↓  
Flow Designer  
↓  
Create Catalog Task  
↓  
Hardware Assignment  
↓  
Laptop Configuration

## Conclusion

By automating the standard laptop procurement process with ServiceNow Flow Designer, the workflow reduces manual overhead and supports timely laptop configuration. The automated process also helps optimise task allocation within the IT department.
