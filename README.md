//Comic-con parking system
It models real-world parking operations including:

Vehicle and visitor management with access control (VIP, staff, general)
Hierarchical parking structure (zones → levels → spots)
Parking sessions with entry/exit tracking
Ticket generation, fee calculation, and payment processing
Support for reserved spots, permits, and priority-based access

The schema follows relational design best practices with clear 1:N and 1:1 relationships, ensuring data consistency, minimal redundancy, and efficient querying.
Core flows like session → ticket → fee → payment are separated for better scalability, maintainability, and auditability.

//Smart elevator control
This ER diagram represents a smart elevator management system within a building environment. It models how buildings contain multiple floors, elevator shafts, and elevators, while users (such as residents or staff) interact with the system by requesting elevator rides. The system tracks elevator assignments, ride logs, and real-time elevator statuses, ensuring efficient movement between floors. It also includes maintenance records to monitor elevator health and servicing, along with mappings between elevators and the floors they serve. Overall, the design captures the complete lifecycle of elevator operations—from user requests and ride execution to monitoring and maintenance—making it suitable for managing a modern automated elevator system.
