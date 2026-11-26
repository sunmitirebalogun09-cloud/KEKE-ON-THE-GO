// Product requirement document for KEKE-ON-THE-GO

1. Product Overview
KEKE-ON-THE-GO is a Java-based campus transportation management system designed to make transportation within a university campus easier, faster, and more convenient.

The system will allow students, staff, and other campus users to request and reserve a keke (tricycle) for transportation from one location to another within the campus.

Users will be able to select their pickup and destination locations, view the transportation fare, specify the number of passengers, and reserve a keke in advance.

The system will also provide features for managing drivers, calculating driver mileage, tracking passenger complaints, and rewarding drivers based on their performance.

The primary goal is to reduce the stress associated with finding transportation on campus, especially during busy periods and when users are running late for lectures, meetings, or other activities.

2. Problem Statement
Have you ever been running late for a lecture and needed to take a keke, only to discover that there are no available drivers nearby?

This is a common transportation challenge experienced by students and staff on university campuses.

Students may spend valuable time searching for available kekes, negotiating transportation fares, or waiting for drivers to become available.

Additionally, the absence of a structured reservation system makes it difficult for passengers to plan their journeys in advance.

Drivers may also experience difficulties managing passenger requests, determining appropriate fares, and maintaining records of their trips.

KEKE-ON-THE-GO aims to address these challenges by providing a simple and organized transportation system that allows users to:
- Request transportation from one campus location to another.
- View the fare before confirming a journey.
- Reserve a keke for a specific time.
- Specify the number of passengers.
- Contact the assigned driver.
- Provide feedback and report complaints.
The system will improve transportation accessibility, reduce unnecessary waiting time, and create a more organized campus transportation experience.

3. Business Objectives
The primary business objective of KEKE-ON-THE-GO is to improve campus mobility by making keke transportation more accessible, convenient, and reliable.
Specific objectives
1. Reduce the time students and staff spend searching for transportation.
2. Provide transparent and consistent transportation fares.
3. Enable passengers to reserve kekes before their intended departure time.
4. Improve communication between passengers and drivers.
5. Encourage better driver performance through a reward system.
6. Maintain accurate records of trips, reservations, fares, and driver performance.
7. Improve passenger satisfaction through a feedback and complaint system.
8. Provide a structured transportation management system for campus authorities.
9. Reduce confusion regarding pickup locations and destination points.
10. Support efficient transportation planning within the university campus.

4. Target Users
KEKE-ON-THE-GO will serve the following categories of users:
4.1 Students
Students are the primary target users of the system.

They will be able to:
- Request transportation to lecture halls, hostels, libraries, and other campus locations.
- Check transportation fares.
- Reserve a keke before departure.
- Specify the number of passengers.
- View driver contact information.
- Submit ratings and complaints.
4.2 Academic and Non-Academic Staff
Staff members will use the system to travel between offices, lecture halls, administrative buildings, and other campus facilities.
4.3 Keke Drivers
Drivers will use the system to:
- View transportation requests.
- Accept or reject available requests.
- View pickup and destination locations.
- Manage reservations.
- Track completed trips.
- View their mileage and performance points.
4.4 Campus Administrators
Administrators will oversee the transportation system.

They will be able to:
- Register and manage drivers.
- Add or update campus locations.
- Configure transportation fares.
- Monitor reservations and completed trips.
- Review complaints.
- Manage driver rewards.
4.5 Campus Visitors
Visitors will be able to use the system to request transportation to recognized locations within the campus.

Stakeholders
We have involved the school authorities and administaration.5. Stakeholders
The following stakeholders will be involved in the development and operation of KEKE-ON-THE-GO:
Stakeholder	Responsibility
Project Team	Design, develop, test, and maintain the system
Students	Use the system to request and reserve transportation
University Staff	Use the system for campus transportation
Keke Drivers	Provide transportation services
School Administration	Approve and oversee the system
Transportation Management	Manage drivers, fares, and transportation policies
System Administrator	Maintain system data and user accounts


6. User Stories
User stories describe the system from the perspective of the people who will use it.
Passenger User Stories
- As a student, I want to select my pickup and destination locations so that I can calculate my transportation fare.
- As a student, I want to view the fare before booking so that I can plan my expenses.
- As a passenger, I want to reserve a keke in advance so that I do not have to search for transportation when I am in a hurry.
- As a passenger, I want to specify the number of people travelling so that the driver can confirm whether the keke has sufficient capacity.
- As a passenger, I want to view the driver's phone number so that I can contact the driver when necessary.
- As a passenger, I want to cancel a reservation when my plans change.
- As a passenger, I want to rate my driver so that good drivers can be recognized.
- As a passenger, I want to submit complaints so that poor service can be addressed.
Driver User Stories
- As a driver, I want to view available transportation requests so that I can choose which trips to accept.
- As a driver, I want to view the pickup and destination locations so that I can plan my journey.
- As a driver, I want to see the number of passengers before accepting a request.
- As a driver, I want to track my completed trips so that I can monitor my work.
- As a driver, I want to earn performance points so that I can receive rewards for good service.
Administrator User Stories
- As an administrator, I want to register drivers so that only approved drivers can use the system.
- As an administrator, I want to add campus locations so that passengers can select recognized destinations.
- As an administrator, I want to update fares so that transportation prices remain accurate.
- As an administrator, I want to review complaints so that I can identify drivers who need improvement.
- As an administrator, I want to view driver performance records so that I can determine reward eligibility.
7. Functional Requirements
Functional requirements describe the specific features the system must provide.

