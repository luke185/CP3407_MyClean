# Secure Online Payments

## Description  
>   V1: Week / Chapter 1 
- As a customer, I want to securely pay for my cleaning service through the app, so I don’t have to handle cash transactions 

## Priority:  
>   V1: Week / Chapter 1

- 10

## Estimation:  

>   V1: Week / Chapter 1
- 4 days  

>   V1: Week / Chapter 3
- Adjusted for Velocity: 5 days (4 / 0.74 = 5.4)
  
### + Planning Poker  

- Luke: 4
- Zane: 5  
- Corey: 4  
- Dylan: 3
- Caleb: 5

Average: 4 days (4.2) 

### + Assumptions  

- Payment services generally provide high quality APIs.

### + Dependencies

- Will need to have booking system functional before this feature can be added

## Tasks  
>   V1: Week / Chapter 3
### + TODO (Pre-velocity)
>   V1: Week / Chapter 4
1. Register with payment services provider and generate required API information (0.5 Days)
2. Build payment interface (1 Day)
3. Implement logic to calculate and store booking price in booking database records (1.5 Days)
4. Link payment interface with bookings in database to retrieve prices for payment (0.5 Days)
5. Retrieve payment confirmation information from API to update booking payment status in database (0.5 Days)  
### + TODO
>   V1: Week / Chapter 4
1. Register with payment services provider and generate required API information (0.5 Days)
2. Build payment interface (1.5 Days)
3. Implement logic to calculate and store booking price in booking database records (2 Days)
4. Link payment interface with bookings in database to retrieve prices for payment (0.5 Days)
5. Retrieve payment confirmation information from API to update booking payment status in database (0.5 Days)
### + IN PROGRESS 
>   V1: Week / Chapter 4
1. Register with payment services provider and generate required API information (18/03/2025)
2. Build payment interface (18/03/2025)
3. Implement logic to calculate and store booking price in booking database records (19/03/2025)
4. Link payment interface with bookings in database to retrieve prices for payment (21/03/2025)
5. Retrieve payment confirmation information from API to update booking payment status in database (21/03/2025)
### + DONE
>   V1: Week / Chapter 2
1. Register with payment services provider and generate required API information (18/03/2025)
2. Build payment interface (19/03/2025) (Took longer than expected due to having to refactor the booking confirmation information)
3. Implement logic to calculate and store booking price in booking database records (21/03/2025)
4. Link payment interface with bookings in database to retrieve prices for payment (21/03/2025)
5. Retrieve payment confirmation information from API to update booking payment status in database (24/03/2025)

## UI Design  

>   V1: Week / Chapter 2  

1. Secure Online Payments Wireframe [Image](/images/ui_design/Secure_Online_Payments_Wireframe.png)


## Completion Evidence 
Task 1. Stripe API dashboard [Task 1](/images/iteration2_completion_evidence/MyClean_Stripe_Payment.png)  
Task 2. Payment Button and Stripe (payment provider) Payment Interface [Task 2](/images/iteration2_completion_evidence/Pay_Now_Interface.png) [Task 2](/images/iteration2_completion_evidence/MyClean_Stripe_Payment.png)  
Task 3. Database table showing bookings with price [Task 3](/images/iteration2_completion_evidence/Payment_Confirmation_Database.png)  
Task 4. Payments workflows to generate price on making a booking and to retrieve calculated prices [Task 4](/images/iteration2_completion_evidence/PaymentWorkflows.png) [Task 4](/images/iteration2_completion_evidence/Price_Calculation.png)  
Task 5. Database table showing payment confirmation information from payment platform provider. [Task 5](/images/iteration2_completion_evidence/Payment_Confirmation_Database.png)  

--- 
