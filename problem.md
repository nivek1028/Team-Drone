# Problem Statement

##2. General Description of Product
The product is a software that will be used to automatically control a drone. The goal of the software is to get a drone to travel from point a to point b autonomously and back. Once the drone reaches point b it will gather information of its surroundings to help the user determine something specific about the location, for example if there is a lot of contamination in that area, if the structure is still structurally stable, or to deliver an object to said location. The primarily focus of this product will be to make it easier for users to get a drone to travel to different locations since flying a drone requires a considerable amount of time and attention.
##2.1 Context of Product
This product is meant to be used in situations where a person cannot reach easily certain locations, specially if these can be dangerous. The environments that where the team has targeted that the product will be used, are in nature environments and in city environments where it must avoid obstacles such as trees, buildings and animals to reach the intended target location.
##2.2 Domain Model with Description
Display and describe your domain model.
The team is planning on using an object model (UML) because with this we will be able to complete partial views of the structured model of the system before finishing it. this will be essential because it can provide an outline of how the structure of the software must be to be compliant with the requirements established by the group.
##2.3 Product Functions (general)
Some of the product functions are that the software will allow the drone to travel to a destination defined by the user autonomously. This makes it simpler for people to use drones for multiple tasks since flying drones is not a simple thing to master, it requires time and practice to be able to fly a drone properly. Another feature that this will have is that the user can also tell it one of the defined tasks to do once it arrives at the location.

##2.4 User Characteristics and Expectations
Describe your users and their abilities.
The target user for this is any person with a drone and with a computer since that will be used to tell the drone the location where it must travel. Since the flight of the drone will be autonomous there is not much for the user to do, mainly telling the drone the location to travel, choosing what the drone will do at said location and the drone will do it automatically.
##2.5 Constraints
Some constraints that this system will have is the distance of the location since most drones use batteries with 7.4v and the average battery has around 5200mAh. So, the average drone needs around two of these batteries making it 10400mAh, but all of this amperage lasts slightly less than an hour depending on the consumption of the drone. This will make the distance that a user inputs a constraint since it could be to far for the drone to reach while it still has enough battery or it might not be able to finish the task before it runs out.

##2.6 Assumptions and Dependencies
A dependency that the software will have is to the flight controller since the flight controller basically makes quick calculations while the drone is flying to determine if the motors are moving at the same velocity or if one of the motors must increase the velocity to be able to maintain the direction or stability.
##3. Functional Requirements

- the motors turn on
- the drone lifts off the ground.
- the drone can float around without losing control
- The drone can travel in a straight line 
- The drone can move in all directions
- The drone can detect objects
- The drone can interact with a computer
- The drone accepts the software’s input
 
