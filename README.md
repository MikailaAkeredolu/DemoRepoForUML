![ProductTheme drawio](https://user-images.githubusercontent.com/10773482/191823842-cb6f2f6c-7726-466f-a0f1-d980ea9abdec.png)

# Homework 1

### All Vehicles pay a 15% tax
### RollerCoater rides pay 20% tax

-  Instantiate 4 Type of Vehicle objects: Car, Truck,  Bike and a RollerCoaster object in main
-  Create an Array of Vehicles to store your vehicle objects in main
-  Invoke the printVehicleNamesAndPrices to print the names and prices of the vehicles in main
- Create an Array of Rideable objects to store your Rideable rides and store only rideable objects in main
- Invoke the getSpeedOfRideableObjects() in main
- Invoke the totalAfterTax in main
- Invoke the totalBeforeTax in main


# Homework 2

### Part 1 - Create the following classes:

- Create a PC class that HAS a Case , Motherboard and a Monitor

- Create a parameterized constructor for PC containing all of its instance variables

- Create a drawLogo() method that is private , that takes and returns nothing but inside the method, invokes/calls the drawPixel(x,y,z) method on the monitor instance variable in the PC class

- Create a public method called description() that takes and returns nothing but prints out the description of the case, monitor and motherboard but starting with the message
 "Welcome to worst buy below is the description of the pc on sale today"


- Make sure all objects can be printed using the String representation of an object

- Create a powerUp() method that is public and returns nothing but inside the method invoke/call the pressPowerButton() method on theCase and after that it calls/invoke the drawLogo() method then right after that it invokes the​ loadProgram() method on the motherBoard ​ivar

### Part 2 - Monitor class:


- Create a Monitor class that HAS a Resolution  and consist of a model and manufacturer as well.(All instance variables)

- Create a void drawPixel(int x, int y, String color) with the following parameters and simply print out "Drawing pixel at " + x + "," + y + " " + " in color "+ color. (use this code inside the method)

### Part 3 - Resolution class:


- Create a Resolution class with these two properties width and height.Private int width; int height;
- Make sure you add all that is necessary, getters, setters etc..

### Part 4 - MotherBoard class:


- Create the following instance variables, fields or properties private String model; String manufacturer, int ramSlots; int cardSlots; String bios;

- Create a loadProgram()method that returns nothing and accepts a parameter called programName as an argument. Inside the method just print out - programName is now running by using the programName argument passed to it

### Part 5 - Case class:

- Create the following private properties/ivars as well as getters String model; String manufacturer; String powerSupply; Dimensions dimensions;

### Part 6 - Dimension class:
- Create the following properties/instance variables as well as getters, constructors...int width; int height; int depth;

### Part 7 - Main class:
- Create an instance/Object of Type PC
- Call the description() method on the pc object3 
- Invoke the powerUp() method method on the pc object

