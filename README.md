# the problem is : why this error comes when i try to using joint state publisher with Rviz in noetic ?
#### this error appear:`
<p><code>ERROR: cannot launch node of type [robot_state_publisher/state_publisher]: Cannot locate node of type [state_publisher] in package [robot_state_publisher]. Make sure file exists in package path and permission is set to executable (chmod +x)</code></p>


# the solution of this problem is : 

#### go to launch file and change any ```state_publisher``` with ```robot_state_publisher``` because a ```state_publisher``` is Because this name has been discontinued
### so , i will go to ```check_motors.launch``` and change any ```state_publisher``` to ```robot_state_publisher``` and then will work 
