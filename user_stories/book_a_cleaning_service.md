# Book a Cleaning Service  

## Description  

>   V1: Week / Chapter 1
- As a customer, I want to easily search for and book a cleaning service through the website, so I can quickly find a reliable cleaner that fits my schedule
- I should be able to select a service in the listing, and book from their listing page

## Priority:  
>   V1: Week / Chapter 1 
- 10

## Estimation:  

>   V1: Week / Chapter 1
- 4 days

>   V1: Week / Chapter 3
- Adjusted for Velocity: 5 days (4 / 0.7 = 5.71) (We rounded this down as we had rounded up a lot on other user stories)

### + Planning Poker  
  
- Luke: 4
- Zane: 3
- Corey: 3
- Dylan: 4
- Caleb: 5

Average: 4 days (3.8)

### + Assumptions  

- None

### + Dependencies

- Customers will need to be able to display company listings in order to select and book them. 

## Tasks  
>   V1: Week / Chapter 3

### + TODO
>   V1: Week / Chapter 4
1. Add logic to control booking availability based on provider availability. (2 days)
2. Add a booking button + logic to each listing on the listings page (0.5 days)
3. Add a booking page for users to select their required booking times. (2 days)
4. Include a page for user's to see their current bookings (0.5 days)
### + IN PROGRESS
>   V1: Week / Chapter ...
1. Add logic to control booking availability based on provider availability. (26/02/2025)
2. Add a booking button + logic to each listing on the listings page. (10/03/2025)
3. Add a booking page for users to select their required booking times. (10/03/2025)
4. Include a page for user's to see their current bookings (13/03/2025)
### + DONE
>   V1: Week / Chapter ...
1. Add logic to control booking availability based on provider availability. (28/02/2025)
2. Add a booking button + logic to each listing on the listings page. (10/03/2025)
3. Add a booking page for users to select their required booking times. (12/03/2025
4. Include a page for user's to see their current bookings (14/03/2025)
## UI Design  
>   V1: Week / Chapter 2


1. Book a Cleaning Service page [Image](/images/ui_design/Book_A_Cleaning_Sevice.png)
## Completion Evidence 
Task 1. Database tables for holding provider availability slots and recurring workflows (recursive code) for periodically generating slots based on provider availability stored in the database:  [Task 1](/images/iteration1_completion_evidence/Booking_Slot_API_Workflows.png) [Task 1](/images/iteration1_completion_evidence/Booking_Slot_Database_Table.png)  
Task 2. Booking buttons on the listings page that link to the booking page: [Task 2](/images/iteration1_completion_evidence/booking_buttons.png)   
Task 3. Booking screen with time selection interface that updates dynamically based on selections: [Task 3](/images/iteration1_completion_evidence/booking_selection_1.png) [Task 3](/images/iteration1_completion_evidence/booking_selection_2.png)   
Task 4. Current bookings table displayed on the user dashboard: [Task 4](/images/iteration1_completion_evidence/user_bookings_tables.png)


