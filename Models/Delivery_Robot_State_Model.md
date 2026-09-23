State-ID|	State Name|	Description|	Entry Condition|	Exit Condition
S1|	IDLE	Robot is switched on and waiting for a delivery request.|	Robot is switched on and ready.|	Delivery request is received.
S2| NAVIGATING	Robot moves toward the destination while continuously checking its surroundings.|	A valid delivery request is received.|	Destination is reached or an obstacle is detected.
S3|	AVOIDING_OBSTACLE	Robot temporarily stops normal navigation and attempts to safely avoid the obstacle.|	An obstacle is detected during navigation.|	Obstacle is cleared and the path is safe.
S4|	DELIVERING	Robot has reached the destination and delivers the package.	Robot reaches the delivery destination.|	Package is successfully delivered.|
S5|	RETURNING	Robot returns to the warehouse after completing the delivery.|	Delivery is completed.|	Robot reaches the warehouse and returns to IDLE..