Each requirement has a unique ID and priority.

Priority levels:
- P1: Essential for the initial version.
- P2: Important but can be implemented after core features.
- P3: Optional enhancement.
ID	Functional Requirement	Priority
FR-01	The system shall allow users to select a pickup location.	P1
FR-02	The system shall allow users to select a destination location.	P1
FR-03	The system shall calculate transportation fares based on the selected route.	P1
FR-04	The system shall display the fare before a reservation is confirmed.	P1
FR-05	The system shall allow users to specify the number of passengers.	P1
FR-06	The system shall prevent reservations that exceed the driver's passenger capacity.	P1
FR-07	The system shall allow users to reserve a keke for a future date or time.	P1
FR-08	The system shall generate a unique reservation ID for every booking.	P1
FR-09	The system shall allow drivers to accept or reject transportation requests.	P1
FR-10	The system shall display the assigned driver's name and phone number.	P1
FR-11	The system shall allow passengers to cancel reservations according to the cancellation policy.	P2
FR-12	The system shall maintain records of completed trips.	P1
FR-13	The system shall calculate the mileage covered by each driver.	P1
FR-14	The system shall award performance points to drivers based on ratings and complaints.	P2
FR-15	The system shall allow passengers to rate completed trips.	P2
FR-16	The system shall allow passengers to submit complaints.	P2
FR-17	The system shall allow administrators to register and manage drivers.	P1
FR-18	The system shall allow administrators to add, remove, and update campus locations.	P1
FR-19	The system shall allow administrators to configure transportation fares.	P1
FR-20	The system shall display reservation and trip summaries.	P2
FR-21	The system shall notify users when their reservations are confirmed or cancelled.	P2
FR-22	The system shall allow administrators to view driver performance reports.	P2
FR-23	The system shall maintain a history of user reservations.	P2
FR-24	The system shall allow drivers to update their availability status.	P1


8. Non-Functional Requirements
Non-functional requirements describe how well the system should operate.
8.1 Usability
- The system must be easy to operate.
- The interface must be simple and understandable.
- Users should be able to complete a basic reservation without extensive instructions.
- Error messages must clearly explain what went wrong.
8.2 Performance
- The system should calculate fares within two seconds.
- The system should process reservations without unnecessary delays.
- The system should support multiple users within the expected pilot environment.
8.3 Reliability
- The system must calculate fares consistently.
- Reservation records must not be lost during normal operation.
- The system must prevent duplicate reservations for the same driver and time slot.
8.4 Accuracy
- The system must display accurate fares based on configured route prices.
- Driver mileage must be calculated correctly.
- Reservation details must be stored and displayed accurately.
8.5 Maintainability
- The Java code must be readable and properly organized.
- The system should use appropriate classes and methods.
- Variables and methods must have meaningful names.
- The system should follow object-oriented programming principles.
8.6 Security
- Administrative functions must be restricted to authorized users.
- User information must be protected.
- Passwords must not be stored as plain text if authentication is implemented.
- The system must validate user inputs to prevent invalid data.
8.7 Scalability
- The system should be designed so that additional campus locations, drivers, and users can be added without major changes to the code.
8.8 Compatibility
- The initial version must run on computers with a compatible Java Runtime Environment.
- The system should be designed so that a graphical user interface or mobile application can be introduced in the future.
9. Scope and Priorities
9.1 In Scope
The initial version of KEKE-ON-THE-GO will include:
1. Selection of pickup and destination locations.
2. Fare calculation using predefined campus routes.
3. Display of fixed transportation prices.
4. Passenger count selection.
5. Driver registration and management.
6. Driver availability management.
7. Reservation creation and management.
8. Reservation confirmation.
9. Driver mileage calculation.
10. Driver performance point calculation.
11. Passenger ratings and complaints.
12. Basic administrative management.
9.2 Out of Scope
The following features will not be included in the initial version:
- Real-time GPS tracking.
- Automatic driver location detection.
- Online payment integration.
- Live map navigation.
- Automated mobile push notifications.
- Artificial intelligence-based driver allocation.
- Integration with external transportation companies.
- Advanced analytics and predictive transportation planning.
These features may be considered for future versions.
9.3 Feature Prioritization
Feature	Priority	Reason
Fare calculation	High	Core functionality
Location selection	High	Required for transportation requests
Reservation system	High	Main purpose of the project
Driver management	High	Required to assign transportation
Passenger capacity validation	High	Ensures valid bookings
Mileage calculation	Medium	Supports driver performance tracking
Driver rewards	Medium	Encourages good service
Ratings and complaints	Medium	Supports service quality
Notifications	Medium	Improves user experience
GPS tracking	Low	Future enhancement


