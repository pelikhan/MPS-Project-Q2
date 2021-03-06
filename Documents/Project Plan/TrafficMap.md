# Traffic Map 

## Description:

* The user would choose a transportation element (known as a trip mode) and decide which path the transportation element 
should take to finish its route by setting up the traffic rules on the map from building code blocks on the right side of 
the PXT environment;

* On the left side of the PXT environment, we would display a traffic map designed by us as the simulator;
* On the traffic map, there would be roads, street blocks, and buildings as default elements on the map;

* With the designated traffic map, the user could choose which transportation element would be running on the map. 
The options are:
   * Car
      * With options of passenger, ambulance, police, paramedic, fire truck, the are differentiated by appearance;
      * With different types of car transportations, the user can add sound elements on it to make it more interesting;
   * Bicycle;
   * Person;

* Then, the user could set up the action of the transportation element to make it move forward, move backward, 
or make turns on specific path or crossroad, or with specific conditions;

* Also, the user could set up the traffic rules as following with Road Condition attributes:
   * Set up traffic lights on designated crossroads. When a transportation encounters a traffic light, it needs to 
      following the traffic light’s indication to move.
      * Set up the light indicator information with the LED attributes to decide action of the transportation on the crossroad;
      * Set up the light running information with the Control attributes to decide how the light should be running;
   * Set up pedestrians on designated roads. When a transportation encounters pedestrians, it needs to wait until the pedestrians finish crossing to move. 
      * Set up the pedestrians on a road to decide which road would be affected
      * Set up the pedestrians action with the Control attributes to decide how the road would be affected, for example, by how long;
   * Set up road work on designated roads. When a transportation encounters road work ahead, the road cannot be accessible.
      * Set up the road work on a road to decide which road would be affected
      * Set up the road work situation with Control attributes to decide how the road would be affected, for example, by how long;
* After all the set ups on the traffic map, the user could run the program to see if the path that the transportation element would be going through is the path that the user wants.

* Logic category in the middle part *tball comment: note sure what this means*

* Object
   * Car (ambulance, police, paramedic, fire truck) 
   * Bicycle 
   * Person
* Color 
      * Green 
      * red 
      * yellow
* Action 
      * forward 
      * back
      * turn 
* Control  
   * If else 
   * a1/a2
   * Direction (vertical/horizontal)
   * Duration
* LED
   * Up 
   * Down 
   * Left 
   * Right 
   * slow/yield 
   * Stop 
* Sound 
      * beep 
      * Siren 
   * Road condition
      * Road
      * Road work
      * Pedastrian
      * Traffic light
