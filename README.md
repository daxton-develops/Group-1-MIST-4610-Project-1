# Group 1 MIST 4610 Project 1

## Team Name: 
21484 Group 1 

## Team Members:

1. Tim Bondon [@tmb26366](https://www.github.com/tmb26366)
2. Zain Merchant [@zm2231](https://www.github.com/zm2231)
3. Daxton Nell [@daxton-develops](https://www.github.com/daxton-develops)
4. Naseem Shash [@nshash02](https://www.github.com/nshash02)
5. Ethan Varghese [@ethanv12345](https://www.github.com/ethanv12345)
6. Marc Wetherington [@marcwetherington](https://www.github.com/marcwetherington)

## Problem Description:

The task at hand is to design and construct a relational database to streamline and manage the comprehensive operations of Ace Haven, a premier tennis club known for its diverse offerings including court rentals, coaching programs, tournaments, and a pro shop. The central entities in our model are the Members, Courts, Coaching Programs, Tournaments, Events, and Pro Shop Inventory, reflecting the multifaceted services provided by the club. Each entity is integral to the functioning of Ace Haven, interacting with various other entities to encapsulate the full spectrum of the club's activities and services.


## Data Model

Explanation of data model: 
The data model is structured to support the complex operations of the premier tennis club Ace Haven by capturing and managing the interactions between various components of the club. Central to this model are the Members, reflecting the active users of the complex, around which the club's services and activities revolve. The Members entity is extensively linked to multiple key activities and services within the club, establishing the foundation for other relationships.

Next to the Members entity are several other important entities: Courts, Bookings, Coaching Programs, and TournamentsAndEvents. Each of these represents a core function or service offered by the club, from court reservations to the organization of events and training programs. The Bookings entity, for example, directly connects Members to Courts, demonstrating the essential relationship between the club's patrons and its primary resources. Similarly, the CoachingProgramsSignup entity bridges Members to specific coaching sessions, facilitating personalized training sessions.

On the commercial side of the club is the Pro Shop Inventory, Equipment Rentals, and EquipmentSales entities. These components not only serve the club's transactional dynamics with members but also ensures the availability and management of tennis-related merchandise and equipment.

Furthermore, the model encompasses operational and support aspects, such as Maintenance and Payments, to ensure seamless club management and service delivery. The inclusion of detailed entities like AgeGroups and Coaches allows Ace Haven to cater to the diverse needs and preferences of the club's members.

In essence, this data model creates a ecosystem reflecting Ace Haven's multifaceted operations. By structuring and interlinking various entities, from Members to Pro Shop Inventory, the model facilitates a holistic approach to club management, catering to all aspects of the tennis club's operations from member services to inventory control and event management and allowing the club to operate efficiently and effectively.


![data model](https://i.ibb.co/Wp5JW3C/Mail-from-Zain-Merchant.png)

## Data Dictionary:

![table one](https://i.ibb.co/19rY51p/Age-Group.png)

![table two](https://i.ibb.co/RcfjdyZ/Bookings.png)

![table three](https://i.ibb.co/zfFcvnB/Coaches.png)

![table four](https://i.ibb.co/ggwG51R/Coaching-Programs-Signup.png)

![table five](https://i.ibb.co/C2pc2g9/Coaching-Programs.png)

![table six](https://i.ibb.co/WvrTm3S/Courts.png)

![table seven](https://i.ibb.co/xspwd9V/Equipment-Rentals.png)

![table nine](https://i.ibb.co/JmvDmyJ/Equipment-Sales.png)

![table 10](https://i.ibb.co/0MzcJzC/Maintenance.png)

![table 11](https://i.ibb.co/9pnz84h/Members.png)

![table 12](https://i.ibb.co/TB9rsBx/Orders.png)

![table 13](https://i.ibb.co/VC4KSVT/Payments.png)

![table 14](https://i.ibb.co/ssSKwYf/Pro-Shop-Inventory.png)

![table 15](https://i.ibb.co/71LVyNs/Rental-Orders.png)

![table 16](https://i.ibb.co/By6t2S4/Tournaments-And-Events.png)

## Queries:

![queryMatrix](https://i.ibb.co/kMxsJYQ/Screenshot-2024-03-27-at-5-35-53-PM.png)

1. Query 1 generates a list that shows each type of membership at the club and the total number of members who have that specific type of membership. The results are grouped by the category of membership type.

![query1](https://i.ibb.co/1LQSMrp/Q1.png)

Query 1 is useful for club managers to understand the distribution of membership types amongst their clientele. Knowing the distribution of members helps with planning services, marketing, and organizing club resources effectively. For example, if there are many members in a premium category, the club might consider expanding exclusive offerings.

2. Query 2 provides a list of all tennis courts by their ID and the number of bookings each one has. The list is organized so that the court with the most bookings is at the top, and the one with the fewest bookings is at the bottom.

![query2](https://i.ibb.co/NjK9T3j/Q2.png)

Query 2 allows managers to see which tennis courts are most popular and have the highest usage. This information can help in maintenance scheduling, as courts that are booked more frequently may require more frequent upkeep. Additionally, the output can help inform reorganizations of court schedules to maximize the utilization of each court. The descending order helps to quickly identify which courts are the busiest.

3. Query 3 retrieves a list of items from the Pro Shop Inventory that have a quantity of less than 5, including the description of each item. It allows for the identification of items that are almost out of stock.

![query4](https://i.ibb.co/FmRY1qV/Q3.png)

Query 3 helps managers to quickly identify the items that need to be re-ordered. It aids in inventory management, ensuring that items are always available for customers, and preventing stockouts that could result in lost sales.

4. Query 4 lists the different methods of payment used by club members and counts the number of payments made by each method. The results are grouped according to the payment method.
 
![query4](https://i.ibb.co/RHshFZM/Q4.png)

Query 4 is useful for financial analysis, helping managers understand which payment methods are used most by members. This can inform decisions regarding payment processing solutions and potential incentives for using preferred payment methods.

5. Query 5 selects names and membership types of members who have not yet participated in a tournaments or events. The list is sorted by membership type.

![query5](https://i.ibb.co/2KWJTt9/Q5.png)

Query 5 allows club managers to target members who have not participated in tournaments or events, to perhaps offer them special incentives to increase engagement and participation rates.

6. Query 6 lists all items sold by the equipment shop, along with the total revenue generated by each item. The list is sorted in descending order by the total revenue.

![query6](https://i.ibb.co/MMQFRC3/Q6.png)

Query 6 gives managers a clear view of the best-selling items in terms of revenue, which enables more informed decisions on inventory purchasing, pricing strategies, and sales promotions.

7. Query 7 shows each court ID, total minutes booked, average booking duration, as well as the number of members who have booked that court. It filters the courts where the average booking time per member is either higher or lower than the overall average booking duration.

![query7](https://i.ibb.co/ZWPwM6r/Q7.png)

Query 7 helps managers identify which courts might be underused or overused compared to the average, suggesting possible issues or opportunities in court scheduling and utilization.

8. Query 8 provides a list of members who have rented equipment but have not made any purchases. The list is ordered by the rental count in descending order.

![query8](https://i.ibb.co/zHFD04V/Q8.png)

Query 8 is beneficial for marketing purposes, identifying members who are potential buyers for the pro shop items since they rent equipment but have not yet purchased. Managers could create targeted promotions to help convert these renters into buyers.

9. Query 9 selects members who have signed up for coaching but have not participated in any tournaments or events, along with the count of coaching sessions they’ve signed up for. The results are ordered by the count of coaching sessions in descending order.

![query9](https://i.ibb.co/Bt8Vtd6/Q9.png)

Query 9 helps the club understand which members are focused on training over competition. This information is important for coaches to know so they can best help each play  and could also identify potential candidates for encouraging into tournament participation.

10. Query 10 retrieves the last participation date in tournaments or events for each member, along with their member ID and name, sorting by the most recent participation date.

![query10](https://i.ibb.co/1fH8yrC/Q10.png)

Query 10 enables managers to see who the most recently active participants are in club events, which could be useful for recognizing and rewarding frequent participants or re-engaging those who haven't participated recently

## Database information:

Name of the database: ns_Sp24_21484_Group1

Additional information: Each query listed above is marked in the database using stored procedures which can be called using the following format: 
CALL TP_Q1();
