# Report

# Introduction
The main aim is to provide information of movie ticket so that customer can book the tickets accordingly.The project has been developed to carry out process easily and quickly.The system enables the user to Book tickets,Cancel tickets,View all booking records.

# Research
Cinemas help in contributing to our daily memories as they provide an essential part of our culture,going to cinemas has been the culture of almost all the families of today’s generation. It is a time when the family can spend some time altogether by stealing some hours from their busy schedule. Movie Ticket Booking System provides the customers facility to book tickets for a movie and to gather information about the movies and theaters.Customers can book ticket of his choice and may cancel a ticket


# Features
 1.Booking tickets

 2.Cancel tickets

 3.Pricing of ticket

 4.View all booking records

# Benefits
 1.User Friendly

 2.Provides flexibility

 3.Can Select the seats as per convience

# Defining our system

Our system have some inbuilt features for user and admin :-
 ## Admin 
 * Login.
 * Can Change Price of a Ticket. 
 * Can View the Reserved Tickets. 
 * Exit System. 
 ## User 
 * Login.
 * View the Movies Avaliable. 
 * Purchase a Ticket. 
 * View the avaliable seats. 
 * Cancel a Ticket. 
 * Exit System.

# SWOT Analysis
![swot](https://user-images.githubusercontent.com/46933088/153005667-325c747e-6e16-4547-9adf-2092c59db05f.png)

# 4W's and 1'H
## Who
* Theater.

## What
* To bulid a system to book ticket,cancel ticket,view reserverd seats,change price of ticket(admin only).

## When
* When user wants to carry out the tasks quickly and this reduces manual work and saves time.

## Where
* This issue is in all parts of the world in theater where there is a lot of booking,cancellation of tickets happening in all the time.

## How
* By creating a system which will provide all the functionalities required,the booking of, cancelling of the tickes and other actions will be take more time and system needs more workers for these actions

# Detail requirements

## High Level Requirements

* HR01	User shall be able to login to the system.	
* HR02	User shall be able to purchase a ticket.
* HR03	User shall be able to get summary of the ticket booked.	
* HR04	User shall be able to cancel a ticket.	
* HR05	User shall be able to view the reserved seats.	

## Low level Requirements

* LR01	User shall be able to login to the system with correct login details.	
* LR02	If appropriate login details are not entered a message is displayed -"wrong password".	
* LR03	Displaying the movies available.
* LR04	Admin can change the price for the movie.	
* LR05	If user specifies seat number which is booked ,message appears that the seat is unavaliable.	
* LR06	Displaying the summary of the ticket booked.

# Architecture Design
![archit](https://user-images.githubusercontent.com/46933088/153163940-5fbcb519-bcca-4084-b193-d9d9d4e19299.png)

# Usecase Diagram
![usecasediag](https://user-images.githubusercontent.com/46933088/153645252-e9f6a355-ef1f-42f2-8527-98a4a3a9fa8c.png)

# Low Level Design 
## Level0
![Lowlevel](https://user-images.githubusercontent.com/46933088/153651243-b1180fc6-8dc3-435a-8f8b-6522e4f1f5c0.png)

## Level1
![highlevel](https://user-images.githubusercontent.com/46933088/153648668-b7e5a9a9-05e9-454d-942a-84728c040f13.png)

# Test Plan

| **Test ID** | **HLT ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |   
|-------------|-----|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  T_01|H_01| Provide required details for login to book a ticket| password| Successfully logined In | Successfully logined In| 
|  T_02|H_01| When wrong password is entered| Password|  Entered Password is wrong | Entered Password is wrong | 
|  T_03|H_02|Display the  details of movie available|  Enter choice | Display list | Display list | 
|  T_04|H_02| Purchase a ticket for the movie available | enter choice | ThankYou for Booking Ticket | ThankYou for Booking Ticket| 
|  T_05|H_03|  Summary of a ticket for purchased movie| enter choice | Booking ID,Customer name,Show Name,Hallno,Price | Booking ID,Customer name,Show Name,Hallno,Price| 
|  T_06|H_04| Cancel a ticket   |ID number|  Your ticket is cancelled | Your ticket is cancelled | 
|  T_07|H_03| Change the price of ticket (only admin) | password| Please enter new price | Please enter new price   | 
|  T_08|H_03| Change the price of ticket after login (only admin) | enter new price -price|Price Updated Successfully | Price Updated Successfully  |
|  T_09|H_03|When wrong password is entered while Changing the price of ticket (only admin) | password | Entered Password is wrong  |  Entered Password is wrong |
|  T_10|H_05|To view the reserved ticke |password| summary of tickeT|summary of ticket | 
|  T_11|H_05|When wrong password is entered to view the reserved ticket|Correct Password | Entered Password is wrongt|Entered Password is wrong |
