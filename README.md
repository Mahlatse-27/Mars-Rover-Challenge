# Mars-Rover-Challenge

# Description

The project is about robotic rovers on Mars used to navigate in a rectangular plateau. Objective is to get the complete view of the terrain to send back to Earth ass they are moved around the terrain by NASA.

# Installations

> Java JDK
>> Download java-jdk.exe
>> Install java-jdk.exe

> Eclipse
>> Download eclipse.exe
>> Install eclipse.exe 
>> On Eclipse Installer Oomph, pick Eclipse for Jva Developers

# Tutorial
![Screenshot (561)](https://user-images.githubusercontent.com/44344718/104879864-4dff1b80-5967-11eb-87f0-421f1f674e4a.png)


# Code Documentation
### Methods:
 > 1. movement_of_rover(int width, int height, String[] rover_pos_arr, String rover_mov):
##### Description
	- Method perforns all the new directions and movements that the rover must take to navigate around the terrain
##### Parameters
    - width : first integer, width of the plateau
    - height : second integer, height of the plateau
    - rover_pos_arr : String array, containing the x & y coordinates and the direction of the rover
    - rover_mov : String, with a new position and direction of the rover
##### Returns
	- String with new position and direction of the rover
> 2. rover_within_bounds(int width, int height, int rover_x, int rover_y)
##### What Function Does
	- Checks if the rover's is outside or inside the plateau.
##### Parameters
    - width : first integer
    - height : second integer
    - rover_x : third integer
    - rover_y : fourth integer
##### Returns
	- True, if the rover is out of bounds and false otherwise

> 3. string_splitter(String line)
##### What Function Does
	- splits a string using a space as the regular expression
##### Parameters
    - line : String
##### Returns
	- String array

# Assumptions

1. Input will always be correct, it will follow the given standard
2. Plateau will always have two rovers

# Contacts
#### Email : millieniummorapedi0212@gmail.com
#### github : https://github.com/Mahlatse-27/Mars-Rover-Challenge
