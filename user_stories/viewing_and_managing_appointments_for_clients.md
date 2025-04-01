 # Viewing and Managing Appointments for Clients

## Description  
>   V1: Week / Chapter 1 
- As a customer, I want to view, reschedule, pay or cancel my upcoming cleaning appointments, so I have full control over my bookings
   
## Priority:  
>   V1: Week / Chapter 1 

- 20

## Estimation:  

>   V1: Week / Chapter 1
- 3 days

>   V1: Week / Chapter 3
- Adjusted for Velocity: 4 days (3 / 0.7 = 4.2)
  
### + Planning Poker  
  
- Luke: 3
- Zane: 3
- Corey: 3
- Dylan: 3
- Caleb: 3

Average: 3 days

### + Assumptions  

- Will need to have a working database of cleaning companies to list them 

### + Dependencies

- Customers will need to be able to make bookings in order to view, reschedule or cancel them. 

## Tasks  
>   V1: Week / Chapter 3
1. Add functionality to the user dashboard to display user bookings with all relevant details (1 day)
2. Add a cancel button to each booking displayed in the dashboard that cancels the relevant booking. (0.5 days)
3. Add database management logic so that when a booking is cancelled, the booked slots are freed up and returned to the pool of available bookings. (Allowing cancelling an rebooking provides reschedueing functionality) (1 day)
4. Add a button to allow payment of a booking from the user dashboard. (0.5 days)
### + TODO
>   V1: Week / Chapter 4
1. Add functionality to the user dashboard to display user bookings with all relevant details
2. Add a cancel button to each booking displayed in the dashboard that cancels the relevant booking. 
3. Add database management logic so that when a booking is cancelled, the booked slots are freed up and returned to the pool of available bookings. (Allowing cancelling an rebooking provides reschedueing functionality) 
4. Add a button to allow payment of a booking from the user dashboard. 
### + IN PROGRESS 
>   V1: Week / Chapter 4
1. Add functionality to the user dashboard to display user bookings with all relevant details (24/03/2025)
2. Add a cancel button to each booking displayed in the dashboard that cancels the relevant booking. (24/03/2025)
3. Add database management logic so that when a booking is cancelled, the booked slots are freed up and returned to the pool of available bookings. (Allowing cancelling an rebooking provides reschedueing functionality) (25/05/2025)
4. Add a button to allow payment of a booking from the user dashboard. (27/05/2025)
### + DONE
>   V1: Week / Chapter 2
1. Add functionality to the user dashboard to display user bookings with all relevant details (24/03/2025)
2. Add a cancel button to each booking displayed in the dashboard that cancels the relevant booking. (25/03/2025)
3. Add database management logic so that when a booking is cancelled, the booked slots are freed up and returned to the pool of available bookings. (Allowing cancelling an rebooking provides reschedueing functionality) (26/05/2025)
4. Add a button to allow payment of a booking from the user dashboard. (28/05/2025)

## UI Design  

>   V1: Week / Chapter 2
1. Viewing and Managing Appointments for Clients Wireframe [Image](/images/ui_design/Viewing_and_Managing_Appointments_for_Clients.png)


## Completion Evidence 
Tasks 1, 2 & 4. Client dashboard booking summary with cancel and pay now buttons included in the interface. [Tasks 1, 2 & 4](/images/iteration2_completion_evidence/Cancel_and_pay_buttons.png)  
Task 2. Workflow logic to cancel a booking [Task 2](/images/iteration2_completion_evidence/workflow_for_cancelling_a_booking.png)  
Task 3. Workflow logic to return booking slots to the available booking pool [Task 3](/images/iteration2_completion_evidence/workflow_for_returning_slots_to_available.png)  
Task 4. Workflow logic for paying a booking from the user dashboard page [Task 4](/images/iteration2_completion_evidence/workflow_for_initiating_payment_on_client_dashboard.png)  

---
