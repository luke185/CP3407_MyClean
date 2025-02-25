# Iteration 1 Time Estimates

>  V1: Week / Chapter 1 
### Available Ideal Work Days
- 4 weeks with 1 work day per team member
- 5 team members
- Total: 5 x 1 x 4 = 20 

### Iteration Summary
> V1: Week / Chapter 1
#### User Stories:
- User Registration (10) [3 days] 
- Display all company listings (10) [4 days]
- Book a cleaning service (10) [4 days]
- Secure Online Payment (10) [4 days]
- Notifications for New Bookings (20) [1 days] {Squeeze this in as a 1 day task}
- Total: 16 days

> [!WARNING]
> Note: Initially we had 4 group members and were working on a 16 day iteration.

>V2: Week / Chapter 3
**Team Velocity:** 0.7 (Recommended velocity for the first iteration of a new project)
#### User Stories (Adjusted for Velocity)
- User Registration (10) (4 days)
- Display all company listings (10) (6 days)
- Book a cleaning service (10) (6 days)
- Company Listing Filters (10) (4 days) {This priority 10 now fits here. Secure Online Payment moved to Iteration 2 as it is now too long} 
- Total: 20 Days

Note: After further research into tools (clearing up some assumptions) we repeated the planning poker process and our estimates increased. 

---
---

# 01 - User Registration and Profile Management

## Description  

>   V1: Week / Chapter 1
- As an individual cleaner, I want to create an account and set up my profile so that I can be discovered by potential clients.  

## Priority:  

>   V1: Week / Chapter 1 
- 10
- This feature **must be added before** many other features relating to user accounts can be implemented  

## Estimation:  

>   V1: Week / Chapter 1 
- 3 days 

>   V1: Week / Chapter 3
- Adjusted for Velocity: 4 days (3 / 0.7 = 4.2)
### + Planning Poker  

- Luke: 3  
- Zane: 3 
- Corey: 3  
- Dylan: 4
- Caleb: 4

Average: 3 days (3.4)  

### + Assumptions  

- We will need to store the cleaner's availability in association with their other profile details in the database.
- It will be straightforward to create user database entries classified by whether they are a cleaner or client. 

### + Dependencies

- None

## Tasks  
>   V1: Week / Chapter 3

### + TODO: Week 4
>   V1: Week / Chapter 4
1. Add user sign up page
2. Add user dashboard / profile page
3. Include database logic to store user profiles
### + IN PROGRESS: Week 4
>   V1: Week / Chapter 4
1. Add user sign up page
2. Add user dashboard / profile page
3. Include database logic to store user profiles
### + DONE
>   V1: Week / Chapter 2
1. Add user sign up page (17/02/2025)
2. Include database logic to store user profiles (17/02/2025)
3. Add user dashboard pages (24/02/2025)

## UI Design  

>   V1: Week / Chapter 2
Wireframes:
1. Home Page [Image](./images/ui-design/Home_Page_Wireframe.png)
2. Listings Page [Image](./images/ui-design/Listings_Page_Wireframe.png)
3. Sign-in Page [Image](./images/ui-design/Sign-in_Page_Wireframe.png)

Other:
1. Design Form [Image](./images/UI-Design_Form.png)
  
## Completion Evidence 
> [!WARNING]
> TODO: ADD COMPLETION EVIDENCE WHEN FINISHED

--- 


# 02 - Display All Company Listings  

## Description  
>   V1: Week / Chapter 1
- As a customer I want to be able to view the cleaning companies available for booking and their availabilities in an easily digestible format, with more detailed information available on companies as I require it. 

  
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
- Zane: 4  
- Corey: 5  
- Dylan: 3
- Caleb: 5

Average: 4 days (4.2)

### + Assumptions  

- Will need to have a working database of cleaning companies to list them 

### + Dependencies

- Cleaner registration needs to be completed so that we can dynamically display company listings. 

## Tasks  
>   V1: Week / Chapter 3

### + TODO: Week 4
>   V1: Week / Chapter 4
1. Add page to display all company listings
2. Create database logic to store companies
### + IN PROGRESS: Week 4
>   V1: Week / Chapter 4
1. Add page to display all company listings
2. Create database logic to store companies
3. Allow companies to set and update their availability for display.
### + DONE
>   V1: Week / Chapter 4
1. Add page to display all company listings (20/02/25)

## UI Design  

>   V1: Week / Chapter 2


[Image](./images/UI-Design_Table.png)
## Completion Evidence 

> TODO: ADD COMPLETION EVIDENCE WHEN FINISHED

---

# 03 - Book a Cleaning Service  

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

### + TODO: Week 4
>   V1: Week / Chapter 4
1. ***Need to finish other 2 user stories before starting this one***
3. Add a booking button + logic to each listing on the listings page
4. Add logic to control booking availability based on provider availability. 
5. Include a page for user's to see their current bookings 
### + IN PROGRESS: Week 4
>   V1: Week / Chapter ...

### + DONE
>   V1: Week / Chapter ...


## UI Design  
>   V1: Week / Chapter 2

# 04 - Company Listing Filters

## Description  

>   V1: Week / Chapter 1
- As a customer, I want to be able to see only the cleaning companies that meet my requirements of price, availability and location. 

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
- Zane: 4
- Corey: 4
- Dylan: 5
- Caleb: 4

Average: 4 days

### + Assumptions  

- None

### + Dependencies

- Customers will need to be able to display company listings in order to filter them. 

## Tasks  
>   V1: Week / Chapter 3

### + TODO: Week 4
>   V1: Week / Chapter 4
1. ***Need to finish other company listing user story, before starting this one***
2. Add filter option to company listing page
### + IN PROGRESS: Week 4
>   V1: Week / Chapter ...

### + DONE
>   V1: Week / Chapter ...


## UI Design  
>   V1: Week / Chapter 2
[Image](./images/UI-Design_Table.png)
## Completion Evidence 
> [!WARNING]
> TODO: ADD COMPLETION EVIDENCE WHEN FINISHED

