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
