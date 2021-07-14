# the problem is : why this error comes when i try to using joint state publisher with Rviz in noetic ?

### this error appear:

<p><code>ERROR: cannot launch node of type [robot_state_publisher/state_publisher]: Cannot locate node of type [state_publisher] in package [robot_state_publisher]. Make sure file exists in package path and permission is set to executable (chmod +x)</code></p>

![Screenshot (71)](https://user-images.githubusercontent.com/56357074/125690408-9c2c943d-7f91-438a-91dd-229e339f2e19.png)

https://user-images.githubusercontent.com/56357074/125701124-2672fbfc-1603-4d5c-b4d9-d445b111bdb8.mp4

# the solution of this problem is : 

#### go to launch file and change any ```state_publisher``` with ```robot_state_publisher``` because a ```state_publisher``` is Because this name has been discontinued

![Screenshot (72)](https://user-images.githubusercontent.com/56357074/125701725-3bb3e501-42c1-44f6-b09e-951da077744d.png)


#### so , i will go to ```check_motors.launch``` and change any ```state_publisher``` to ```robot_state_publisher``` and then will work 






https://user-images.githubusercontent.com/56357074/125701086-ce1465f7-0459-473c-847d-315577e0689e.mov


