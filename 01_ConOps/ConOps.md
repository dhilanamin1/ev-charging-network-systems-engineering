# Concept of Operations (ConOps)
### EV Charging Network - Inglewood City Hall/ Civic Center

A Concept of Operations describing how the Inglewood Civic Center and City Hall EV charging station is used on a day-to-day basis, highlighting users, purpose, operational scenarios, and limitations. 

## 1. Purpose
This system allows locals, tourists, city hall staff / civic-center users, and
commuters a place to charge their vehicles at the Inglewood Civic Center, which
is close in proximity to the Kia Forum, Intuit Dome, and Sofi Stadium. This
location is accessible via four different freeways and will be an EV charging
station that will serve as a reliable public charging that can satisfy commuter
demands as well as large influx of traffic surrounding major events in the area.

## 2. System Boundary
**Inside the System:**
The system includes the charging stations, the software that logs data including
free/occupied chargers, charger failures, billing/pricing logic, and usage, and
the physical connection to the power grid.

**External to the system:**
External to the system are the drivers, their vehicles, the electrical power grid
and utilities, and the payment processing system.

## 3. User Classes 
| User Class | Role / What They Want |
|---|---|
| Driver | Wants to charge their vehicle while at or before leaving an event, conduct business in City Hall / the Civic Center, fill up their battery while on their commute, or charge before heading home. |
| Maintenance / Cleaning Staff | Work on any charger failures, check the data and software for faults, and clean the charger ports to remove debris. |
| City of Inglewood (Governing Body) | Owns the charging station and ensures public accessibility, maintained safety codes, and that the station is a fit for the civic center. |
| Electrical Grid Provider | Sets a fixed power supply to the station and requires the station to stay within that supply at all times, even during the busiest hours. |
| Station Operator | Adjusts pricing, ensures the functionality of the station, and manages safety for drivers. |
| Payment Processing Operator | Ensures each transaction flows smoothly across all chargers, ensuring the security of user payments. |

## 4. Operational Scenarios

### Scenario A- Normal Operation 
A driver wants to charge their vehicle, they see an open charger, and the system
lets the driver know if the charger is available. They plug the charger into
their vehicle, then authenticate/pay, at which point charging begins. They wait
in their car or conduct business in City Hall / the Civic Center until their car
is charged to their liking or fully charged, then remove the charger and put it
back into the port. The charging station logs the data and charges the user
accordingly.

### Scenario B- Peak / Busy Hours
After a large event, a high influx of traffic visits the charging station, with
drivers filling each charger. Drivers may find that there is a wait to use the
charging station until another vehicle leaves. The system will show chargers as
unavailable, and the system operator will see that the charging station is at
100% capacity. The system will provide drivers and the operator with an expected
wait time. A line may form in the parking lot, or drivers may park in
non-charger spaces while they wait for a charger to free up. The station
operator will manage the driver queue, ensure that waiting vehicles do not
overflow into the public road, and may assign a waiting area for drivers.

### Scenario C - Charger Failure 
A charger may develop a failure condition in which not enough power is being
output to the vehicle. The software logs the issue, flags the fault, and notifies
a maintenance staff member. The remaining chargers continue operating at full
capacity and remain available to drivers, while the failed charger displays a
notification indicating that it is unavailable.

## 5. Assumptions
- Drivers will arrive at different times, but during peak hours, there may be a wait and some drivers may leave to another charging station if the wait is too long, while some may stay if the wait time is within a reasonable period. 
- The charging times of each driver will vary depending on their own preferences.
- The electrical grid will be able to supply enough power for each charger to operate at full capacity. 
- Drivers will have a form of acceptable payment that allows them to charge their vehicles. 
- Drivers will leave once their charge is done.
- Busy/Peak times will be predictable depending on the event schedule of local event centers.

## 6. Constraints
- The civic center lot may be limited by space for chargers. It can only hold a limited amount of charging stations. (Exact amount to be determined)  
- The capacity of the electrical grid may only be able to supply a limited amount of chargers. (Exact amount to be determined). 
- City ordinances and safety regulations must be adhered to at all times along with public accessibility. 
- The city of Inglewood has limited funding for the chargers, so the costs of operations and building the stations must be within an allocated budget and justified. 

