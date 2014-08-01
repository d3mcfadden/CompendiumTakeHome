Compendium Takehome Problem
===========================

The following is a test designed to ensure you have a fundamental understanding of building applications. It is not meant to be challenging, just to qualify your skills and open a conversation.

Please write the code in whatever environment you are comfortable in.  Please fork this repository and provide the link back to your fork.

### Application Requirements:

Write an application that simulates a bank of elevators in a building.  The “UI” for this program can be a command line REPL that listens for instructions and prints out what it is doing.

### The following commands should be implemented in the CLI:

* start program with argument that define number of floors and number of elevators. Ex: ./elevator.py -e 3 -f 10 (bank of 3 elevators in an 10 floor building)
* SEED the program - initialize elevators to random floors
* CALL an elevator to a specific floor with an direction
* ENTER elevator (ENTER N where N is the index of the elevator)
* EXIT elevator
* CLOSE door without exiting
* select destination floor (GO <FLOOR>)
* select MULTIPLE destinations (GO <FLOOR>,<FLOOR>,<FLOOR>)
* WHERE prints the floor the user is on (starts at 1)

### Example User Stories:

* I start out on floor 1
* I call SEED to initialize the elevators to random floors
* I can CALL from floor 1 to go UP - CALL 1 UP
* I can ENTER that elevator and GO to floor 5
* I can get and error message if I attempt to ENTER an elevator that is not available
* I can then EXIT on that floor
* I call WHERE and am told what floor I am on floor 5
* I can CALL the elevator to floor 5 to go down
* I can GO to floors 4,3,2 and 1 on the way down
* I can CLOSE the door without exiting to continue to my next floor

Please focus on making your code readable, testable and maintainable.  Those are the three most important parts of this exercise.
