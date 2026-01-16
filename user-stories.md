## Story #1 [Basic Room Booking]

As an Employee , I want to book an available room , So that i can reserve space for a meeting. 

### Acceptance criteria 
Given that i am logged into the system , when i select date and time , Then i should see rooms available for booking
Given the availability of the room on that specific date , When i confirm the booking , Then the room should be reserved successfully 
Given a booking is complete , when i view my emails , Then i should have eceived an email confirming my booking

### Story points 
5 

### Priority 
High 

### Dependencies:
-None 

### Technical notes:
 -Requires booking records 

 ### Design Notes:
 -Use a calendar view to show room availability 


 ## Story #2 [Recurring meetings setup]
 
 As an Employee , i want to create recurring room bookings ,So that i dont book for the same meeting repeatedly

 ### Acceptance criteria 
 Given that i am completing my booking details , when i press the duration option  recurring shows , Then i am prompted to choose recurrence pattern
 Given that i choose the recurring option , When its done loading , Then available dates occur 
 Given the available dates , when i confirm the dates the meeting is gonna be in , Then the booking is successful

 ### Story points 
 8
 ### Priority 
 Medium 

 ### Dependencies 
  story #1

 ### Technhical notes:
  Requires recurring booking option

 ### Design Notes:
 recurring option

 ## Story #3 [Room capacity filtering]

 As an Employee , I want to filter the rooms by size , So that i can find a room that fits people who will be in the meeting 

### Acceptance criteria 
Given i entered number of people who will be attending , When i search rooms , Then only room fitted display 
Given no rooms match , When i search , Then i receive a prompt
Given capacity filter applied , when i reset filters , Then all rooms display 
 ### Story points 
 3
 ### Priority 
 Medium 

 ### Dependencies 
  story #1

 ### Technhical notes:
  Requires room capacity field

 ### Design Notes:
 Capacity filter on search panel


 ## Story #4 [Booking cancellation]

 As an Employee , I want to cancel a room booking , So that the room becomes available for booking

 ### Acceptance Criteria 
 Given I have an existing booking  , When i select cancel , Then the booking is cancelled 
 Given booking is cancelled , When i select room availability , Then the room is available 
 Given i cancelled , When i receive an email , Then i confirm my cancellation 

 ### Story points 
 3
 ### Priority 
 High

 ### Dependencies 
  story #1

 ### Technhical notes:
  Requires Cancel booking function

 ### Design Notes:
 Cancel button

 ## Story #5 [Room equipment requirements]

 As an Employee , I want to request room with specific equipment , So that the meeting has needed equipment

 ### Acceptance Criteria 
 Given I am booking  , When i select equipment needs , Then rooms with such equipment display 
 Given the equipment is unavailable , When i search , Then i see no results
 Given i confirm booking , When equipment is available , Then booking is cvonfirmed  

 ### Story points 
 5
 ### Priority 
 Medium

 ### Dependencies 
  story #1

 ### Technhical notes:
  Requires equiment attribures in rooms

 ### Design Notes:
 Equipment checklist

 ## Story #6 [Admin dashboard viewing]

 As an Admin, I want to view system dashboard , So that i can monitor bookings 

 ### Acceptance Criteria 
 Given I log in as admin , When i access dashboard , Then booking display  
 Given data exists , when dashboard loads , Then charts show usage trends
 Given noi data exist , when dashboard loads , Then empty state displays

 ### Story points 
 5
 ### Priority 
 Medium

 ### Dependencies 
  story #1

 ### Technhical notes:
  Requires reporting issues

 ### Design Notes:
 Graphs and summary cards

## Story #7 [Room maintanance scheduling]

 As a Facilities manager , I want to schedule room maintenance , so that rooms wont be available during this time

 ### Acceptance Criteria 
 Given I select room , when i schedule maintenance , Then room is blocked from booking 
 Given maintenance exists , When employees search rooms , Then room is hidden 
 given maintenance ended , When maintence is done , Then room becomes available

 ### Story points 
 8
 ### Priority 
 Medium

 ### Dependencies 
  story #1

 ### Technhical notes:
  Maintenance on system 
 ### Design Notes:
 Maintenance dates view


## Story #8 [Visitor booking Assistance]

 As a Receptionist , I want to book rooms for visitors , So that they can have meeting spaces

 ### Acceptance Criteria 
 Given visitor details entered , when booking created , Then reservation is saved  
 Given visitor booking exists , when viewing bookings, Then it is labeled visistor 

 ### Story points 
 5
 ### Priority 
 low

 ### Dependencies 
  story #1

 ### Technhical notes:
  visitor booking field 

 ### Design Notes:
 visitor form fields


 ## Story #9 [Booking conflict resolution]

 As an Admin, I want to resolve booking conflicts , So that double bookings are prevented

 ### Acceptance Criteria 
 Given two bookings overlap , when conflict detected , then system blocks saving 
 Given admin intervenes , When conflict resolved , Then booking remains
 Given conflict occurs , When user attempt bookings , Then warning appears

 ### Story points 
 8
 ### Priority 
 high

 ### Dependencies 
  story #1

 ### Technhical notes:
  conflict-check logic on booking save 

 ### Design Notes:
 conflict alert messages

 ## Story #10 [Usage reports generation]

 As an Admin, I want to generate usage reportts , So that i can analyze room utilization

 ### Acceptance Criteria 
 Given I select rweport period , When generate clicked , Then report downloads
 given data exists , when report generated , then correct totals display 
 Given no data exist , when report generated , Then empty report is produced

 ### Story points 
 5
 ### Priority 
 Medium

 ### Dependencies 
  story #6

 ### Technhical notes:
  export to pdf function

 ### Design Notes:
 date range picker






































