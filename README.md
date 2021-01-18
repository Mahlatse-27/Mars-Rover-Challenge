# Mars-Rover-Challenge

# Description

The project is about 2 robotic rovers on Mars used to navigate in a rectangular plateau. Objective is to get the complete view of the terrain to send back to Earth as they are moved around the terrain by NASA. Rover's position is determined by the x and y coordinates. 

# Installations

> Java JDK
>> Download java-jdk.exe
>> Install java-jdk.exe

> Eclipse
>> Download eclipse.exe
>> Install eclipse.exe 
>> On Eclipse Installer Oomph, pick Eclipse for Jva Developers

# Tutorial
##### Installing Java JDK
![Screenshot (561)](https://user-images.githubusercontent.com/44344718/104879864-4dff1b80-5967-11eb-87f0-421f1f674e4a.png)
### Installing Eclipse IDE
![Screenshot (557)](https://user-images.githubusercontent.com/44344718/104880422-31afae80-5968-11eb-8b2d-bc68391b2bf2.png)
### I used Java, thus I had to choose Eclipse for Java Developers
![Screenshot (558)](https://user-images.githubusercontent.com/44344718/104880409-2eb4be00-5968-11eb-8f2d-bce91d8b4f0c.png)
### Since it is an already existing project it has to be imported
![Screenshot (564)](https://user-images.githubusercontent.com/44344718/104880209-d5e52580-5967-11eb-804e-7b359984d83c.png)
![Screenshot (565)](https://user-images.githubusercontent.com/44344718/104880939-21e49a00-5969-11eb-994d-f4662d411fe0.png)
![Screenshot (566)](https://user-images.githubusercontent.com/44344718/104880223-da114300-5967-11eb-8b6a-5182c1395d7b.png)
### Browse through foloders and select Mars-Rovers-Challenge folder then click finish and finally run the program

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
##### Description
	- splits a string using a space as the regular expression
##### Parameters
    - line : String
##### Returns
	- String array

# Assumptions

1. Input will always be correct, it will follow the given standard
2. Plateau will always have two rovers
3. Plateau will always be a 2D-Plane
4. Rovers will never get directions such as 'NW'/'SE' and the rest

# Contacts
#### Email : millieniummorapedi0212@gmail.com
#### github : https://github.com/Mahlatse-27/Mars-Rover-Challenge
