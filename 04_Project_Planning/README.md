# Project Planning

## Project Title
Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Project Goal
To automate the procurement and configuration process for standard laptops using ServiceNow Flow Designer.

## Project Plan

| Phase | Activity | Expected Outcome |
|---|---|---|
| 1 | Create Flow | Create the Standard Laptop Task flow |
| 2 | Configure Trigger | Use Service Catalog as the flow trigger |
| 3 | Configure Action | Create a Catalog Task automatically |
| 4 | Configure Task Fields | Set description, approval, and assignment group |
| 5 | Assign Flow | Connect the flow to the Standard Laptop catalog item |
| 6 | Place Order | Place a Standard Laptop order through Service Catalog |
| 7 | Approval | Approve the requested item |
| 8 | Verify Task | Check the generated Catalog Task and Hardware assignment |

## Planned Flow

1. Create a Flow named "Standard Laptop Task".
2. Set the application as Global.
3. Set Run As to System User.
4. Add the Service Catalog trigger.
5. Add the Create Catalog Task action.
6. Configure the Requested Item Record.
7. Set the required task fields.
8. Save and activate the Flow.
9. Assign the Flow to the Standard Laptop service catalog item.
10. Place a Standard Laptop order.
11. Approve the request.
12. Verify the generated Catalog Task.

## Task Assignment Plan

The generated Catalog Task will be assigned to the **Hardware** assignment group so that the laptop can be configured after the request is approved.

## Expected Result

The completed plan should result in an automated process where an approved Standard Laptop request generates a Catalog Task and assigns it to the Hardware team for configuration.
