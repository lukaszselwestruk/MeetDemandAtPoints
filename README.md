Meet Demand At Points System Developed with Unity 2022
I. Implemented Mechanics:

- All data and calculations were done using Scriptable Objects.
- Visualization was implemented on Game Objects.
- Points of sale were set on the scene (3D representation), and upon game start, we generated corresponding logical objects for them.
- Points of sale generated demand for a specific resource at random intervals (the range was set in a Scriptable Object with configuration).
- Player's resources were displayed on the UI layer (2D representation).
- Player's resources were automatically produced at a specified frequency (range set in Scriptable Object configuration).
- The player satisfied demand at a point by selecting the owned resource and the corresponding point (e.g., a simple drag-and-drop). At this moment, a transaction occurred, and the player lost the resource to meet the demand at the point.
- UI elements and 3D elements were in separate autonomous, concurrently running scenes (they were not aware of each other's existence), communicating with each other and the data layer in Scriptable Objects.
