# Project Design

## Project Title
Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Platform
ServiceNow

## Automation Tool
Flow Designer

## Project Design Overview
The project is designed to automate the procurement and configuration process for standard laptops in ServiceNow.

The workflow connects the Standard Laptop Service Catalog item with a Flow Designer flow. After the service request is approved, the flow automatically creates a Catalog Task and assigns it to the Hardware assignment group for laptop configuration.

## Workflow Design

The overall workflow is designed as follows:

Service Catalog
        ↓
Standard Laptop
        ↓
Place Order
        ↓
Approval
        ↓
Flow Designer
        ↓
Create Catalog Task
        ↓
Laptop need to Configured
        ↓
Assignment Group: Hardware

## Flow Design

### Flow Name
Standard Laptop Task

### Application
Global

### Run As
System User

### Trigger
Service Catalog

### Action
Create Catalog Task

## Catalog Task Design

The Catalog Task is designed with the following values:

| Field | Value |
|---|---|
| Request Item | Requested Item Record |
| Table | Catalog Task |
| Short Description | Laptop need to Configured |
| Description | Laptop need to Configured |
| Assignment Group | Hardware |
| Approval | Approved |

## Service Catalog Design

The Standard Laptop service catalog item is connected to the created Flow.

Users can:

1. Open Service Catalog.
2. Select Hardware.
3. Select Standard Laptop.
4. Click Order Now.
5. View the order status.
6. Open the Request Number.
7. Access the Approvers section.
8. Approve the request.
9. Open the Requested Item.
10. View the generated Catalog Task.

## Expected Design Output

After approval of the Standard Laptop request, a Catalog Task should be created automatically. The task should contain the required short description and should be assigned to the Hardware group for configuration.

## Design Goal

The design aims to create a streamlined and automated laptop procurement workflow that reduces manual intervention and ensures that approved laptop requests are forwarded to the Hardware team for configuration.
