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


data model pic

## Data Dictionary:

![table one](https://ibb.co/RC3GmfM)

![table two](https://ibb.co/L1mNH5b)

![table three](https://ibb.co/9YhX581)

![table four](https://ibb.co/h8HkP5m)

![table five](https://ibb.co/KwcPwds)

![table six](https://ibb.co/GQZhzJg)

![table seven](https://ibb.co/3sDVQ6t)

![table nine](https://ibb.co/S5tF5dC)

![table 10](https://ibb.co/Z8bVTbB)

![table 11](https://ibb.co/CwBN196)

![table 12](https://ibb.co/6RjNkR7)

![table 13](https://ibb.co/5jH78TL)

![table 14](https://ibb.co/mhs9qWj

![table 15](https://ibb.co/mcgtzFf)

![table 16](https://ibb.co/Cb9zKTJ)


## Queries:

query table pic

1. Query 1 description.

query1ss

Management Function.

2. Query 2 description.

query2ss

Management Function.

3. Query 3 description.

query3ss

Management Function.

4. Query 4 description.
 
query4ss

Management Function.

5. Query 5 description.

query5ss

Query 5 Management Function.

6. Query 6 description.

query6ss

Query 6 Management Function.

7. Query 7 description.

query7ss

Query 7 Management Function.

8. Query 8 description.

query8ss

Query 8 Management Function.

9. Query 9 description.

query9ss

Query 9 Management Function.

10. Query 10 description.

query10ss

Query 10 Management Function

## Database information:

Name of the database: ns_Sp24_21484_Group1

Additional information: Each query listed above is marked in the database using stored procedures which can be called using the following format: 
CALL TP_Q1();
