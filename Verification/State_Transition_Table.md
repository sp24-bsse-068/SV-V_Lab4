Transition-ID|	From State|	Event / Condition|	To State|	Requirement
E1|	IDLE|	Delivery Request Received|	NAVIGATING|	The robot shall start navigation when a valid delivery request is received.
E2|	NAVIGATING|	Obstacle Detected|	AVOIDING_OBSTACLE|	The robot shall detect obstacles while navigating and enter obstacle avoidance mode.
E3|	AVOIDING_OBSTACLE|	Obstacle Avoided|	NAVIGATING|	The robot shall resume navigation when the obstacle is safely avoided.
E4|	NAVIGATING|	Destination Reached|	DELIVERING|	The robot shall enter the delivery state when it reaches the destination.
E5|	DELIVERING|	Delivery Successful|	RETURNING|	The robot shall start returning to the warehouse after successfully delivering the package.
E6|	RETURNING|	Warehouse Reached|	IDLE|	The robot shall return to the idle state when it reaches the warehouse.
E7|	NAVIGATING|	Critical Battery|	RETURNING|	The robot shall stop normal navigation and return to the warehouse when a critical battery condition is detected..
