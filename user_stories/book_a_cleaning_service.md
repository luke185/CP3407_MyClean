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
- Adjusted for Velocity: 6 days (4 / 0.7 = 5.71)

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
1. Add logic to control booking availability based on provider availability. (2 days)
2. Add a booking button + logic to each listing on the listings page (1 day)
3. Include a page for user's to see their current bookings (1 day)

### + TODO: Week 4
>   V1: Week / Chapter 4
1. Add logic to control booking availability based on provider availability. 
2. Add a booking button + logic to each listing on the listings page
3. Include a page for user's to see their current bookings 
### + IN PROGRESS: Week 4
>   V1: Week / Chapter ...
1. Add logic to control booking availability based on provider availability. 
2. Add a booking button + logic to each listing on the listings page. 
### + DONE
>   V1: Week / Chapter ...
1. Add logic to control booking availability based on provider availability. (28/02/2025)

## UI Design  
>   V1: Week / Chapter 2
Book a Cleaning Service page [Image](/images/ui_design/Book_A_Cleaning_Sevice.png)

## Completion Evidence 

Database tables for holding provider availability slots and recurring workflows (recursive code) for periodically generating slots based on provider availability stored in the database: [Image](/images/iteration1_completion_evidence/Booking Slot API Workflows.png) [Image](images/iteration1_completion_evidence/Booking Slot Database Table.png)


