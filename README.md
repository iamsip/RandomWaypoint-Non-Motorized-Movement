# Random Waypoint Non Motorized Movement

A MATLAB function for simulating the mobility model of a node using the Random Waypoint Model. 

## Function Description

The function `randomWaypoint` simulates the movement of a node based on the Random Waypoint mobility model. The movement speed of the node is determined randomly within a predefined range. If the node crosses a specified boundary, its movement direction is randomized.

### Usage

```matlab
newPosition = randomWaypoint(currentPosition, rxHeight);

Parameters:

currentPosition: A structure containing the node's current position (x, y), distance (d1), angle (phi), and other positional attributes.
rxHeight: The height of the receiver.
Returns:

newPosition: A structure containing the node's updated position and related attributes.
Dependencies
Ensure the myPackageConstant function is accessible and set up to provide the necessary constants such as time and txHeight.
