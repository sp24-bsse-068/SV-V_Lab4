Req-ID|	Requirement|	Description|	Priority|
R1|	The robot shall enter Idle state when it is switched on and remain there until a valid delivery request is received.|	Defines the robot's initial behavior.|	High
R2|	The robot shall start navigation toward the specified destination when a valid delivery request is received while it is idle.|	Initiates a delivery journey.|	High
R3|	The robot shall continuously monitor its surroundings while navigating toward the destination.|	Allows the robot to detect obstacles during movement.|High	
R4|	When an obstacle is detected during navigation, the robot shall stop normal navigation and enter Obstacle-Avoidance mode.|	Prevents the robot from continuing into an obstacle.|	High
R5|	The robot shall resume navigation toward the destination after successfully avoiding the detected obstacle.|	Returns the robot to its original delivery journey.|	High
R6|	When the robot reaches the destination, it shall start the package delivery process.|	Begins delivery only after reaching the correct destination.|	High
R7|	The robot shall begin returning to the warehouse only after the package has been successfully delivered.|	Ensures the return journey follows successful delivery.|	High
R8|	The robot shall continuously monitor its battery level during navigation and return to the warehouse when the battery reaches a critical level.|	Protects the robot from becoming stranded due to low battery.|	High
R9|	The robot shall enter Idle state after reaching the warehouse and shall wait for a new delivery request.|	Completes the current journey and prepares for another request.|	High
R10|	The robot shall prevent the delivery process from starting unless it has received a valid delivery request, reached the destination, and is not in Obstacle-Avoidance mode.|	Enforces restrictions on invalid delivery-state transitions.|High	
