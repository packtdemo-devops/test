Solution :

We can think of the movement of leftward and rightward particles separately. Picture two arrays of 'X' and '.', where an 'X' represents a particle moving in that direction and a '.' represents the absence of a particle.
We can more easily represent the 'X's and '.'s as 0s and 1s. Furthermore, an array of 0s and 1s is simply a binary representation of a number. We can model the movement of leftward and rightward particles by performing bitwise operations on these numbers. 
We can also check the 'animation' of the tube at any time by performing a bitwise or on the leftward and rightward numeric representations, since a bitwise or will check whether any type of particle is in each position.


Java Definition 
 
Class: Animation 
 
Method: animate 
 
Method signature: 
 
 public String[] animate(int speed, String init) Your method should be public 
   
Function signature: 
 
vector<string> animate(int speed, const string& init) 
