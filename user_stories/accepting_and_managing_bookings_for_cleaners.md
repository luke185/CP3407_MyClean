# Accepting and Managing Bookings for Cleaners

## Description  
>   V1: Week / Chapter 1
- As a cleaner, I want to receive and manage service requests, so I can accept jobs that fit my availability and workload. I should be able to see a list of customer bookings and be able to accept or reject them

## Priority:  
>   V1: Week / Chapter 1

- 20

## Estimation:  

>   V1: Week / Chapter 1
- 3 days

>   V1: Week / Chapter 3
- Adjusted for Velocity: 4 days (3 / 0.74 = 4.05)

### + Planning Poker  
  
- Luke: 4
- Zane: 4
- Corey: 4
- Dylan: 5
- Caleb: 5

Average: 4 days (4.4)

### + Assumptions  

- Assuming that bookings shouldn't just be automatically accepted when they are made.
- Assuming we can easily duplicate the client booking summary interface for providers

### + Dependencies

- Customers will need to be able to make bookings in order for cleaners to accept or reject them. 

## Tasks  
>   V1: Week / Chapter 3
### + TODO (Pre-velocity)
>   V1: Week / Chapter 4
1. Add interface and database logic to allow cleaners to toggle automatic acceptance of bookings. (1 Day)
2. Add a booking summary to the provided dashboard that includes the bookings status. (0.5 Days)
3. Add buttons to accept or reject bookings if automatic acceptance is not toggled on. (0.5 Days)
4. Add a button to cancel a client booking that does not make the slots available again. (1 Day)  
### + TODO
>   V1: Week / Chapter 4
1. Add interface and database logic to allow cleaners to toggle automatic acceptance of bookings. (1.5 Days)
2. Add a booking summary to the provided dashboard that includes the bookings status. (0.5 Days)
3. Add buttons to accept or reject bookings if automatic acceptance is not toggled on. (0.5 Days)
4. Add a button to cancel a client booking that does not make the slots available again. (1.5 Days)
### + IN PROGRESS 
>   V1: Week / Chapter 4
1. Add interface and database logic to allow cleaners to toggle automatic acceptance of bookings. (29/03/2025)
2. Add a booking summary to the provided dashboard that includes the bookings status. (31/01/2025)
3. Add buttons to accept or reject bookings if automatic acceptance is not toggled on. (01/04/2025)
4. Add a button to cancel a client booking that does not make the slots available again. (01/04/2025)  
### + DONE
>   V1: Week / Chapter 2
1. Add interface and database logic to allow cleaners to toggle automatic acceptance of bookings. (30/03/2025)
2. Add a booking summary to the provided dashboard that includes the bookings status. (01/04/2025)
3. Add buttons to accept or cancel bookings if automatic acceptance is not toggled on. (01/04/2025)
4. Add a button to cancel a client booking that does not make the slots available again. (02/04/2025)

## UI Design  
>   V1: Week / Chapter 2
> Accepting and Managing Bookings for Cleaners Wireframe  [Image](/images/ui_design/Accepting_and_Managing_Bookings_for_Cleaners_Wireframe.png)

## Completion Evidence 
Task 1. Provider setting toggle in dashboard and database with related field [Task 1](/images/iteration2_completion_evidence/automatic_acceptance_toggle.png) [Task 1](/images/iteration2_completion_evidence/database_table_with_auto_accept_field.png)  
Task 2, 3 & 4. Booking summary table and accept / cancel buttons [Task 2 & 3](/images/iteration2_completion_evidence/provider_view_and_manage_bookings_table.png)  
Task 4. Workflow for providers to cancel a booking [Task 4](/images/iteration2_completion_evidence/provider_booking_cancelation_workflow.png)  

---
