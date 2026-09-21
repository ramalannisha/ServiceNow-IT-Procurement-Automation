# Requirement Analysis

## Project Title
Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Problem Statement
The current IT procurement process lacks efficiency and automation, resulting in delays and manual overhead, particularly in handling standard laptop orders. Requests for standard laptops often require configuration, but this step is prone to oversight or delay, leading to frustration among users and inefficient resource allocation within the IT department.

## User Story
As a member of the IT procurement team, I want a streamlined process for ordering standard laptops so that tasks are automatically generated and assigned to the hardware team for configuration. This will ensure that laptops are promptly configured upon arrival, reducing user wait times and minimising manual intervention.

## Project Objective
The objective of this project is to implement an automated workflow using Flow Designer to facilitate the procurement and configuration of standard laptops.

The project aims to:

1. Create a seamless experience for users requesting standard laptops by ensuring timely configuration.
2. Reduce manual intervention and potential errors in the procurement process.
3. Improve resource utilisation within the IT department by optimising task allocation.
4. Enhance overall efficiency and productivity in IT procurement operations.

## Functional Requirements

### 1. Flow Creation
The system should provide a Flow Designer workflow named "Standard Laptop Task".

### 2. Service Catalog Trigger
The flow should use the Service Catalog as the trigger.

### 3. Catalog Task Creation
The flow should automatically create a Catalog Task after the required approval.

### 4. Request Item Mapping
The Requested Item Record should be used in the Request Item field.

### 5. Task Description
The Catalog Task should contain the short description:

"Laptop need to Configured"

The description field should also contain:

"Laptop need to Configured"

### 6. Assignment Group
The created Catalog Task should be assigned to the Hardware assignment group.

### 7. Approval Condition
The flow should process the Catalog Task when the Approval field is set to "Approved".

### 8. Service Catalog Integration
The Standard Laptop service catalog item should use the created Flow.

### 9. Laptop Ordering
Users should be able to place an order for the Standard Laptop through the Service Catalog.

### 10. Task Verification
After approval, the generated Catalog Task should be available under the Requested Item and display the updated status, short description, and assignment group.

## Main Requirements Summary

| Requirement | Description |
|---|---|
| Platform | ServiceNow |
| Automation Tool | Flow Designer |
| Service | Standard Laptop |
| Trigger | Service Catalog |
| Action | Create Catalog Task |
| Assignment Group | Hardware |
| Approval | Approved |
| Short Description | Laptop need to Configured |
| Service Catalog | Standard Laptop |

## Expected Outcome
The automated workflow should ensure that standard laptop requests are processed efficiently, approved requests generate the required Catalog Task, and the task is assigned to the Hardware team for configuration.