10. System Workflow
The system will follow this basic workflow:
Passenger Workflow
1. The user opens the KEKE-ON-THE-GO application.
2. The user selects a pickup location.
3. The user selects a destination.
4. The system checks whether the selected route is valid.
5. The system calculates and displays the transportation fare.
6. The user enters the number of passengers.
7. The system checks passenger capacity.
8. The user selects a preferred departure time.
9. The system displays available drivers.
10. The user selects a driver or submits a transportation request.
11. The driver accepts the request.
12. The system confirms the reservation.
13. The trip is completed.
14. The system records the trip and updates the driver's mileage.
15. The passenger may submit a rating or complaint.
Driver Workflow
1. The driver logs into the system.
2. The driver updates their availability.
3. The driver views available requests.
4. The driver accepts or rejects a request.
5. The driver receives the passenger's pickup and destination information.
6. The driver completes the trip.
7. The system records the completed journey.
8. The driver's mileage and performance points are updated.
11. Business Rules
Business rules define the conditions under which the system operates.
1. A reservation must have a valid pickup location and destination.
2. The pickup location and destination must be different.
3. The system must not allow reservations for more passengers than the keke can accommodate.
4. Every reservation must have a unique reservation ID.
5. A driver must be registered and approved before accepting reservations.
6. A driver must be available before accepting a new reservation.
7. A reservation must have a valid departure date and time.
8. The fare must be calculated before the reservation is confirmed.
9. The fare must be based on the configured route price.
10. A cancelled reservation must not be recorded as a completed trip.
11. Driver mileage must only be updated after a trip has been completed.
12. Driver rewards must be calculated using the approved performance criteria.
13. Passengers must only be allowed to rate completed trips.
14. Administrators must be able to review complaints before applying penalties.
15. A driver must not have overlapping confirmed reservations.
12. Fare Calculation Requirements
The system will use predefined prices for recognized campus routes.

For example:
Pickup Location	Destination	Fare
Main Gate	Library	₦200
Main Gate	Cafeteria	₦150
Library	Hostel	₦250
Cafeteria	Lecture Hall	₦100
Hostel	Main Gate	₦200


These prices are examples and must be replaced with approved campus transportation fares.
Fare Calculation Logic
The system will:
1. Receive the pickup location.
2. Receive the destination.
3. Search for the corresponding route.
4. Retrieve the configured fare.
5. Display the fare to the passenger.
If the route does not exist, the system must display an appropriate message.

Important: Since the initial version uses fixed prices, it does not need to calculate actual road distance or GPS mileage. Route-based pricing will be easier to implement and test in Java.
13. Driver Performance and Reward System
KEKE-ON-THE-GO will include a driver performance system to encourage reliable and professional transportation services.

Drivers will earn performance points based on:
- Passenger ratings.
- Number of completed trips.
- Number of complaints.
- Reservation acceptance and completion.
- Punctuality, where recorded.
Example Reward Structure
Performance	Points
Completed trip	+5
Five-star passenger rating	+10
Positive passenger feedback	+5
Verified complaint	-10
Cancelled accepted reservation without valid reason	-5


The driver with the highest performance score within a specified period may receive a reward.

Possible rewards include:
- Driver of the week recognition.
- Transportation service awards.
- Incentives approved by campus authorities.
The reward system should consider the number of trips completed, not just the total number of ratings, to ensure fair comparisons between drivers.
14. Acceptance Criteria
Acceptance criteria define the conditions that must be met before the system or a feature is considered complete.
ID	Acceptance Criteria
AC-01	The system allows users to select valid pickup and destination locations.
AC-02	The system displays the correct fare for a configured route.
AC-03	The system rejects routes that are not recognized.
AC-04	The system prevents users from selecting the same pickup and destination.
AC-05	The system prevents reservations that exceed passenger capacity.
AC-06	The system generates a unique reservation ID for every booking.
AC-07	The system prevents a driver from accepting overlapping reservations.
AC-08	The system calculates driver mileage correctly after completed trips.
AC-09	The system updates driver performance points correctly.
AC-10	The system displays reservation details clearly.
AC-11	The system allows administrators to update route prices.
AC-12	The system records completed and cancelled reservations separately.
AC-13	The system allows passengers to submit feedback after completing a trip.
AC-14	The system displays clear error messages for invalid inputs.
AC-15	The system maintains accurate driver and reservation records. 



